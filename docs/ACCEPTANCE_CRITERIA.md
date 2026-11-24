# Acceptance criteria — proposed, not executed

| Test | Requirement | Expected result |
| --- | --- | --- |
| T01 | FR-01, FR-02 | Synthetic HR and Finance records map to approved canonical fields; source IDs/provenance preserved; source records unchanged |
| T02 | FR-03 | Rename a required source field; incompatible import is rejected and last known-good data retained |
| T03 | FR-03 | Add an optional field; required mapping still works and change is logged |
| T04 | FR-03, FR-04 | Supply invalid/missing required values; rejected records or batch and completeness are reported according to approved publication rules |
| T05 | FR-04, NFR-03 | Simulate missed refresh; dashboard displays last successful update and stale warning, including aggregate limitations |
| T06 | FR-05 | Reconcile dashboard counts, turnaround and backlog against hand-calculated synthetic fixture |
| T07 | FR-06 | Change approved KPI target with future effective date; historical results retain prior definition |
| T08 | FR-07, NFR-01 | Test manager, executive and analyst identities; unauthorized detail cannot be accessed through UI or data endpoint |
| T09 | NFR-01 | Inspect ingested records and logs; excluded sensitive fields are absent |
| T10 | NFR-02, FR-08 | Verify documented identity, permissions, owner, audit evidence and failure alert routing; revoke access and observe controlled failure |
| T11 | NFR-04 | Demonstrate approved release path, UAT evidence and rollback procedure in available sandbox |
| T12 | NFR-05 | Verify fixtures are synthetic and evidence contains no credentials or employer data |

Exact fixture values, freshness cutoff, tolerated invalid-record threshold and role permissions require agreement before tests are finalized. No tests have been run.
