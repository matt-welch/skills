---
name: investigate-dependencies
category: research
description: Audit, evaluate, and recommend project dependencies
applicability: general
---

# Skill: Investigate Dependencies

## Description

Audit the project's dependency tree to identify outdated packages, known vulnerabilities, license issues, and opportunities to reduce bundle size or complexity.

## Usage

Provide the dependency manifest (e.g., `package.json`, `requirements.txt`, `go.mod`, `pom.xml`). This skill will:

- List **outdated packages** and their latest available versions
- Flag **known security vulnerabilities** (CVEs) with severity ratings
- Identify **license conflicts** or restrictive licenses that may affect distribution
- Highlight **unused or redundant dependencies** that can be removed
- Recommend **lighter alternatives** where applicable

## Example Prompts

- "Audit our `package.json` for vulnerabilities and outdated packages."
- "Are there any GPL-licensed dependencies that could cause issues for our commercial product?"
- "Which of our Python dependencies have known CVEs and how urgent are they?"

## Notes

- Cross-reference findings with the official advisory databases (e.g., GitHub Advisory Database, NVD).
- Prioritize fixes by severity—critical and high vulnerabilities should be addressed immediately.
- Test the application after any dependency upgrade to catch breaking changes.
