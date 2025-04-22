# 🛣️ DirectiveOS Public Roadmap

DirectiveOS is entering its pre-alpha development phase. This roadmap outlines our projected build priorities, feature milestones, and intended rollout strategy. 

This document is public, but source code remains closed.

---

## 🎯 Core Principles

- **Structure over speed** — no MVPs, no shortcuts.
- **Modular by default** — each system is isolated and composable.
- **Durable systems** — sustainable UX over dopamine-driven tools.
- **Privacy-first** — designed for self-hosting and local data sovereignty.

---

## 🔒 Phase 0 — Planning & Architecture (Q2 2025)

> Status: **🚧 Active**

- Finalize module architecture (auth, scheduling, journaling, etc.)
- Define core schema (Postgres-first, audit-safe)
- Lock tech stack (Rust backend, React frontend, GraphQL API)
- Establish brand systems, CLI onboarding spec, and UX principles
- Roadmap repo structure and internal dev cadence
- Launch website for early access and signup funnel

---

## 🚧 Phase 1 — Internal Alpha Build (Q3–Q4 2025)

> Status: **🔒 Planned**

- Stand up local-first system shell: Auth, encrypted session cache, encrypted journal seed
- Core modules:
  - Task Matrix (tag-based, prioritization engine)
  - Journal Stream (templated + freeform capture)
  - Directive Queue (sequential + recursive tasks)
  - Signal Layer (alerts, memory hooks, cross-module triggers)
- Internal-only web UI shell (SPA React + Tailwind)

---

## 🔐 Phase 2 — Private Beta Cohort (Q4 2025)

> Status: **🔒 Planned**

- Closed beta with onboarding flow
- Self-hosted Docker image with external Postgres config
- Local-first encrypted data model (preview)
- Feedback system embedded into product (non-intrusive UX)
- Begin integration planning with Notion, Outlook, and CalDAV

---

## 🌐 Phase 3 — Public Launch Preview (Late Q4 2025)

> Status: **🔒 Planned**

- DirectiveOS Companion App (journal/task interface)
- Read-only public dashboards (metric visualizations)
- Optional analytics layer (disabled by default)
- Web installer + CLI bootstrap script
- Launch Partner API (invite-only)
- Open community Discord

---

## 🧭 Future Considerations (Post-2025)

- Local AI assistant for directive shaping (offline inference)
- Custom module SDK (for vetted partners)
- Encrypted sync mesh between devices
- DirectiveOS Mobile (offline-first, Rust-native wrapper)
- Integration library for GTD-style external tools (Logseq, Obsidian, etc.)

---

## 📫 Want to be part of the alpha?

Join the waitlist or reach out:

- 🌐 [directiveos.com](https://directiveos.com)
- 📬 labs@directiveos.com

