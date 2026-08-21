# Trade Subcontractor Prospecting Derived Run Log

- Run ID: `ISS-V1-TRADE-OUTREACH-20260821T032301-0400`
- Discovery source class: Illinois Department of Transportation Contract Detail / Authorized Bidders
- Source count: 2
- Prospects discovered: 12
- Qualified contacts: 12
- Send attempts observed: 24 message attempts across 12 intended recipients
- Gmail SENT verified: 24 message instances
- No bounce observed at check: 11 unique recipients
- Bounced: 1 unique recipient
- Same-run duplicate attempts: 12
- Contact-form-only: 0
- Unusable: 1
- Send failed: 0 API-level failures
- Canonical Drive reference: `08_TRADE_SUBCONTRACTORS/ISSPOS_TRADE_SUBCONTRACTOR_PROSPECT_LEDGER` and `TRADE_SUBCONTRACTOR_RUN_2026-08-21T032301-0400`
- Drive state: COMPLETE
- Program economics used: $0 upfront cost + revenue-share model

## Evidence handling
Authorized Bidder appearance was treated only as OBSERVED public-procurement participation. No award, license, certification, recommendation, or current-eligibility inference was made.

## Material control incident
The 12 selected prospects were already sent one individual same-subject outreach message shortly after they were persisted as PENDING_SEND. Before that state was reconciled back to Drive, a second serial sender transmitted another individual message to each of the same 12 recipients. Post-send Gmail verification detected both message sets. No further outreach was sent after detection.

## Bounce reconciliation
One recipient, Alessio and Sons Co. at `jyoung@alessiocompanies.com`, returned a Gmail Delivery Status Notification (Failure): address not found or unable to receive mail. Canonical state was changed to BOUNCED/UNUSABLE and automatic retry is blocked unless explicitly revalidated.

## Discovery/control-method change
A current-run Gmail gate is now required immediately before each send, or immediately before a tightly bounded serial tranche: search SENT for the exact recipient + expected subject after the prospect `first_seen_at`. If a match already exists, do not send; reconcile the existing message/thread ID into Drive and classify `ALREADY_SENT_CURRENT_RUN`. A PENDING_SEND ledger state alone is insufficient because a concurrent or partially completed sender may have already transmitted the message before Drive reconciliation.
