# Requirements baseline — draft

These IDs are stable references for scope, design and testing. Targets and implementation remain subject to simulated stakeholder approval.

| ID | Requirement | Priority |
| --- | --- | --- |
| FR-01 | Preserve existing departmental systems and ingest approved operational fields | Must |
| FR-02 | Translate source-specific fields and statuses to a canonical model without losing source provenance | Must |
| FR-03 | Validate source schema and records; detect incompatible changes, prevent invalid publication and record failures | Must |
| FR-04 | Expose last successful refresh, completeness, validity and import execution status separately | Must |
| FR-05 | Report received/completed requests, turnaround and backlog with documented metric definitions | Must |
| FR-06 | Evaluate department-specific KPIs against approved, effective-dated targets; avoid unsupported productivity rankings | Must |
| FR-07 | Provide executive aggregate, department-scoped manager and authorized cross-department analyst views | Must |
| FR-08 | Maintain approved source mappings, data contracts, ownership and import history | Must |
| NFR-01 | Minimize collected data; enforce access at data/service layer, not only UI | Must |
| NFR-02 | Use least-privilege, sustainable integration identity with accountable ownership and auditing | Must |
| NFR-03 | Target daily reporting refresh; agreed cutoff, timezone and failure thresholds pending | Must |
| NFR-04 | Separate development, acceptance testing and production release; document approvals and rollback | Must |
| NFR-05 | Use synthetic data only; document assumptions, tests and limitations | Must |

## Ownership
Business owners approve meanings and targets; security approves access; architect recommends and owns technical implementation within delegated authority; sponsor approves scope/budget. No production authorization is implied.
