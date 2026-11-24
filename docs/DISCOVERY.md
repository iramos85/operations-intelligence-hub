# Discovery record — 2026-11-24

Status: initial fictional stakeholder interview complete; findings awaiting review. Michelle, Director of Business Operations, is a simulated customer. All organizational details are synthetic.

## Current state
Four departments use existing tools: HR (SharePoint list), IT (third-party ticketing system), Finance (Excel), Facilities (shared mailbox and Excel). Operations analysts receive extracts or summaries and spend approximately three business days monthly consolidating a workbook and preparing leadership slides. Reports can be stale or inconsistent. Source owners retain restricted access; analysts do not currently have direct access to every system.

## Business needs
Daily visibility into received/completed requests, turnaround and backlog; meaningful department-specific performance against agreed targets rather than cross-team productivity rankings. Executives need company-wide visibility, managers their own department details, and analysts cross-department access for discrepancy investigation. Avoid copying sensitive employee, financial or security details without justification.

## Architect's discovery contributions
- Preserve existing departmental processes; consolidate through mappings into a common reporting definition.
- Detect source structure changes and distinguish stale, incomplete and failed data instead of generic errors.
- Meet department heads to agree data contracts, definitions and accountable owners.
- Establish current ownership and permissions before deciding collection and storage.
- Prefer governed non-human identities, with justified purpose, least privilege, accountable ownership and routine audits; managed identity is a candidate, not a selected implementation.
- Evaluate departments against their own agreed metrics.
- Maintain V1 scope through DEV, UAT and PROD; classify UAT feedback against the original requirements versus enhancements.

## Outstanding stakeholder validation
Department owners must approve source fields, completion semantics, targets and access; IT/security must confirm supported integration identities; sponsor must approve scope, budget and release criteria. No actual stakeholder sign-off has occurred.
