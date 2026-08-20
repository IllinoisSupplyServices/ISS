# IS&S V1 Trade Subcontractor — Bid Tabulation Outreach Run

- Run ID: `ISS-V1-BID-TAB-OUTREACH-20260820-100`
- Authority: Google Drive is canonical prospect/outreach state. GitHub is sanitized derived/control/changelog only.
- Discovery action: searched public bid-tabulation, vendor-list, plan-holder, and public procurement sources for trade/service businesses.
- Outreach action: 100 cold-outreach send attempts through the connected IS&S Gmail account.
- Gmail SENT verification: 100 messages observed in SENT for the batch subject `Illinois Supply & Services — Trade Subcontractor Program`.
- Known post-send bounces at reconciliation: 9.
- Non-bounced-at-check messages: 91. This is not a claim of final delivery; it means no bounce was observed at the reconciliation check.
- Canonical Drive batch record: `ISS_V1_BID_TABULATION_OUTREACH_20260820_100`
- Drive record URL: https://docs.google.com/spreadsheets/d/1Wm49tgdstRzh3kjepkJ761mewjyAUbNzg05C2G4yjTA/edit
- Drive folder: `08_TRADE_SUBCONTRACTORS`
- Canonical prospect IDs in this run: `ISS-V1-TRADE-PROSPECT-20260820-00077` through `ISS-V1-TRADE-PROSPECT-20260820-00176`
- Evidence state: `OBSERVED_PUBLIC_BID_TABULATION_CONTACT`
- Dedupe state: `CURRENT_RUN_UNIQUE` for the 100 batch records.
- Program economics used in outreach: $0 upfront cost; revenue-share model; no activation or annual renewal fee.

## Known bounced/unusable company contacts

The canonical Drive record carries the actual public business email addresses and Gmail message IDs. Sanitized GitHub logging stores company-level bounce state only:

- C & S Construction — BOUNCED
- Construct Society — BOUNCED
- Armor D2 — BOUNCED
- American Demolition Corporation — BOUNCED
- Automated Logic — BOUNCED
- J.S. Riemer — BOUNCED
- John Burns Construction — BOUNCED
- W.B. Olson — BOUNCED
- Skyelite Painting Solutions — BOUNCED

## Discovery method / reusable logic

1. Search public procurement portals for bid tabulations, bid-result pages, bidder/vendor download lists, and plan-holder lists.
2. Prioritize Illinois trade/facility categories: construction, excavation, plumbing, mechanical/HVAC, electrical, fencing, demolition, paving, painting, flooring, landscaping, communications/low voltage, environmental, and facility-support services.
3. Extract only publicly published business contacts associated with identifiable companies.
4. Qualify commercial relevance; do not treat bid-tabulation appearance as an award, license, or current government eligibility claim.
5. Deduplicate company/email within the run before send.
6. Send one concise IS&S Trade Subcontractor invitation using authoritative $0-upfront/revenue-share language.
7. Verify each attempted message in Gmail SENT.
8. Search Gmail for delivery-failure notices and mark those contacts BOUNCED/UNUSABLE in Drive.
9. Persist the full company/contact/message-level record in Drive; GitHub stores sanitized derived counts, states, source classes, and Drive reference only.

## Source classes used

- Lake County Purchasing Portal bid listings and bid-detail/vendor-download records
- Will County public purchasing/bid records
- Heneghan & Associates public bid-tabulation/plan-holder project pages
- Related Illinois public procurement bid-result/vendor-list sources

## Reconciliation state

- Drive persistence: `VERIFIED_READBACK`
- Gmail SENT verification: `VERIFIED`
- Bounce scan: `VERIFIED_AT_RECONCILIATION_TIME`
- GitHub derived log: written by this commit; readback verification required before propagation is considered complete.
