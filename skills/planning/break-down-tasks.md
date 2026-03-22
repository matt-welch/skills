---
name: break-down-tasks
category: planning
description: Decompose a large feature or project into actionable tasks and subtasks
applicability: general
---

# Skill: Break Down Tasks

## Description

Take a high-level feature description or project goal and decompose it into a prioritized list of actionable tasks suitable for tracking in an issue tracker or sprint board.

## Usage

Provide a feature description or goal, and this skill will produce:

- **Epic / Parent task** – the top-level deliverable
- **User stories** – from the user's perspective where applicable
- **Tasks** – concrete, independent units of work
- **Subtasks** – finer-grained steps within each task
- **Dependencies** – ordering constraints between tasks

## Example Prompts

- "Break down the work for adding multi-tenancy to our SaaS app."
- "What tasks are needed to migrate our CI pipeline from Jenkins to GitHub Actions?"
- "Decompose the work for implementing a caching layer in front of our database."

## Notes

- Aim for tasks that can be completed by a single developer in one to three days.
- Surface risks or unknowns as explicit research or spike tasks.
- Group tasks by component or team when the work spans multiple areas.
