# IS&S V1 — Business Program Monitoring

## Purpose
This index is the durable recovery point for the automated search that tracks business-development, supplier-development, procurement-assistance, mentoring, accelerator, student-consulting, and government-contracting programs relevant to Illinois Supply & Services.

## Monitoring cadence
- Schedule: hourly
- Start: 2026-08-21 21:00 America/New_York
- Mode: condition watch
- Notification rule: notify only when there is a meaningful new program, opening, deadline, or eligibility change worth pursuing.
- Persistence rule: every completed search run must be saved, even when there is no notification.

## Run storage
Each completed run should be written under:

`derived/business-programs/monitoring/runs/`

Use an ISO-timestamped JSON or Markdown filename so the record is chronological and auditable.

## Minimum record fields
Each run should preserve, when available:
- search timestamp
- queries/categories checked
- sources reviewed
- program name and direct URL
- benefit / support offered
- eligibility
- cost or subsidy status
- application window and deadline
- geographic scope
- program status
- material changes since the prior run
- rejected or irrelevant programs with brief reasons when useful
- unknowns and conflicts
- recommended priority
- evidence/provenance sufficient to reproduce the conclusion

## Evidence standard
Persist concise, auditable sourcing/research rationale and evidence. Do not persist private chain-of-thought. Distinguish VERIFIED, OBSERVED, INFERRED, UNKNOWN, CONFLICT, and STALE where relevant.

## Current known high-priority programs
Initial research identified the following as material candidates to monitor and revalidate:
- Illinois APEX Accelerator
- Duke Fuqua Client Consulting Practicum
- ICCC National Accelerator
- Goldman Sachs 10,000 Small Businesses
- ChicagoMSDC PIPE
- ChicagoMSDC SCALE
- SCORE Illinois
- SBA Mentor-Protégé Program
- Illinois Tollway Technical Assistance / Partnering for Growth
- IDOT DBE Supportive Services

This index should be updated as material program state changes or new high-priority programs are identified.
