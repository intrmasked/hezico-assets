# Hezico Assets

## Project Overview
A library of reusable templates and assets for Hezico. This repo contains production-ready templates that can be used across Hezico projects.

## Structure
- `templates/` - Reusable prompt-ready templates (documentation, processes, etc.)
- Each template lives in its own subdirectory under `templates/`

## LLM Universality — Critical Rule
All templates in this repo MUST be LLM-agnostic. They are designed to be dropped into ANY large language model (Claude, ChatGPT, Gemini, Copilot, Llama, Mistral, etc.) and produce consistent, high-quality output.

Rules for template authorship:
- No LLM-specific syntax, system prompts, or tool references
- Use plain Markdown with clear section headers and placeholder syntax
- Placeholders use `{{PLACEHOLDER_NAME}}` format — universally understood
- Instructions within templates should be written as plain English directives
- Each template must include a `README.md` explaining what it does, what to paste where, and what output to expect
- Templates should be self-contained: one file = one complete prompt, no chaining required
- Include example input/output where helpful so any LLM understands the expected format

## Template Categories
- `templates/documentation/` — Documentation generation templates (story docs, technical specs, etc.)
- `templates/code/` — Code generation and review templates
- `templates/process/` — Process and workflow templates

## Conventions
- All templates are Markdown (`.md`) files
- Each template directory contains a `README.md` (usage guide) and the template file(s)
- Keep templates focused — one template = one job
- Templates should work with zero context about Hezico internals unless the user pastes it in

## Code Style (for any code templates)
- 2-space indentation
- Use semantic HTML elements
- CSS: BEM-like naming or utility classes, mobile-first responsive design
- JS: ES6+ modules, no jQuery
