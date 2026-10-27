# Red Energy — demo source documents (SYNTHETIC)

Document-side context for a Databricks Genie ontology demo. Red Energy is a **fictional** Australian energy retailer; no real customers, people or personal data appear here.

Genie answers business questions by reasoning across governed data in Unity Catalog *and* the documents a business runs on — the issues in this repo, the linked Confluence pages, and the email trail.

## The situation

A cost-reduction programme removed the control that caught metering data problems. When the market data feed changed format, nothing noticed. **71 households** were billed on estimated reads, leaving **A$31,185.78** of revenue unsettled and **22 already-at-risk customers** (A$61,113.86 of lifetime value) with a legitimate grievance.

The programme's tracker reports **A$73,000.00** of savings on a **retired** margin definition. Restated on the approved one, the net is **A$30,692.28** — **58.0% lower** — and the unsettled revenue alone exceeds it.

## Issues

1. Risk: automating meter-read validation removes our only feed-format detection
2. INCIDENT: metering feed format change not detected
3. Stop collections on any bill raised from an estimated read
4. Re-read capacity cannot clear estimated reads inside a billing cycle
5. Cost programme tracker reports on a retired margin definition
6. Offshore support script has no path for "my bill is an estimate"

*Every figure here is generated from the synthetic lakehouse, so documents and data always reconcile.*
