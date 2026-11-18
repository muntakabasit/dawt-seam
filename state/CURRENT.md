# CURRENT — Worker Identity / Work Linkage Position

**Recovered:** 2026-11-18 from user statement in chat. Not independently verified against original source text.
**Status:** REPORTED from chat surfaces. Absent from BelawuOS, ofa-jack, belawu-governance (GitHub search zero hits).
**Custody:** First public commit of this recovered position.

## Recovered status

| Component | Status | Label |
|-----------|--------|-------|
| Persistent worker identity concept | Established concept | REPORTED |
| Responsibility separated from worker/session | Established architectural direction | REPORTED |
| Worker Identity Registry | Proposed | REPORTED |
| Permanent Worker ID format | Proposed; not fully ratified | REPORTED |
| Responsibility ↔ Work linkage (OFA_WORK_LINKAGE_001, 13 Nov) | Developed | REPORTED |
| Assignment / Contribution / Actor identity | Defined in linkage | REPORTED |
| Session binding | Developed | REPORTED |
| Clock-In refinement (sub-fixture of linkage) | Developed | REPORTED |
| Identity / assignment / authority separation | Explicitly established | REPORTED |
| Full end-to-end identity fixture | Not yet proven | REPORTED |
| Registry populated with validated workers | Not established | REPORTED |
| Worker replacement continuity test | Still needs evidence | REPORTED |
| Run ID as distinct execution-episode identity | Observation from Grok Request ID; fit under assessment | INFERRED |

## How the pieces connect (no new architecture)

```
Worker ID (persistent responsibility)
  → Responsibility ID
    → Work ID (undertaking)
      → Assignment ID (authorised piece)
        → Run ID (execution episode)
          → Session / Events / Contributions / Evidence / Outcome
```

Clock-In binds a session to an already-authorised assignment; it does not create identity, assignment or authority.
Run ID is not Worker ID. A worker has many runs; a run carries model/machine/session without becoming the worker.

## What remains required

- Recover original OFA_WORK_LINKAGE_001 text (or the chat share that holds it) for verbatim preservation.
- Assess whether Run ID is already represented, missing, or conflated with Session ID.
- Keep Registry as proposed until linkage and continuity tests are reconciled.
- Do not treat the Grok observation as a reason to invent a new Worker ID architecture.

## Three consequential matters

1. Doctrine-file custody gap (still blocks #25 source-recovery and checking later amendments against locked text).
2. Work-linkage foundation not yet in shared custody — recovery of OFA_WORK_LINKAGE_001 + Clock-In needed before any identity fixture can be proven.
3. UncleSam Indeed V1: operator acts partially closed; principle/gate files still missing from repo; Gmail status uncertain.

No activation. No new registry. No dispatch.
