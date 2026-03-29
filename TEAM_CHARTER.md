# Team Charter — Beat-Bot Project

> This document defines how our team works together. It is a living document — update it after each retrospective.

---

## Team Name

> **[TO BE DECIDED]** — Decide as a team in your first meeting.

---

## Team Roles

| Role | Person | Responsibilities |
|------|--------|-----------------|
| Scrum Master | TBD | Facilitates ceremonies, removes blockers, protects the team from distractions |
| Product Owner | TBD | Owns the backlog, prioritizes User Stories, represents Beat Müller's needs |
| Architect | TBD | Leads technical decisions, defines the system design |
| Developer | TBD | Implements features, writes tests, reviews code |
| QA | TBD | Tests features with "tricky queries", ensures Definition of Done is met |

> **Note:** In a small bootcamp team, one person may hold multiple roles. Be explicit about it.

---

## Mission Statement

> We build a reliable, honest AI assistant that saves Beat Müller time — without ever guessing, hallucinating, or leaking sensitive information.

---

## Team Values

1. **Accuracy over speed** — A wrong answer is worse than a slow one.
2. **Transparency** — If something is blocked, say so immediately. No silent blockers.
3. **Cite your sources** — In code reviews and in the bot itself.
4. **Ship small, ship often** — Prefer a working 50% over a broken 100%.
5. **Learn out loud** — This is a bootcamp. Asking questions is a feature, not a bug.

---

## Ground Rules

- **Decision making:** Discuss → Vote (majority) → Document in the Wiki.
- **Raising issues:** Create a GitHub Issue tagged `[BLOCKER]`. Mention @Scrum Master.
- **Missing a standup:** Notify the team in advance via Slack/Discord.
- **Code reviews:** Every PR needs at least 1 approval before merging to `main`.
- **Sensitive topics / conflicts:** Talk to the Scrum Master first, privately.

---

## Definition of Done (DoD)

A User Story is **Done** when ALL of the following are true:

- [ ] Code is pushed to the `main` branch on GitHub
- [ ] The GitHub Issue is moved to the **Done** column on the Kanban board
- [ ] The Wiki is updated with any new logic or decision
- [ ] The feature was tested with at least one "tricky query" (edge case)
- [ ] No hardcoded secrets in the code (passwords, tokens, API keys)

---

## Communication Plan

| Channel | Purpose |
|---------|---------|
| Slack / Discord | Daily async standups, quick questions |
| GitHub Issues | Task tracking, technical discussions |
| GitHub Wiki | Documentation, decisions, MoSCoW map |
| Thursday on-site | Sprint Review with Beat Müller |

---

## Risk Register

| # | Type | Risk | Mitigation |
|---|------|------|-----------|
| 1 | Technical | We don't know how to connect Python to the Slack interface yet | Research `slack_bolt` library in Sprint 1; add spike task to backlog |
| 2 | Team | Uneven skill levels may slow down the Python work | Pair programming; senior member reviews junior PRs |

> Update this table as new risks are identified.

---

*Last updated: 2026-03-30 | Version: 1.0*
