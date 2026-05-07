    Non-engineers struggle to use Claude Code as a real development tool to enhance their workflows because they're not experienced with professional development workflows and the existing possibilities of Claude Code, so they continue to use AI as a search engine and basic code generator instead of a comprehensive force multiplier.
    
    The Claude Workflow Coach guides non-engineers through professional Claude Code workflows — from dev environment setup to agentic prompting and MCP integration — so they can use AI as a true development partner instead of a basic code generator.

## Goals

### User goals
1. **Adopt a concrete workflow improvement.** After using the coach, a user implements at least one Claude feature that automates a previously manual part of their day-to-day workflow.
2. **Develop a generative mindset.** Users leave able to identify their *own* future automation opportunities without needing the app to prompt them.

### Product goals
1. **Fast time-to-first-insight.** The coach surfaces a personalized, actionable suggestion early in the experience — not after a long onboarding flow.

### PM / personal goals
1. **Demonstrate business–technology bridge thinking.** The project shows a hiring manager that the PM can identify where AI tooling closes real organizational productivity gaps — not just technical curiosity for its own sake.

## Users

### Primary persona: Jackson

**Background:** Has written Python in classes and knows SQL. Enjoys computer science and has the logical foundation to follow technical concepts — but has not set up a real developer environment. He hasn't worked in a terminal seriously, doesn't have a Git workflow, and hasn't configured his tools (editor, AI assistants, project structure) for professional use.

**Motivation:** Productivity (wants to automate manual parts of his current workflow) and curiosity (interested in what's possible with AI tooling beyond chat).

**Pain point:** Has Claude Code installed but uses it like a search engine and code generator — the way someone uses ChatGPT. Doesn't know the workflows, integrations, or features that would make it a true force multiplier.

### Anti-personas — who this is NOT for

- **Complete beginners** who have never opened a terminal or written any code. The Workflow Coach assumes a baseline of CS literacy.
- **Users who haven't installed Claude Code yet.** The Coach starts *after* the install — guiding the install of Claude Code itself is out of scope.

## Features

### Must-have (MVP)

1. **Problem capture.** A single, free-form text box where Jackson types the problem he's having with Claude Code or describes his current workflow context. No multi-step intake form — one input, one submission. The user's level and role are inferred by the AI from how they phrase the problem.

2. **AI-powered recommendation engine.** When Jackson submits, the system matches his problem to the most relevant Claude Code capability and surfaces it as his recommended tile.

3. **Tile content.** Each capability is presented as a tile with the following structure, in order:
   - **Immediate commands / steps** to start using the capability (action-first — this is what makes Jackson actually adopt it)
   - **What it is** — short explanation
   - **Why it helps** — workflow benefit specific to Jackson's situation
   - **Use cases** — concrete situations where it applies
   - **Source link** — link to the official Claude Code documentation page the tile was sourced from

4. **Capability tree.** A horizontal hierarchical layout of all tiles, organizing Claude Code's capabilities into a navigable map. Jackson's recommended tile is highlighted as "this is what you need." Any tile is clickable to reveal its full content.

5. **AI-powered semantic search.** A search bar that lets Jackson find tiles by intent (e.g. "I keep forgetting commands") rather than only by keyword. Same underlying matching logic as the recommendation engine, different UI.

### Nice-to-have (post-MVP)

- **Multi-turn AI follow-up dialog.** A conversational interface where Jackson can ask deeper questions about his recommendation or other tiles after exploring the tree.

## Out of Scope

Explicitly **not** part of the MVP. Naming these prevents scope creep:

- **User accounts / login.** Anonymous, stateless on first use.
- **Persistent history / saved plans.** Recommendations are not stored across sessions.
- **Sharing or export.** No "share this plan" or "export to PDF."
- **Guidance for installing Claude Code itself.** The product assumes Claude Code is already installed (per anti-persona).