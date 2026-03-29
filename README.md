# Beat-Bot: GreenLeaf Logistics Internal AI Assistant

> An internal AI chatbot that answers repetitive employee questions using the company handbook — so Beat Müller's office door stops being a revolving door.

## Project Overview

**Client:** Beat Müller, Head of Operations & HR, GreenLeaf Logistics (Basel Branch)
**Team:** TBD (update after Team Charter is finalized)
**Timeline:** 3 Sprints × 1 week | Sprint 1 starts: 2026-03-30

---

## What Does Beat-Bot Do?

Beat-Bot answers employee questions like:
- "Is May 1st a holiday in Basel?" → ✅ Yes, Labor Day is a Basel-Stadt holiday.
- "Can I expense this 36 CHF lunch?" → ❌ No, the limit is 35 CHF per person.
- "My dog died, can I stay home?" → The bot redirects to the correct bereavement policy.

It answers **only from verified sources** (the handbook + official holiday data) and always cites the exact section it used.

---

## Project Structure

```
beat-bot/
├── docs/               # Project documentation & source PDFs
│   ├── Handbook GreenLeaf Logistics.pdf
│   ├── Stakeholder Briefing.pdf
│   ├── Project1 Ready to get started.pdf
│   └── Quick-Start Kanban Guide.pdf
├── src/                # Bot source code (Python)
├── data/               # Structured data files (CSV, JSON)
│   └── holidays_2026.csv
├── tests/              # Test cases
├── TEAM_CHARTER.md     # Team roles, values, Definition of Done
├── requirements.txt    # Python dependencies
└── README.md
```

---

## Beat's Non-Negotiables (Acceptance Criteria)

| # | Rule | Detail |
|---|------|--------|
| 1 | No guessing on money | Max 35 CHF/person, no alcohol reimbursement |
| 2 | Basel accuracy | Follow Basel-Stadt cantonal holiday calendar |
| 3 | Security first | Never reveal internal Wi-Fi passwords or MAC addresses |
| 4 | Proof of source | Always cite the exact handbook section used |

---

## Sprint Overview

| Sprint | Dates | Goal |
|--------|-------|------|
| Sprint 1 | 2026-03-30 → 2026-04-05 | Setup, MoSCoW, Team Charter, core Q&A engine |
| Sprint 2 | 2026-04-06 → 2026-04-12 | Expense validation + Holiday logic |
| Sprint 3 | 2026-04-13 → 2026-04-19 | Security filtering + Source citation + Final polish |

---

## Scrum Rituals

- **Daily Standup:** Async (comment on active GitHub Issue)
- **Sprint Review:** Every Thursday on-site with Beat Müller
- **Retrospective:** End of each sprint (Friday)

---

## Tech Stack (Planned)

- **Language:** Python 3.x
- **Interface:** Slack Bot (via `slack_bolt`)
- **Data:** pandas, CSV for holiday data
- **AI/LLM:** TBD (Sprint 2 decision)

---

## Definition of Done

A feature is **Done** when:
1. Code is pushed to GitHub
2. The Wiki is updated with the new logic
3. The feature passes a "tricky query" test

---

*Project started: 2026-03-30 | Bootcamp Project 1*
