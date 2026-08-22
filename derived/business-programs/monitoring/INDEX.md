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
- `derived/business-programs/monitoring/runs/2026-08-22T01-52-06-04-00.md`
- Result: no material change. Illinois CMS Vendor Summit details remain TBD; Illinois APEX, CEI Mentor Protégé, UIC Business Opportunity Forum, CMS Vendor Outreach and EntreCorps statuses were revalidated without a meaningful new opening/deadline/eligibility change. Newly surfaced Techstars Chicago/Anywhere cycles open August 24 but were not promoted because they are venture accelerators with weak fit to IS&S's current procurement/supplier-development operating model.

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
- **Illinois Capital Development Board — General Informational Outreach** — August 26, 2026, 9:30 AM–12:00 PM CDT, 19433 Renwick Rd., Crest Hill. CDB expressly invites contractors, subcontractors, engineers, architects, suppliers, and professional-services firms. Covers CDB prequalification, diversity requirements, bidding process, and upcoming projects. Official RSVP link published; cost and RSVP closing deadline not stated. Priority: HIGH.
- **Illinois CDB — RISE IDOC Progressive Design-Build RFQ Informational Meeting** — August 27, 2026, 10:00 AM–12:00 PM CDT, 333 S. Wabash Ave., Chicago, with virtual attendance option. RFQ overview and Q&A for a major IDOC progressive-design-build procurement. Direct IS&S prime/team eligibility is not established; useful for procurement intelligence and possible teaming/subcontracting awareness. Priority: MEDIUM-HIGH.
- **University of Illinois System Diverse Supplier Development Program — Cohort 5** — applications currently open; cohort begins August 2026. Nine-month program with student consulting, workshops, government-contracting support, financial/data/technology training, and guided BEP certification path. No cost. Eligibility requires minority-, woman-, person-with-disabilities-, and/or veteran-owned small business; priority also favors current U of I suppliers, firms 3+ years old, and firms with at least one employee besides owner. Deadline not stated. Priority: HIGH IF ELIGIBLE.
- **EntreCorps — Fall 2026 Client Applications** — pro-bono University of Illinois student consulting for Fall 2026 (September–December), with strategic research, market/customer analysis, growth strategy and related business problem-solving. Current announcement seeks Illinois founders, startups and small businesses looking to grow or innovate. Deadline not stated. Priority: HIGH.
- **Doing Business with UIC: Business Opportunity Forum** — August 28, 2026, 9:00 AM–2:00 PM CDT, UIC Forum, Chicago. University procurement and partnership networking/information forum. Cost and registration-close date not stated on official CEI page. Priority: HIGH.
- **State of Illinois CPO-GS 3rd Annual Reverse Vendor Fair** — September 17, 2026, 9:00 AM–12:00 PM, Springfield. Registration live; cost and closing deadline not stated on official page. Priority: HIGH.
- **Illinois CEI BEP/VBP Certification Kickstart Workshop** — September 23, 2026, 11:00 AM–1:00 PM, Skokie. Priority: HIGH if certification assistance is needed.
- **2026 IMPACT Small Business Summit (MWRD)** — September 24, 2026, 8:00 AM–2:00 PM CDT, Malcolm X College, Chicago. 55+ exhibitors including agencies and prime contractors/consultants; registration link published. Cost and closing deadline not stated on official page. Priority: HIGH.
- **Chicago's 2026 Procurement Symposium** — October 19, 2026, 10:00 AM–3:00 PM CDT, Malcolm X College, Chicago. Registration open; Eventbrite currently identifies the event as free. Includes City/sister agencies, primes, procurement/certification panels, networking, and targeted matchmaking. Priority: HIGH.
- **Illinois CEI Mentor Protégé Program** — live; protégé participation requires BEP certification and documented track record. Priority: HIGH if eligible.
- **Illinois APEX Accelerator** — open to existing Illinois businesses; offers one-on-one confidential counseling, government-contracting technical assistance, market research, certification help, bid matching, mentor-protégé support, SAM assistance, bid-package review, subcontracting opportunities, contract administration support and networking. Priority: HIGH.
- **Illinois CMS Vendor Outreach Office Hours** — next session September 2, 2026, 1:00–2:30 PM. Priority: MEDIUM-HIGH.

## Watchlist / details pending
- **State of Illinois Vendor Summit — Fall 2026, Springfield** — official CMS page says attendees will learn about doing business with State agencies/universities and upcoming contracting opportunities, with prime/subcontractor networking. Exact date, location, cost, and registration window remain unpublished. Priority: MEDIUM-HIGH WATCH; elevate when registration opens.

## Other material programs to monitor and revalidate
- Illinois APEX Accelerator
- Duke Fuqua Client Consulting Practicum
- ICCC National Accelerator
- Goldman Sachs 10,000 Small Businesses
- ChicagoMSDC PIPE
- ChicagoMSDC SCALE — current application deadline September 11, 2026; eligibility thresholds may make fit conditional
- SCORE Illinois
- SBA Mentor-Protégé Program
- Illinois Tollway Technical Assistance / Partnering for Growth
- IDOT DBE Supportive Services
- Illinois Small Business Set-Aside Program
- CPO-GS Tuesday Afternoon Procurement Series
