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
- `derived/business-programs/monitoring/runs/2026-08-21T21-55-49-04-00.md`
- Result: two newly surfaced actionable Illinois procurement-development events warranted notification; one additional State vendor summit was added as a save-the-date watch item.

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
- **Doing Business with UIC: Business Opportunity Forum** — August 28, 2026, 9:00 AM–2:00 PM CDT, UIC Forum, Chicago. University procurement and partnership networking/information forum. Cost and registration-close date not stated on official CEI page. Priority: HIGH.
- **State of Illinois CPO-GS 3rd Annual Reverse Vendor Fair** — September 17, 2026, 9:00 AM–12:00 PM, Springfield. Registration live; cost and closing deadline not stated on official page. Priority: HIGH.
- **Illinois CEI BEP/VBP Certification Kickstart Workshop** — September 23, 2026, 11:00 AM–1:00 PM, Skokie. Priority: HIGH if certification assistance is needed.
- **2026 IMPACT Small Business Summit (MWRD)** — September 24, 2026, 8:00 AM–2:00 PM CDT, Malcolm X College, Chicago. 55+ exhibitors including agencies and prime contractors/consultants; registration link published. Cost and closing deadline not stated on official page. Priority: HIGH.
- **Chicago's 2026 Procurement Symposium** — October 19, 2026, 10:00 AM–3:00 PM CDT, Malcolm X College, Chicago. Registration open; Eventbrite currently identifies the event as free. Includes City/sister agencies, primes, procurement/certification panels, networking, and targeted matchmaking. Priority: HIGH.
- **Illinois CEI Mentor Protégé Program** — live; protégé participation requires BEP certification and documented track record. Priority: HIGH if eligible.
- **Illinois CMS Vendor Outreach Office Hours** — next session September 2, 2026, 1:00–2:30 PM. Priority: MEDIUM-HIGH.

## Watchlist / details pending
- **State of Illinois Vendor Summit — Fall 2026, Springfield** — official CMS Buying Plan save-the-date says attendees will learn about doing business with State agencies/universities and upcoming contracting opportunities, with prime/subcontractor networking. Exact date, location, cost, and registration window remain unpublished. Priority: MEDIUM-HIGH WATCH; elevate when registration opens.

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
- CPO-GS Tuesday Afternoon Procurement Series
