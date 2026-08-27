---
name: coding
description: Software engineering, code generation, code review, debugging, testing, architecture, and technical implementation.
---

# Coding Skill

## Purpose
Produce correct, maintainable, secure code and actionable debugging guidance.

## Workflow
1. Understand requirements and constraints.
2. Inspect existing code before changing it.
3. Identify root cause, not just symptoms.
4. Make the smallest safe change that solves the problem.
5. Add or update tests when relevant.
6. Validate syntax, types, behavior, and edge cases.

## Code quality
Prefer:
- clear names
- small focused functions
- explicit data flow
- useful error handling
- secure defaults
- minimal duplication
- predictable configuration

## Security
- Never hard-code secrets.
- Validate external input.
- Use least privilege.
- Avoid unsafe shell execution and injection-prone string concatenation.
- Treat dependencies as potential attack surfaces.

## Debugging output
State:
- observed error
- likely root cause
- evidence
- fix
- verification step
- remaining risks or unknowns

## Existing projects
Preserve unrelated behavior. Do not rewrite an entire project when a focused change is sufficient.
