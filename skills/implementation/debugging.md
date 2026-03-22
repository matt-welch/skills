---
name: debugging
category: implementation
description: Systematically diagnose and fix bugs in code
applicability: general
---

# Skill: Debugging

## Description

Systematically diagnose the root cause of a bug or unexpected behavior and propose a targeted fix. The skill applies structured reasoning rather than trial-and-error patching.

## Usage

Provide the failing code, error message, stack trace, and any reproduction steps. This skill will:

1. **Understand the symptom** – what is observed vs. what is expected
2. **Trace the execution path** – walk through the code to find where behavior diverges
3. **Identify the root cause** – the underlying defect, not just the surface error
4. **Propose a fix** – the minimal change that resolves the root cause
5. **Suggest a regression test** – a test that would catch this bug in the future

## Example Prompts

- "My API returns a 500 error on this request. Here's the stack trace."
- "This sorting function produces incorrect output for duplicate values—why?"
- "After the last deployment, memory usage climbs until the process crashes."

## Notes

- Always fix the root cause, not just the symptom.
- Add a test that reproduces the bug before applying the fix.
- Note any related areas of the code that could harbor similar defects.
