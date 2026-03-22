---
name: evaluate-technology
category: research
description: Compare and evaluate technology options for a given requirement
applicability: general
---

# Skill: Evaluate Technology

## Description

Research and compare technology options—libraries, frameworks, databases, cloud services, or architectural patterns—for a given requirement, and provide a structured recommendation with trade-offs.

## Usage

Provide the requirement or problem statement and any constraints (e.g., language, existing stack, team familiarity, budget). This skill will:

- Identify **candidate options** relevant to the requirement
- Evaluate each option against criteria such as maturity, community, performance, licensing, and cost
- Summarize **trade-offs** for each option
- Provide a **recommendation** with justification
- Flag **deal-breakers** (e.g., licensing incompatibilities, end-of-life status)

## Example Prompts

- "We need a message queue. Compare Kafka, RabbitMQ, and AWS SQS for our use case."
- "Which ORM should we use for a new Python microservice?"
- "Evaluate managed Kubernetes offerings across AWS, GCP, and Azure."

## Notes

- Weight evaluation criteria by what matters most for the project (e.g., operational simplicity may outweigh raw performance for a small team).
- Include links or references to benchmarks, documentation, and community resources.
