# Task 8 - Organization Structure & Decision Rights

## Aurex Digital Solutions

**Version:** 1.0  
**Status:** Foundational Draft / Draft v1.0  
**Institution:** Aurex Digital Solutions  
**Current maturity:** Founder-led / pre-formalization  
**Purpose:** Define institutional functions, role accountabilities, decision ownership, delegation, and authority boundaries

**Navigation:** [Previous: Governance Framework](./GOVERNANCE-FRAMEWORK.md) | [Home: Documentation Index](./README.md) | [Next: Open-Source & Licensing Framework](./OPEN-SOURCE-AND-LICENSING-FRAMEWORK.md)

> This document describes roles and decision rights. It does not create employees, committees, legal powers, or authority to control third-party infrastructure.

## 1. Role of This Document

The [Governance Framework](./GOVERNANCE-FRAMEWORK.md) defines how Aurex governs. This document makes that model operational by defining:

- institutional functions and current staffing;
- role purpose and accountability;
- decision ownership and approval levels;
- delegation and access boundaries;
- role appointment and review principles.

A role describes a function. Accountability describes the outcome it owns. Authority describes what it may decide. A title alone creates none of these.

## 2. Current Structure

Aurex is currently founder-led and pre-formalization. The institutional model should distinguish required functions from actual appointments.

```text
Founder
  +-- Institution building and executive function
  +-- Technical development
  +-- Research and innovation
  +-- Programme development
  +-- Operations, partnerships, finance, and assurance as required
```

Current holder:

| Function | Current holder | Status |
| --- | --- | --- |
| Founder and transitional executive | Ayiemba Rodgers | Active |
| Technical, research, programme, operations, finance, partnerships, and assurance functions | Founder-led or external support as needed | Not separately staffed |
| Governing body | TBD | Not constituted |

This is a truthful minimum structure, not a claim of a larger organization.

## 3. Target Functional Model

Functions should separate as workload, risk, resources, and accountability require:

```text
Governing oversight
        -> Executive leadership
        -> Institutional functions
        -> Programmes and projects
        -> Delivery teams

Assurance functions review across the model.
```

Potential functions include Engineering & Technology, Research & Innovation, Programmes, Operations, Finance, Partnerships, Security, Risk, Legal/Compliance, and Ethics/Public Interest. They should be created because work requires them, not for appearance.

## 4. Core Roles

### Founder

Provides founding stewardship, strategic direction, institutional formation, initial technical direction, programme initiation, early resource allocation, and initial representation during the transitional stage. Founder authority remains subject to law, safety, contracts, the Charter, governance, and adopted policies.

### Executive function

Translates approved direction into strategy execution, people, resources, programmes, operations, partnerships, risk implementation, and reporting. It is currently covered by the founder.

### Engineering and Technology

Owns technical architecture, software, systems integration, interoperability, testing, releases, technical documentation, and engineering quality within approved scope and constraints. It cannot grant itself authority over third-party infrastructure.

### Research and Innovation

Owns research questions, methods, experiments, modelling, evidence, validation, and technology assessment. Research asks whether a claim is true; engineering determines how to build a credible solution.

### Programme function

Owns programme objectives, scope, milestones, dependencies, resources, risks, evidence gates, reporting, and outcomes. Every significant programme must have one accountable owner.

### Operations and Finance

Operations maintains institutional records, procurement coordination, assets, internal systems, and continuity. Finance manages budgets, expenditure controls, reporting, grants, revenue, and audit support. Separation of requesting, approving, receiving, and reconciling funds should increase as Aurex grows.

### Partnerships

Owns documented relationships with utilities, governments, universities, communities, funders, technology providers, and other stakeholders. Discussions, endorsements, formal partnerships, legal authority, and operational permission must remain distinct.

### Assurance

Security, risk, legal, ethics, research integrity, safety, and financial control functions provide proportionate review and challenge. Delivery teams should not always be the sole authority determining whether work is safe, compliant, or ready.

Detailed function requirements are linked through the [Operating Model](./OPERATING-MODEL.md), [Security & Responsible Technology Policy](./SECURITY-AND-RESPONSIBLE-TECHNOLOGY-POLICY.md), [Risk Management Framework](./RISK-MANAGEMENT-FRAMEWORK.md), [Legal & Institutional Readiness](./LEGAL-AND-INSTITUTIONAL-READINESS.md), and [Ethics, Sovereignty & Public-Interest Framework](./ETHICS-SOVEREIGNTY-AND-PUBLIC-INTEREST-FRAMEWORK.md).

## 5. Decision-Rights Model

Aurex uses five decision roles:

- **P - Propose:** develops the proposal
- **R - Review:** examines evidence, risks, constraints, and implications
- **A - Approve:** authorizes the decision within defined authority
- **E - Execute:** implements the approved decision
- **I - Inform:** must be informed

Every significant decision should answer:

```text
Who proposes?
Who reviews?
Who approves?
Who executes?
Who must be informed?
```

These labels clarify workflow; they do not create legal authority. Decision rights should attach to roles, not personalities, wherever possible.

## 6. Founding-Stage Decision Matrix

| Decision | Propose | Review | Approve | Execute | Inform |
| --- | --- | --- | --- | --- | --- |
| Routine documentation or engineering | Contributor or technical function | Maintainer or technical review | Delegated role or founder | Contributor or engineering | Affected users |
| Architecture change | Technical function | Technical and security review | Founder or delegated technical authority | Engineering | Affected programmes |
| Research study | Research function | Technical or ethics review as needed | Programme owner or founder | Research | Relevant stakeholders |
| New project or programme | Programme function | Technical, resource, and risk review | Founder during formation | Programme owner | Relevant functions |
| Material expenditure | Responsible function | Finance or resource review | Founder within current authority | Operations or finance | Institutional records |
| External partnership | Partnerships function or founder | Relevant technical, legal, finance, and assurance review | Founder during formation | Authorized representative | Relevant functions |
| Public institutional position | Relevant function | Institutional review | Founder or authorized executive | Authorized representative | Institution |
| Charter or mission change | Authorized proposer | Governance review | Founder during transition; future highest authority | Institutional administration | Institution |

This matrix is transitional and must be updated when roles and governing bodies are formally appointed.

## 7. Reserved Decisions

The highest authorized level should approve decisions affecting:

- institutional purpose or mission;
- Charter provisions or fundamental governance;
- merger, dissolution, or transfer of institutional control;
- disposal of core intellectual property;
- major borrowing or materially different business activity;
- appointment or removal of top executive leadership.

Until formal governance exists, these decisions remain founder-reserved unless limited by law, contract, funding conditions, or another valid authority.

## 8. Delegation and Appointment

A delegation must identify the delegator, recipient, scope, decision and financial limits, duration, reporting requirements, conditions, and revocation mechanism. Delegated authority cannot exceed the authority of the delegating person or body.

A role appointment should record the role, holder, effective date, authority source, accountability, reporting relationship, term where relevant, and approval source. Unfilled roles should remain marked `TBD`; fictional staffing weakens institutional accuracy.

A role and delegation register should be maintained as Aurex grows.

## 9. Access and Technical Rights

Access should follow role and minimum required capability:

```text
Role -> Required capability -> Minimum access -> Audit and review
```

Repository roles such as contributor, maintainer, technical lead, repository administrator, and organization administrator should remain distinct and use least privilege. Technical, security, data, licensing, and release requirements are defined in the [Open-Source & Licensing Framework](./OPEN-SOURCE-AND-LICENSING-FRAMEWORK.md), [Contributing Framework](./CONTRIBUTING-FRAMEWORK.md), and [Security & Responsible Technology Policy](./SECURITY-AND-RESPONSIBLE-TECHNOLOGY-POLICY.md).

## 10. Escalation and Stop-Work

A role holder must escalate when a decision exceeds delegated authority or involves safety, cybersecurity, data, legal or regulatory uncertainty, material budget deviation, conflict of interest, significant failure, unauthorized control, or likely harm to people, communities, partners, systems, or public trust.

Anyone may raise a good-faith stop-work concern for credible safety or security risk. It must receive prompt review without retaliation. Emergency protective action may be taken by designated roles, documented afterward, and reviewed; emergency action is not a permanent governance bypass.

The [Code of Conduct](./CODE-OF-CONDUCT.md) and [Governance Framework](./GOVERNANCE-FRAMEWORK.md) define the related conduct and escalation standards.

## 11. Structural Principles

- Structure follows capability, workload, risk, resources, and accountability.
- Every material outcome has one ultimately accountable role, even when many people contribute.
- Delivery and assurance should gain independent separation as risk increases.
- Institutional knowledge should be documented, accessible, and transferable.
- Founder approval should decrease for routine work as delegated authority and governance mature.
- Roles and structures should be reviewed, modified, renewed, or retired as the institution changes.

## 12. Maturity Path

```text
Founder-led
    -> Defined functions
    -> Delegated roles
    -> Independent assurance
    -> Institutional governance
```

Aurex should be able to operate when a key person is unavailable by maintaining records, backups, controlled credentials, and handover procedures. The [Organization Roadmap](./ORGANIZATION-ROADMAP.md) and [Governance Framework](./GOVERNANCE-FRAMEWORK.md) provide the broader maturity context.

## Document Status

This document is a Foundational Draft v1.0 for Aurex's founder-led, pre-formalization stage. Repository-wide status is maintained in the [README](./README.md) and [Organization Documentation Baseline v1.0](./ORGANIZATION-DOCUMENTATION-BASELINE-V1.0.md).

**Previous:** [Governance Framework](./GOVERNANCE-FRAMEWORK.md)
**Home:** [Documentation Index](./README.md)
**Next:** [Open-Source & Licensing Framework](./OPEN-SOURCE-AND-LICENSING-FRAMEWORK.md)
