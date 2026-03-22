---
name: write-tests
category: implementation
description: Generate unit, integration, or end-to-end tests for a given piece of code
applicability: general
---

# Skill: Write Tests

## Description

Generate a comprehensive test suite for a given function, class, module, or API endpoint. Tests are idiomatic for the target language and framework, and cover the happy path, edge cases, and error conditions.

## Usage

Provide the code under test and any existing test examples for style guidance. This skill will produce tests covering:

- **Happy path** – correct behavior with valid inputs
- **Edge cases** – boundary values, empty inputs, large inputs
- **Error conditions** – invalid inputs, exception handling, failure modes
- **Side effects** – database writes, external calls, event emissions (mocked as needed)

## Example Prompts

- "Write unit tests for this `parseCSV` function in Python using pytest."
- "Generate Jest tests for this React component."
- "Add integration tests for the `/users` REST endpoint."

## Notes

- Follow the Arrange-Act-Assert (AAA) pattern for clarity.
- Use mocks and stubs for external dependencies to keep unit tests fast and isolated.
- Aim for tests that document intent—test names should read like specifications.
