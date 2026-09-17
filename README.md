# Job Applier Multi-Agent System (JAMS)

A security-first, human-supervised multi-agent platform for AI-assisted job discovery, CV optimisation, and application automation.

## Vision

JAMS helps candidates manage repetitive aspects of the job application process while retaining human control over critical decisions.

The platform is designed around:

- Local-first AI execution
- Human-in-the-loop approvals
- Security by design
- Explainable recommendations
- Prompt-injection resistance
- Browser automation isolation

## Planned Features

### Job Search Agent

Finds opportunities matching user-defined criteria.

### Evaluation Agent

Scores and ranks opportunities using configurable rules and AI-assisted analysis.

### CV Agent

Suggests small, ATS-friendly improvements while preserving accuracy.

### Cover Letter Agent

Generates tailored cover letters for review.

### Form Agent

Assists with application form completion.

### Review Agent

Introduces approval gates before any significant action.

### Orchestrator Agent

Coordinates workflow between specialised agents.

## Technology Stack

- Java 21
- Spring Boot
- Spring AI
- PostgreSQL
- Playwright
- Docker
- Ollama
- Claude Desktop (optional)

## Security Principles

- Human approval before application submission
- No secrets within prompts
- Browser isolation
- Least-privilege agent permissions
- Job descriptions treated as untrusted input
- Prompt-injection mitigation

## Status

Project planning and architecture phase.
