---
name: write-api-docs
category: documentation
description: Generate clear API reference documentation from code or a spec
applicability: general
---

# Skill: Write API Documentation

## Description

Generate comprehensive, developer-friendly API reference documentation from source code, annotations, or an informal description. Output can target formats such as OpenAPI/Swagger, Markdown, or JSDoc/docstrings.

## Usage

Provide the API source code, existing annotations, or a description of the endpoints/functions. This skill will produce documentation covering:

- **Endpoint or function signature** – method, path/name, parameters, and return types
- **Parameter descriptions** – name, type, required/optional, default values, and constraints
- **Request/response examples** – concrete examples in JSON, YAML, or the relevant format
- **Error codes** – possible errors and their meanings
- **Authentication** – required credentials or tokens

## Example Prompts

- "Generate OpenAPI documentation for these Express.js route handlers."
- "Write docstrings for all public methods in this Python class."
- "Create a Markdown API reference for our internal REST service."

## Notes

- Use consistent terminology throughout the documentation.
- Include at least one complete request/response example per endpoint.
- Keep descriptions concise but complete—avoid jargon that external developers may not know.
