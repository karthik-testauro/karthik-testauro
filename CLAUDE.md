# CLAUDE.md

Repository-specific instructions for Claude Code when working in this GitHub portfolio. Apply these standards alongside higher-priority instructions and applicable security policies.

## 1. Repository Purpose

This repository is the GitHub profile portfolio for **Karthik Kodati** (`karthik-testauro`). It exists to present professional identity and link to real engineering work.

- The only deliverables in this repository are `README.md`, the profile banner (`karthik-github-banner.png`), this file, and supporting profile assets.
- Playwright frameworks, AI testing tools, and any other substantial project live in **separate repositories**. Do not build application or framework code here.
- Link completed projects into the profile README. Do not reference or describe repositories that are unfinished, private, or not yet published.
- Do not make speculative claims about work in progress.

## 2. Professional Identity and Branding

Position Karthik as an experienced **Quality Engineering Architect**: Senior SDET, Test Automation Architect, and practitioner of AI-assisted quality engineering.

Areas of expertise to represent accurately:

- Playwright with TypeScript
- Enterprise test automation architecture
- UI, API, and integration testing
- Page Object Model and custom fixtures
- Parallel execution and CI/CD
- REST and SOAP API validation
- AI agents for quality engineering
- Quality governance and release engineering

Writing style rules:

- Authoritative, technically credible, and human. Write as a senior engineer would, not as marketing copy.
- Prioritize engineering evidence over decorative presentation. A linked repository with tests and CI says more than an adjective.
- Avoid hype words, superlatives, and inflated claims. No "world-class", "cutting-edge", "revolutionary".
- Keep sentences direct. Prefer concrete nouns and verbs over abstractions.

## 3. GitHub Portfolio Standards

- Maintain a premium, minimalist visual identity. Fewer elements, well chosen, consistently styled.
- **Keep the existing banner** (`karthik-github-banner.png`) unless a replacement is explicitly approved by Karthik.
- Highlight real repositories and demonstrable engineering work. Every project mention must point to something that exists and can be inspected.
- **Never fabricate** GitHub statistics, achievements, metrics, badges, contribution counts, stars, awards, or projects.
- Do not add stat cards, streak widgets, or trophy images that generate numbers the profile does not substantiate.
- Technology badges may be used only for technologies Karthik actually works with.
- Before editing `README.md`, read it in full. Preserve the existing structure unless a restructure is requested.

## 4. Engineering Standards

These engineering standards should be adapted into the individual CLAUDE.md files of future Playwright, TypeScript, and AI quality engineering repositories. Instructions in this profile repository do not automatically apply to separate repositories.

- Prefer **Playwright** and **TypeScript** with a modular architecture.
- Apply **SOLID** principles where they improve clarity and maintainability. Do not over-abstract small projects.
- Use reusable fixtures, clear abstractions (Page Objects, API clients, data builders), and reliable, explicit assertions.
- Maintain strong error handling, strict test isolation, and consistent code quality (linting, formatting, type safety).
- Avoid flaky patterns: hard-coded waits, shared mutable state between tests, order-dependent tests.
- Every real engineering project must include meaningful tests, documentation (README with setup and usage), and a CI workflow that runs the suite.
- Treat test frameworks as production-grade software.

## 5. AI-Assisted Development

- Use AI to support test design, implementation, debugging, and documentation. The engineer remains accountable for the result.
- **Never describe experimental AI capabilities as production-ready.** Research, prototypes, and experiments must be labelled as such.
- **Verify generated code and tests before reporting success.** Run them. If something could not be run or verified, say so explicitly.
- Clearly distinguish **implemented** features from **planned** features in all READMEs, summaries, and commit messages.
- Do not claim a tool, agent, or workflow works unless it has been executed and its output inspected.

## 6. Security and Confidentiality

- Never publish credentials, tokens, API keys, secrets, connection strings, or private information of any kind.
- Never reproduce confidential employer or client source code, test data, business logic, or internal documentation.
- Do not name clients, employers, or internal systems in a way that discloses non-public information.
- Use synthetic examples and publicly available demo applications for all demonstrations.
- Before committing, check that no file contains secrets or private data.

## 7. Git and GitHub Governance

- **Inspect the current branch and working-tree status** (`git status`, `git branch`) before making any change.
- Work on **feature branches** for substantive changes. Do not make substantive edits directly on `main`.
- **Never force-push.** Never rewrite published history.
- **Never commit or push without Karthik's explicit approval.** Stage and present changes; wait for a clear "commit" or "push" instruction.
- Prefer **pull requests** for reviewable changes.
- After any modification, provide a clear summary: what changed, why, and how it was validated (diff, status, test output where relevant).
- Commit messages: imperative mood, concise subject, body explaining intent when non-trivial.

## 8. Collaboration Rules

- **Explain architectural decisions before substantial implementations.** Present the approach, trade-offs, and alternatives, then wait for agreement.
- **Present one development milestone at a time.** Complete it, show the result, and stop.
- **Wait for Karthik's approval before moving to the next milestone.**
- **Ask questions when important requirements are ambiguous.** Do not guess on decisions that materially change the outcome.
- Routine, low-risk judgment calls may be made without asking. State the assumption made.
- Report outcomes faithfully. If a step failed, was skipped, or could not be verified, say so plainly.

## 9. Quick Checklist

Before presenting any change in this repository, confirm:

1. Branch and working tree were inspected first.
2. No statistics, projects, or achievements were invented.
3. The banner is unchanged unless replacement was approved.
4. No secrets or confidential material are included.
5. Nothing has been committed or pushed without approval.
6. A summary of changes and validation is included.
