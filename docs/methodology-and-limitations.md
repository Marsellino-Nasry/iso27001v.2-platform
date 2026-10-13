# Methodology and Limitations

## Purpose

The ISMS Assurance Platform supports structured assessment and documentation of an Information Security Management System (ISMS). It is a practitioner support tool; it does not independently determine compliance or certification eligibility.

## Assessment workflow

1. **Define context and scope** — document the organization, ISMS boundaries, interfaces, dependencies, exclusions, and interested parties.
2. **Assess Clauses 4–10** — record the requirement, assessment conclusion, evidence inspected, and rationale.
3. **Assess information-security risks** — document risk scenarios, likelihood, impact, inherent/residual risk, owners, treatment decisions, and acceptance approvals.
4. **Prepare the SoA** — document whether each Annex A control is applicable, the rationale for inclusion or exclusion, implementation status, and relevant risk-treatment references.
5. **Assess control implementation and effectiveness** — distinguish documented design from implementation and operating evidence. Record sampling limitations.
6. **Record findings** — describe the criterion, condition, objective evidence, risk/consequence, root cause where established, and agreed corrective action.
7. **Track remediation** — assign accountable owners, due dates, milestones, status, and closure evidence.
8. **Review and report** — validate data and calculations, obtain appropriate approvals, and communicate limitations.

## Evidence quality

Conclusions should be traceable to objective evidence. Interviews may explain a process but ordinarily should be corroborated where the conclusion depends on implementation or operation. Record the evidence reference, period covered, sample selection, test performed, result, and any limitation.

## Risk and control decisions

- Use risk criteria approved by the organization.
- Link risk treatment decisions to the risk register and SoA where appropriate.
- Document risk-owner approval for risk acceptance.
- Ensure exclusions and applicability decisions are justified and reviewed.
- Do not assume that every Annex A control must be applicable, or that an excluded control needs no documented rationale.

## Reporting and score limitations

Any readiness index, maturity score, percentage, heat map, or threshold is an indicator generated from configured assumptions. Unless separately validated and formally adopted, it is not an ISO/IEC-defined certification threshold and must not replace auditor judgement, management review, or a certification body's decision.

Before each release, test calculation logic, edge cases, empty datasets, status mappings, export integrity, and consistency between on-screen data and generated reports.

## Security and privacy review

Before using the tool with client data, inspect local persistence, network requests, external dependencies, browser storage, exported files, access controls, and data-clearing behaviour. The statement that data remains in the browser must be verified against the actual source code and runtime behaviour.

## Limitations

- The tool does not provide legal advice or guarantee compliance.
- It cannot replace competent internal auditing, independent certification auditing, or management accountability.
- Control implementation status is not equivalent to operating effectiveness.
- Sample outputs are fictional examples and must not be treated as evidence from a real engagement.
