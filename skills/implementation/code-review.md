---
name: code-review
category: implementation
description: Review code changes for correctness, style, security, and maintainability
applicability: general
---

# Skill: Code Review

## Description

Perform a thorough review of code changes—whether a diff, pull request, or inline snippet—and provide structured feedback covering correctness, style, security, performance, and maintainability.

## Usage

Provide the code or diff to review, along with any relevant context (language, framework, coding standards). This skill will produce feedback organized by severity:

- **Critical** – bugs, security vulnerabilities, or data-loss risks that must be fixed
- **Major** – logic errors, performance problems, or violations of key architectural rules
- **Minor** – style issues, naming inconsistencies, or small improvements
- **Suggestion** – optional enhancements or alternative approaches worth considering

## Example Prompts

- "Review this pull request and flag any bugs or security issues."
- "Check this Python function for correctness and PEP 8 compliance."
- "Does this database migration look safe to run in production?"

## Notes

- Be specific: reference line numbers or snippets when raising concerns.
- Explain *why* an issue matters, not just what should change.
- Acknowledge good patterns alongside problems to provide balanced feedback.
