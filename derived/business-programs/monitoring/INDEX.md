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

## Latest completed run
- `derived/business-programs/monitoring/runs/2026-08-21T21-05-25-04-00.md`
- Result: two newly surfaced high-priority Illinois opportunities warranted notification.

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

## Current high-priority opportunities
- **State of Illinois CPO-GS 3rd Annual Reverse Vendor Fair** — September 17, 2026, 9:00 AM–12:00 PM, Springfield. Registration live; cost and closing deadline not stated on official page. Priority: HIGH.
- **2026 IMPACT Small Business Summit (MWRD)** — September 24, 2026, 8:00 AM–2:00 PM CDT, Malcolm X College, Chicago. 55+ exhibitors including agencies and prime contractors/consultants; registration link published. Cost and closing deadline not stated on official page. Priority: HIGH.
- **Illinois CEI Mentor Protégé Program** — live; protégé participation requires BEP certification and documented track record. Priority: HIGH if eligible.
- **Illinois CEI BEP/VBP Certification Kickstart Workshop** — September 23, 2026, 11:00 AM–1:00 PM, Skokie. Priority: HIGH if certification assistance is needed.
- **Illinois CMS Vendor Outreach Office Hours** — next session September 2, 2026, 1:00–2:30 PM. Priority: MEDIUM-HIGH.

## Other material programs to monitor and revalidate
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
- Illinois Small Business Set-Aside Program
