# Startup Engineering

Agent skills for startup engineering. Authored by Selva Ganapathy.

Startup teams get overwhelmed by agent tooling. There are hundreds of skills, commands, agents, and integrations — and no clear answer to *"what should we actually use?"* This repo is my answer: a curated starter kit of skills I use and recommend for small-to-mid startup engineering teams.

Install it, and your agents immediately have access to opinionated defaults for the problems startup teams face every day.

## Install

```
/plugin install selvaganapathyc/startupengineering
```

That's it. Your agents now have access to every skill in this collection.

## Who this is for

- **Small-to-mid startup engineering teams** (roughly 2–20 engineers)
- **Teams where not everyone is senior** — the skills encode opinions that protect less-experienced engineers from common pitfalls
- **Teams overwhelmed by agent-era tooling** and wanting a sensible starting point
- **Technical founders** setting up agent infrastructure for their team for the first time

If you're at a large company with established practices, these skills may not fit your context. They're calibrated for startup constraints: small teams, fast iteration, pragmatism over completeness.

## The startup engineering lifecycle

These skills span the lifecycle of building software in a startup — from understanding the problem to running the system in production. Broadly, that lifecycle has six phases:

- **Define** — framing the problem, writing user stories, prioritizing work
- **Discover** — researching users, validating assumptions, finding market fit
- **Design** — architecting the system, modeling data, designing APIs
- **Develop** — writing code, reviewing changes, handling errors
- **Validate** — testing strategies, quality gates, CI/CD
- **Operate** — deploying, monitoring, scaling in production

Skills in this collection touch every phase where I have strong opinions worth encoding. Some phases are currently thin and will grow over time as I author more skills. The skill list below tells you what's currently available.

## What's in this collection

### api-and-interface-design

Guides stable API and interface design.

**Activates when:** designing APIs, module boundaries, or any public interface — including REST or GraphQL endpoints, type contracts between modules, or boundaries between frontend and backend.

### browser-testing-with-devtools

Tests in real browsers.

**Activates when:** building or debugging anything that runs in a browser — inspecting the DOM, capturing console errors, analyzing network requests, profiling performance, or verifying visual output with real runtime data via Chrome DevTools MCP.

### ci-cd-and-automation

Automates CI/CD pipeline setup.

**Activates when:** setting up or modifying build and deployment pipelines, automating quality gates, configuring test runners in CI, or establishing deployment strategies.

### code-review-and-quality

Conducts multi-axis code review.

**Activates when:** before merging any change — reviewing code written by yourself, another agent, or a human, and assessing it across correctness, readability, architecture, security, and performance.

### code-simplification

Simplifies code for clarity.

**Activates when:** refactoring code for clarity without changing behavior — when code works but is harder to read, maintain, or extend than it should be, or when reviewing code that has accumulated unnecessary complexity.

### context-engineering

Optimizes agent context setup.

**Activates when:** starting a new session, agent output quality degrades, switching between tasks, or configuring rules files and context for a project.

### debugging-and-error-recovery

Guides systematic root-cause debugging.

**Activates when:** tests fail, builds break, behavior doesn't match expectations, or any unexpected error appears — and a systematic approach to finding and fixing the root cause is needed rather than guessing.

### deprecation-and-migration

Manages deprecation and migration.

**Activates when:** removing old systems, APIs, or features; migrating users from one implementation to another; or deciding whether to maintain or sunset existing code.

### documentation-and-adrs

Records decisions and documentation.

**Activates when:** making architectural decisions, changing public APIs, shipping features, or recording context that future engineers and agents will need to understand the codebase.

### frontend-ui-engineering

Builds production-quality UIs.

**Activates when:** building or modifying user-facing interfaces — creating components, implementing layouts, managing state, or when the output needs to look and feel production-quality rather than AI-generated.

### git-workflow-and-versioning

Structures git workflow practices.

**Activates when:** making any code change — committing, branching, resolving conflicts, or organizing work across multiple parallel streams.

### idea-refine

Refines ideas iteratively through structured divergent and convergent thinking.

**Activates when:** a raw idea needs to be sharpened into something actionable. Invoke with "idea-refine" or "ideate" to trigger the interactive dialogue.

### incremental-implementation

Delivers changes incrementally.

**Activates when:** implementing any feature or change that touches more than one file, or when you're about to write a large amount of code at once and a task feels too big to land in one step.

### performance-optimization

Optimizes application performance.

**Activates when:** performance requirements exist, regressions are suspected, Core Web Vitals or load times need improvement, or profiling reveals bottlenecks that need fixing.

### planning-and-task-breakdown

Breaks work into ordered tasks.

**Activates when:** a spec or clear requirements exist and work needs to be broken into implementable tasks — when a task feels too large to start, scope needs estimating, or parallel work is possible.

### security-and-hardening

Hardens code against vulnerabilities.

**Activates when:** handling user input, authentication, data storage, or external integrations — building any feature that accepts untrusted data, manages user sessions, or interacts with third-party services.

### shipping-and-launch

Prepares production launches.

**Activates when:** preparing to deploy to production, needing a pre-launch checklist, setting up monitoring, planning a staged rollout, or defining a rollback strategy.

### source-driven-development

Grounds every implementation decision in official documentation.

**Activates when:** building with any framework or library where correctness matters and authoritative, source-cited code free from outdated patterns is needed.

### spec-driven-development

Creates specs before coding.

**Activates when:** starting a new project, feature, or significant change and no specification exists yet — or when requirements are unclear, ambiguous, or only exist as a vague idea.

### test-driven-development

Drives development with tests.

**Activates when:** implementing any logic, fixing any bug, or changing any behavior — when you need to prove that code works, when a bug report arrives, or when modifying existing functionality.

### using-agent-skills

Discovers and invokes agent skills.

**Activates when:** starting a session or needing to discover which skill applies to the current task. This is the meta-skill that governs how all other skills are discovered and invoked.

## How to use this

1. Install the collection (command above)
2. Your agents automatically pick up the skills
3. When working on relevant tasks, agents will apply the skills — no manual invocation needed in most cases
4. If you want to disable a specific skill for your team, edit your agent configuration to exclude it

## The broader ecosystem

This repo is one piece of a broader effort to help startup teams navigate agentic engineering:

- **[startupengineering.io](https://startupengineering.io)** — Curation, principles, and decision guidance for choosing among many authors' skills (including this collection). Visit when you want to think carefully about specific decisions, compare approaches from different authors, or understand the reasoning behind a recommendation.
- **This repository** — An opinionated starter kit for teams who want to start immediately with sensible defaults.

Most teams will benefit from both: install this repo today to get your agents working, visit the site when you need to make specific choices or understand trade-offs more deeply.

## Why opinionated?

These skills reflect my judgment from 18 years of engineering, 5 years as a startup founder, and 4 years as a Principal AI Architect. They're not meant to be neutral or universally applicable — they're opinionated defaults calibrated for startup teams.

Opinions compound: a team adopting a coherent set of approaches makes better decisions than a team picking from a neutral smorgasbord. If you disagree with specific choices, swap them out. But starting with a coherent set beats starting with none.

## Contributing

This is currently Selva's personal collection — contributions are not open at this time. If you have suggestions or feedback, open an issue.

If you're building your own skills, I encourage you to publish them in your own repo and share them with the community. The agentic engineering space benefits from more authored skills, not fewer.

## About the author

Selva Ganapathy is a Principal AI Architect with 18 years in product engineering. Previously founded a SaaS startup (5 years, scaled 0 → 6Cr ARR) and built enterprise-grade systems at Brocade, Juniper, and HCL. Currently leading a 14-member team building Gen AI-powered SaaS at Mintmesh. Based in Bengaluru, India.

- Website: [startupengineering.io](https://startupengineering.io)
- LinkedIn: [linkedin.com/in/selvaganapathyc](https://linkedin.com/in/selvaganapathyc)

## License

MIT — see [LICENSE](./LICENSE) for details.

These skills are free to use, modify, and distribute. Attribution is appreciated but not required. If you find them useful, a star on the repo is welcome.
