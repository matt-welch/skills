---
name: estimate-effort
category: planning
description: Estimate the effort and complexity of a task or set of tasks
applicability: general
---

# Skill: Estimate Effort

## Description

Analyze a task or set of tasks and produce effort estimates with supporting reasoning. Estimates are expressed as story points, T-shirt sizes, or time ranges depending on the team's preference.

## Usage

Provide one or more tasks, and this skill will:

- Assess **complexity** – number of moving parts, unknowns, and cross-cutting concerns
- Assess **effort** – expected developer time, accounting for testing and review
- Identify **risk factors** – external dependencies, unclear requirements, or technical debt
- Produce a **confidence level** – how certain the estimate is given available information

## Example Prompts

- "How long would it take to add full-text search to our product catalog?"
- "Estimate the effort to containerize our monolith with Docker."
- "Give me story-point estimates for the tasks in our upcoming sprint."

## Notes

- Always pair estimates with stated assumptions; estimates are only as good as the information provided.
- Flag tasks with high uncertainty as candidates for a time-boxed investigation spike.
