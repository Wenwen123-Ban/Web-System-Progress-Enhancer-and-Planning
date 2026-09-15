# Objective — Version 1.0

## Goal
Establish a reliable foundation for **creating, organizing, and tracking personal projects.**

## Scope
This version focuses on the core loop only — no advanced analytics, automation, or collaboration features yet.

### In Scope
- [ ] Create a project (title, description, status)
- [ ] Organize projects (categorize, tag, or group)
- [ ] Track progress (task/status updates over time)
- [ ] Persist data reliably (database schema stable and migratable)
- [ ] Basic error handling and logging for core actions

### Out of Scope (for v1.0)
- Multi-user support / permissions
- Notifications or reminders
- Reporting dashboards or analytics
- Third-party integrations

## Success Criteria
A user can create a project, organize it, update its progress, and trust that the data persists correctly across sessions — with no manual intervention required.

## Alignment Check
| Core Principle | How v1.0 honors it |
|---|---|
| Progress over perfection | Ships a minimal but working core loop rather than a polished partial system. |
| Knowledge from every task | Each shipped feature is documented in `docs/objectives` and `docs/debugging`. |
| Record failures | Known issues and bugs logged under `docs/debugging`, not discarded. |
| Solve real problems | Feature set limited to what's needed to actually track a project end-to-end. |
| Stay maintainable | Backend kept to a simple models/routes/services split (see `backend/`). |
| Earn complexity | No automation or integrations added until the core loop is proven. |

## Status
🟡 In Progress — see `docs/releases` for changelog entries tied to this objective.

---
*Objective owner: —  |  Target: Foundation release  |  Version: 1.0*
