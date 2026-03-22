---
name: refactoring
category: implementation
description: Identify and apply refactoring opportunities to improve code quality
applicability: general
---

# Skill: Refactoring

## Description

Analyze existing code and apply targeted refactoring techniques to improve readability, reduce duplication, improve testability, and align with design principles—without changing external behavior.

## Usage

Provide the code to refactor along with any goals or constraints (e.g., must stay backward compatible, target language version). This skill will:

- Identify **code smells** – duplication, long methods, large classes, deep nesting, etc.
- Suggest or apply **refactoring techniques** – extract method, introduce abstraction, simplify conditionals, etc.
- Preserve **external behavior** – all public contracts remain unchanged
- Highlight **test coverage gaps** that should be addressed before or after refactoring

## Example Prompts

- "Refactor this 200-line function into smaller, testable units."
- "The `UserService` class has too many responsibilities. How should it be split?"
- "Simplify this deeply nested conditional logic."

## Notes

- Refactoring should be done in small, verifiable steps—not as one large rewrite.
- Ensure adequate test coverage exists before starting to avoid regressions.
- Document the rationale for structural changes so reviewers understand the intent.
