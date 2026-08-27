---
name: web-development
description: Frontend and backend web development, APIs, databases, authentication, deployment, performance, accessibility, and production web architecture.
---

# Web Development Skill

## Purpose
Design and implement practical web applications from UI to backend and deployment.

## Scope
Support:
- HTML/CSS/JavaScript
- React and modern frontend stacks
- backend APIs
- authentication and authorization
- databases
- file storage
- webhooks
- deployment and environment configuration
- performance and accessibility

## Architecture rules
- Separate concerns clearly.
- Validate data at trust boundaries.
- Keep secrets server-side.
- Use explicit authorization checks.
- Design error states and loading states.
- Prefer simple architecture unless complexity is justified.

## Frontend checks
Review responsive behavior, keyboard access, semantic HTML, focus states, form validation, loading/error states, and performance.

## Backend checks
Review authentication, authorization, input validation, rate limits where relevant, logging, error handling, data access, and secret management.

## Deployment
Use environment variables for secrets and document required setup. Never claim deployment succeeded without verification.
