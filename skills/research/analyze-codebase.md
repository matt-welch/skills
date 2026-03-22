---
name: analyze-codebase
category: research
description: Provide a structured overview and analysis of an unfamiliar codebase
applicability: general
---

# Skill: Analyze Codebase

## Description

Explore and summarize an unfamiliar codebase to quickly answer questions like: what does it do, how is it organized, what are the key components, and what are the most notable design decisions or problem areas.

## Usage

Provide access to the repository (or relevant files) and any specific questions. This skill will produce:

- **Project summary** – purpose, language(s), and major frameworks
- **Directory structure** – roles of key directories and files
- **Core components** – the most important modules, classes, or services and how they interact
- **Data flow** – how data enters, is processed, and exits the system
- **Notable patterns** – design patterns, abstractions, or conventions used
- **Technical debt or risks** – areas that are complex, poorly tested, or likely to cause issues

## Example Prompts

- "Give me a high-level overview of this repository before I start contributing."
- "Where is the authentication logic in this codebase?"
- "What are the riskiest parts of this legacy system?"

## Notes

- Start with entry points (main files, routers, CLI commands) to understand the control flow.
- Map component dependencies to identify tightly coupled or frequently changed areas.
