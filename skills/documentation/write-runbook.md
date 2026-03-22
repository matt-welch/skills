---
name: write-runbook
category: documentation
description: Create an operational runbook for a service or process
applicability: general
---

# Skill: Write Runbook

## Description

Produce a step-by-step operational runbook for a service, deployment, incident response procedure, or routine maintenance task. Runbooks enable any team member—not just the original author—to carry out the process safely and correctly.

## Usage

Provide the service or process name and a description of the steps involved. This skill will structure the runbook with:

- **Overview** – purpose and scope of the runbook
- **Prerequisites** – required access, tools, and knowledge
- **Procedure** – numbered, copy-paste-friendly steps
- **Validation** – how to verify each step succeeded
- **Rollback** – steps to undo changes if something goes wrong
- **Escalation** – when and how to escalate if the runbook doesn't resolve the issue

## Example Prompts

- "Write a runbook for deploying a new version of our API service."
- "Create an incident response runbook for a database failover."
- "Document the steps for rotating our API keys."

## Notes

- Use imperative language ("Run", "Navigate to", "Verify") to make steps unambiguous.
- Include expected outputs and screenshots where helpful.
- Keep the runbook up to date as the system evolves; treat it as living documentation.
