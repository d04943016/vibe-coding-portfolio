# claude-review-pipeline

[Back to portfolio](../../README.md)

claude-review-pipeline is a Claude Code plugin concept for generating a complete, domain-aware code review pipeline inside any project. It creates a tailored domain expert, installs reviewer agents, and drives an iterative loop: domain review, design, implementation, stabilization, testing, and repeat.

## Portfolio Summary

| Item | Summary |
|---|---|
| Domain | AI-assisted software engineering workflow |
| Target users | Developers who want repeatable, domain-aware review loops for vibe-coded projects |
| Main value | Converts vague "please review this" workflows into a structured multi-agent quality system |
| Stack | Claude Code plugin conventions, skill templates, reviewer agents, markdown-based workflow docs |
| Public-safe version | Installation paths and generated internal file layouts were summarized |

## What It Does

The pipeline has two main phases:

- `/review-setup`: conversational setup that discovers the project domain, generates a domain expert, selects reviewers, configures optional E2E testing, and writes project-specific workflow files.
- `/product-iteration`: repeated development cycle that rotates domain review angles, asks the user to choose iteration scope, designs and implements the change, then runs review-fix loops until stability criteria are met.

## Key Highlights

| Highlight | Why it matters |
|---|---|
| Domain expert generation | The reviewer is shaped by the project's actual domain rather than acting as a generic lint pass |
| Parallel reviewer roles | Code architecture, tester, UI/UX, database, API design, and performance perspectives can run side by side |
| Review-fix convergence | The flow requires repeated clean rounds before considering an iteration stable |
| E2E testing handoff | Browser, API, or CLI E2E tests can be included as part of the loop |
| Metrics and history | Iterations can accumulate review history, deferred items, lessons learned, and review angles |

## Review Dimensions

| Reviewer | Focus |
|---|---|
| Code Architecture | Security, structure, resource lifecycle, maintainability |
| Tester | Coverage gaps, regression risk, missing test cases |
| UI/UX | Error states, loading states, accessibility, interaction quality |
| Database | Migrations, transaction safety, constraints, injection risk |
| API Design | Contracts, status codes, error semantics, route consistency |
| Performance | Complexity, memory use, slow paths, N+1 query patterns |

## Vibe Coding Notes

This is a meta-project: it is a workflow tool for making other vibe-coded projects safer. The strongest idea is the separation between domain review, user prioritization, implementation, and stabilization. It makes AI coding feel less like one long improvisation and more like a repeatable engineering loop.

## Public Version Adjustments

- Removed source-oriented file listings and local installation path examples.
- Kept the setup flow, iteration model, reviewer roles, and stability criteria.
- No images were present in the original README, so this folder intentionally has no required screenshots.

