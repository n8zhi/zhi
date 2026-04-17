# 志 Zhi (zhì)

**An open-source framework for purposeful agency in the age of AI.**

Zhi (志, zhì; pronounced like "Jrive" without the "-ve": "jri.") is an MCP-native goal decomposition and time allocation layer that sits between humans and their AI. It persists long-term goals, decomposes them into progressive milestones calibrated to produce flow, and connects to calendars and tools to maintain honest alignment between intentions and actions.

---

## The Thesis

As AI handles more of the work humans used to do, the risk isn't joblessness — it's a meaning crisis.

If David Deutsch is right that problems are inevitable but soluble, and that expanding our capacity to solve them is what gives life meaning, then a world where AI solves most problems *for us* is a world where meaning has to be deliberately maintained rather than passively encountered.

Instant gratification accelerates. Ambient difficulty decreases. People lose the structured progression through increasingly hard challenges that gives them a sense of growth and purpose.

Zhi exists to offer another way.

Not by making people more productive for its own sake, but by providing a persistent, transparent, progressive, and flow-state-inducing relationship with meaningful difficulty. It helps people identify what they're actually trying to do/be/become, decomposes that into a sequence of challenges calibrated to stretch them, and uses their calendar and AI tools to help them execute.

The goal isn't merely to get things done. It's to help humans meaningfully engage with reality as the nature of that reality rapidly changes.

---

## How It Works

Zhi is infrastructure, not an app. It's a reasoning protocol and data format that any AI can use via MCP, API, or CLI.

### The Core Components

**志 (Telos)** — A living document articulating what you're trying to become and why. Not static. Refined continuously through dialectical reflection as your understanding deepens and your capabilities grow. The framework expects your purpose to evolve. Evolution with continuity is the process working.

**Capability Dimensions** — Skill trees representing the capacities you're developing. Starting from universal human pillars (health, mastery, relationships, creative output, financial/material capacity, epistemic skill), these evolve through use into something unique to you. Capabilities combine in unpredictable ways — the framework tracks intersections and emergent possibilities, not just individual progress.

**Milestones** — Concrete, near-term, falsifiable markers within each capability dimension. These are what the system calibrates for flow: hard enough to require genuine growth, achievable enough to maintain engagement. Progress is measured locally against milestones, then aggregated into a directional signal for the whole trajectory.

**Criticism Cycles** — The dialectical engine. Every goal, capability assessment, and trajectory is treated as a conjecture — a best guess subject to genuine criticism and revision. The system doesn't validate. It challenges. "Is this still the right direction? What evidence would change your mind? What are you not seeing?"

**Heartbeats** — Dynamic signals about real-world needs at multiple scales: local, civilizational, long-term. The framework maps your developing capabilities against problems that matter, surfacing the possibility space where what you're becoming meets what the world needs.

**Titles** — Dynamic recognition of growth. As capabilities develop and milestones are reached, the system assigns evolving names that reflect who you're becoming. Not vanity metrics — legible markers of real progression, the way ranks in a skill-based game reflect genuine capability.

### The Interfaces

- **MCP Server** — Any AI session connects to your full Zhi context. Your AI knows your telos, your capability state, your current milestones, and your honest progress. No copy-pasting your life story into every conversation.
- **CLI** — `zhi status`, `zhi challenge`, `zhi heartbeat`. Power-user and programmatic access.
- **Linked Documents** — Everything is human-readable markdown in a git repo you own. Browse it in Obsidian, VS Code, or a text editor. Fork it, version it, export it. Your data, your format, your control.
- **Calendar Integration** — Connects to your actual schedule. What you commit to vs. what you complete is the primary honesty signal.

---

## Why Infrastructure, Not an App

Apps are fixed artifacts maintained by companies. They improve when the company ships updates. They die when the company dies.

Zhi is a protocol. It improves from every direction simultaneously:

- **AI improves → Zhi improves.** Better foundation models execute the reasoning protocol with more intelligence. No update required.
- **Community improves → Zhi improves.** Better capability templates, criticism protocols, onboarding patterns, and heartbeat sources flow back through open contribution.
- **You improve → Zhi improves.** The framework is subject to the same conjecture-and-criticism process it teaches. It evolves through use.

The framework is built on the epistemology it embodies: all progress comes from guessing, failing, and improving. Including progress on the framework itself.

---

## Philosophical Foundations

Zhi draws on:

- **David Deutsch** (*The Beginning of Infinity*) — Problems are inevitable, soluble, and the growth of knowledge to solve them is unbounded. Progress comes through conjecture and criticism, not authority or revelation.
- **Mihaly Csikszentmihalyi** (Flow) — Optimal human experience occurs at the boundary between current capability and challenge. Too easy → drift. Too hard → paralysis. The system calibrates for the zone where growth happens.
- **Aristotle** (Telos) — A life well-lived requires direction toward an end worth pursuing. Purpose is not discovered passively — it is constructed, tested, and refined through action and reflection.

The synthesis: **meaningful human agency requires structured progression through increasingly difficult problems that matter.** AI can either erode that progression or support it. Zhi is the tool for ensuring it's the latter.

---

## Current Status

Zhi is in early specification. The following are being defined:

- [ ] Telos document schema
- [ ] Capability dimension structure and starter templates
- [ ] Milestone format and flow-calibration protocol
- [ ] Criticism cycle protocol
- [ ] Heartbeat signal specification
- [ ] MCP server implementation
- [ ] CLI tool
- [ ] Calendar integration (Google Calendar via MCP)
- [ ] Infinite canvas visualization spec

---

## Contributing

Zhi improves through the same process it teaches: conjecture and criticism. If you see something wrong, open an issue. If you have a better approach, propose it. The framework is a living conjecture about how to maintain human agency and meaning in a world of increasingly capable AI. It should be challenged.

---

## License

MIT. Use it for anything. Build on it freely.

---

*志於道 — Set your purpose on the way.*
