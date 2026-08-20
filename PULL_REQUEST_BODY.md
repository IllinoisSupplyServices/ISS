# Standardize config/schema names and rules — align sourcing policy and schemas

This PR standardizes and aligns several configuration and JSON schema files to prevent runtime inconsistencies and improve validation.

What I changed

- Updated config/IS&S_V1_SOURCING_POLICY.json (already committed on main)
  - Replaced `bid_revenue` with `bid_price` and updated the profit formula to use `bid_price`.

- Added/updated config/IS&S_V1_MASTER_INDEX.json
  - Removed the master index self-reference from `read_order` to avoid recursive loading.
  - Added `UNVERIFIED` to `state_classes` to match the supplier-memory schema.

- Updated config/IS&S_V1_GATE_POLICY.json
  - Converted `three_failed_sourcing_attempts` from a string to a structured object: `{threshold: 3, outcome: "UNRESOLVABLE"}`.

- Updated schemas/supplier-memory.schema.json
  - Made `last_verified_at` optional (removed from required list) to allow `UNVERIFIED` state.
  - Added a typed shape for entries in the `provenance` array (source, retrieved_at, url, evidence_type, notes).

Verification performed

- Syntactic JSON validation for all modified files.
- Cross-file consistency checks for state names and variable names.

Suggested follow-ups

- Run schema validations against sample data (if available) to ensure no existing supplier-memory records break.
- Consider adding a CI job to validate JSON schemas on PRs.

Commits:
- ab5041f: Standardize profit variable to bid_price and update profit_formula
- 39317a6: Align configs/schemas: remove self-reference, add UNVERIFIED, structure gate rule, and improve provenance schema

