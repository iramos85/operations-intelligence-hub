# Architecture decision records

All decisions below are **proposed**, not accepted or implemented. For each, evaluate alternatives, feasibility, costs, risks and test evidence before changing status. Record the owner, approval and date when accepted.

| ID | Proposal | Alternatives / trade-offs | Validation |
| --- | --- | --- | --- |
| ADR-001 | Preserve sources; canonical reporting model | Replace sources or query each directly; mapping adds maintenance but reduces disruption | Confirm source interfaces and semantic mappings |
| ADR-002 | Schema validation and drift detection; last known-good publication | Fail open or fail entire dashboard; balance availability with accuracy | T02–T05 |
| ADR-003 | Data contracts and departmental stewardship | Informal agreements or centralized ownership; formal contracts add coordination | Owner-approved contract and change process |
| ADR-004 | Data minimization and access boundaries | Replicate all details or ingest aggregates only; evaluate drill-down needs and privacy | T08–T09 |
| ADR-005 | Prefer governed non-human identities | Managed identity, service principal, dedicated user identity; connector support and licensing determine feasibility | T10 and authentication proof of concept |
| ADR-006 | Configurable, department-specific, effective-dated KPIs | Hardcode definitions or rank departments by volume; configuration requires governance | T06–T07 |
| ADR-007 | DEV/UAT/PROD and baseline-based feedback triage | Direct deployment or phased release; environment cost and approval overhead | T11 |

Data platform, Power Apps, Power BI and orchestration choices remain open. The repository name and original description do not constitute a technology decision.
