# Skills

Skill definitions for use with AI coding assistants such as GitHub Copilot and Claude. Each skill describes a common software-development activity, how to invoke it, and what output to expect.

## Inventory

Skills are organized into categories. Each file lives under `skills/<category>/`.

### Planning

| Skill | File | Description |
|-------|------|-------------|
| Create Technical Specification | [`skills/planning/create-technical-spec.md`](skills/planning/create-technical-spec.md) | Draft a structured technical spec for a feature or system |
| Break Down Tasks | [`skills/planning/break-down-tasks.md`](skills/planning/break-down-tasks.md) | Decompose a large feature or project into actionable tasks and subtasks |
| Estimate Effort | [`skills/planning/estimate-effort.md`](skills/planning/estimate-effort.md) | Estimate the effort and complexity of a task or set of tasks |

### Implementation

| Skill | File | Description |
|-------|------|-------------|
| Code Review | [`skills/implementation/code-review.md`](skills/implementation/code-review.md) | Review code changes for correctness, style, security, and maintainability |
| Refactoring | [`skills/implementation/refactoring.md`](skills/implementation/refactoring.md) | Identify and apply refactoring opportunities to improve code quality |
| Debugging | [`skills/implementation/debugging.md`](skills/implementation/debugging.md) | Systematically diagnose and fix bugs in code |
| Write Tests | [`skills/implementation/write-tests.md`](skills/implementation/write-tests.md) | Generate unit, integration, or end-to-end tests for a given piece of code |

### Research

| Skill | File | Description |
|-------|------|-------------|
| Investigate Dependencies | [`skills/research/investigate-dependencies.md`](skills/research/investigate-dependencies.md) | Audit, evaluate, and recommend project dependencies |
| Analyze Codebase | [`skills/research/analyze-codebase.md`](skills/research/analyze-codebase.md) | Provide a structured overview and analysis of an unfamiliar codebase |
| Evaluate Technology | [`skills/research/evaluate-technology.md`](skills/research/evaluate-technology.md) | Compare and evaluate technology options for a given requirement |

### Documentation

| Skill | File | Description |
|-------|------|-------------|
| Write API Documentation | [`skills/documentation/write-api-docs.md`](skills/documentation/write-api-docs.md) | Generate clear API reference documentation from code or a spec |
| Update README | [`skills/documentation/update-readme.md`](skills/documentation/update-readme.md) | Create or improve a project README to help new contributors get started |
| Write Runbook | [`skills/documentation/write-runbook.md`](skills/documentation/write-runbook.md) | Create an operational runbook for a service or process |

## Skill File Format

Each skill is defined in a Markdown file with YAML front matter:

```markdown
---
name: skill-name
category: <planning|implementation|research|documentation|...>
description: One-line description of what the skill does
applicability: <general|repo-specific>
---

# Skill: <Skill Name>

## Description
...

## Usage
...

## Example Prompts
...

## Notes
...
```

## Contributing

To add a new skill:

1. Choose the appropriate category (`planning`, `implementation`, `research`, `documentation`, or a new category if none fits).
2. Create a new Markdown file under `skills/<category>/<skill-name>.md` following the format above.
3. Add a row to the inventory table in this README.
4. Open a pull request with a brief description of the skill and its intended use.
