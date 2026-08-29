# Task 10 - Contributing Framework

## Aurex Digital Solutions

**Version:** 1.0
**Status:** Foundational Draft / Draft v1.0
**Institution:** Aurex Digital Solutions
**Phase:** Technical Governance
**Purpose:** Define Aurex Digital Solutions' institution-wide framework for responsible participation, contribution review, contributor progression, maintainer authority, and contribution governance across Aurex-controlled projects.

**Navigation:** [Previous: Open-Source & Licensing Framework](./OPEN-SOURCE-AND-LICENSING-FRAMEWORK.md) | [Home: Documentation Index](./README.md) | [Next: Security & Responsible Technology Policy](./SECURITY-AND-RESPONSIBLE-TECHNOLOGY-POLICY.md)

Task 9 established how Aurex technology can be legally shared, reused, modified, distributed, and governed through open-source and licensing rules.

Task 10 establishes how people participate in building Aurex technology and documentation responsibly.

> Open source provides permission to participate. A contributing framework provides the pathway to participate responsibly.

This framework is institution-wide policy direction. It does not create repository-specific automation, branch protection, DCO enforcement, issue templates, pull request templates, or contributor permissions by itself. Repository-level guides should implement this framework in proportion to each repository's maturity, risk, and operational purpose.

---

## 1. Purpose

The Contributing Framework establishes a common institutional model for participation in Aurex projects.

It governs:

- contributor entry;
- contribution types;
- onboarding;
- issue selection;
- development workflow;
- commits;
- pull requests;
- reviews;
- testing;
- documentation;
- contribution licensing;
- technical decision participation;
- contributor progression;
- maintainer responsibilities;
- recognition;
- disputes;
- rejection;
- inactivity and offboarding.

Individual repositories may add project-specific requirements, but they should remain consistent with this framework.

---

## 2. Contribution Philosophy

Aurex should operate on a simple principle:

> Contribution should be open to capable participants, while authority is earned through demonstrated responsibility and explicitly granted through governance.

Therefore:

```text
OPEN PARTICIPATION
       !=
UNRESTRICTED AUTHORITY
```

Anyone may potentially contribute.

Not everyone automatically receives:

- merge authority;
- repository administration;
- deployment access;
- production credentials;
- institutional decision rights.

Participation can be open while authority remains explicit, limited, and accountable.

---

## 3. Why Contributors Matter

Aurex's mission is larger than one founder or engineering team.

Building African digital energy infrastructure requires expertise across:

- electrical engineering;
- power systems;
- software engineering;
- embedded systems;
- cybersecurity;
- data engineering;
- AI/ML;
- economics;
- policy;
- regulation;
- research;
- technical writing;
- field operations.

The contribution model should turn that diversity into coordinated institutional capability.

---

## 4. Contribution Is Broader Than Code

Aurex should recognize contributions including:

```text
CODE
DOCUMENTATION
RESEARCH
TESTING
BUG REPORTS
DESIGN
DEVICE INTEGRATIONS
DATA MODELS
SECURITY
SPECIFICATIONS
TRANSLATION
FIELD KNOWLEDGE
ISSUE TRIAGE
COMMUNITY SUPPORT
```

Someone does not need to be a software engineer to contribute meaningfully.

---

## 5. Contributor Categories

Aurex should distinguish participation levels without inventing fictional current role holders.

### Visitor

Reads and uses public resources.

### Participant

Engages in discussions, issues, reviews, or community activities.

### Contributor

Has submitted accepted or meaningful work.

### Regular Contributor

Contributes consistently and demonstrates project understanding.

### Maintainer

Has explicitly delegated responsibility for defined project areas.

### Technical Lead

Provides technical stewardship within defined authority.

### Institutional Role Holder

Exercises authority established by Aurex governance rather than merely repository participation.

This progression is earned and appointed, not automatic.

---

## 6. Contributor Journey

A healthy pathway should look like:

```text
DISCOVER AUREX
      |
      v
READ DOCUMENTATION
      |
      v
UNDERSTAND CODE OF CONDUCT
      |
      v
FIND CONTRIBUTION
      |
      v
DISCUSS IF NECESSARY
      |
      v
BUILD / WRITE / RESEARCH
      |
      v
TEST
      |
      v
SUBMIT
      |
      v
REVIEW
      |
      v
IMPROVE
      |
      v
ACCEPT
      |
      v
CONTINUE CONTRIBUTING
      |
      v
EARN GREATER RESPONSIBILITY
```

The system should make the first contribution understandable.

---

## 7. Contributor Entry Requirements

Before contributing, a participant should understand:

1. the repository's purpose;
2. maturity level;
3. applicable license;
4. Code of Conduct;
5. contribution instructions;
6. security-reporting rules;
7. relevant technical standards.

Contributors should not be required to understand the entire Aurex institution before fixing a typo or reporting a bug.

Requirements should be proportional to contribution risk.

---

## 8. Code of Conduct

Participation in Aurex-controlled projects is subject to the institutional [Code of Conduct](./CODE-OF-CONDUCT.md).

This applies to:

- issues;
- pull requests;
- reviews;
- discussions;
- community channels;
- meetings;
- technical debates;
- field collaboration.

Technical disagreement is welcome.

Personal hostility is not.

---

## 9. Contribution Licensing

Contributions must comply with the applicable project license and the [Open-Source & Licensing Framework](./OPEN-SOURCE-AND-LICENSING-FRAMEWORK.md).

A contributor must have the right to submit the work.

Contributors must not knowingly submit:

- proprietary employer code without permission;
- confidential information;
- incompatible licensed code;
- copied third-party work without authorization;
- unlawfully obtained data.

---

## 10. DCO Direction

Aurex's preferred initial contribution attestation is the Developer Certificate of Origin (DCO), subject to final legal-readiness review.

Where enabled, contributors certify contributions through a sign-off such as:

```text
Signed-off-by: Contributor Name <email@example.com>
```

The sign-off means the contributor asserts that they have the right to submit the contribution under the project's applicable terms.

It is not merely decorative commit text.

This document does not enable DCO enforcement by itself. Task 20 and repository-specific implementation work should confirm the legal and operational readiness of any enforcement mechanism.

---

## 11. Contribution Starting Point

Repositories should make contribution opportunities discoverable.

Useful issue labels may include:

```text
good first issue
help wanted
documentation
bug
research
testing
integration
security
discussion
```

Aurex should avoid creating hundreds of unmaintained labels.

Use only categories that help contributors navigate work.

---

## 12. Before Starting Work

Small contributions may proceed directly.

For substantial work, contributors should first open or identify an issue.

This helps prevent:

```text
CONTRIBUTOR
     |
     v
works for three weeks
     |
     v
submits large PR
     |
     v
architecture incompatible
     |
     v
PR rejected
```

For major changes:

> Discuss before building.

---

## 13. Issue Requirements

A useful technical issue should explain:

- problem;
- context;
- expected behavior;
- current behavior where relevant;
- evidence;
- affected component;
- proposed outcome.

Issues should describe problems before prescribing solutions where practical.

---

## 14. Feature Proposals

Significant features should explain:

```text
PROBLEM
   |
   v
USER / SYSTEM NEED
   |
   v
REQUIREMENTS
   |
   v
ALTERNATIVES
   |
   v
PROPOSED APPROACH
   |
   v
IMPACT
```

Major architecture changes may require an Architecture Decision Record (ADR).

---

## 15. Branching

Project-specific repositories may define their own branching strategy.

A simple default could be:

```text
main
 |
 +-- feature/...
 +-- fix/...
 +-- docs/...
 +-- research/...
```

The exact workflow should remain proportional to project maturity.

A two-person prototype does not require enterprise-scale GitFlow.

---

## 16. Main Branch

The primary branch should represent the repository's authoritative development state according to that project's maturity.

Direct pushes to protected critical branches should progressively be restricted.

As teams grow:

```text
CHANGE
   |
   v
BRANCH
   |
   v
PULL REQUEST
   |
   v
REVIEW
   |
   v
CHECKS
   |
   v
MERGE
```

---

## 17. Commit Standard

Commits should be:

- understandable;
- scoped;
- reviewable;
- attributable.

A useful commit message should explain what changed.

Examples:

```text
feat: add inverter telemetry adapter
fix: handle missing meter timestamp
docs: clarify facility EMS architecture
test: add battery controller integration tests
```

Aurex may use Conventional Commits where useful, but it should not turn commit syntax into bureaucracy.

---

## 18. Atomic Changes

Prefer commits and pull requests that represent coherent changes.

Avoid combining:

```text
NEW FEATURE
+
UNRELATED REFACTOR
+
FORMATTING ENTIRE REPOSITORY
+
DEPENDENCY UPGRADE
```

in one review unless necessary.

Smaller coherent changes are easier to:

- review;
- test;
- revert;
- understand.

---

## 19. Pull Request Requirements

A pull request should normally answer:

- What changed?
- Why?
- How was it tested?
- What risks exist?
- What documentation changed?
- Does it introduce dependencies?
- Does it affect compatibility?
- Does it affect security?

Not every typo correction needs a long explanation.

Again: proportionality.

---

## 20. Pull Request Template

A common Aurex template may eventually resemble:

```text
## Problem

## Change

## Testing

## Documentation

## Compatibility Impact

## Security Impact

## Related Issue

## Checklist
- [ ] Tests pass
- [ ] Documentation updated
- [ ] Licensing/provenance checked
- [ ] No secrets included
```

Repositories can extend this where necessary.

This framework does not create a pull request template file by itself.

---

## 21. Review Principle

Code review exists to improve the system, not demonstrate reviewer superiority.

Reviews should evaluate:

- correctness;
- architecture;
- maintainability;
- tests;
- security;
- performance where relevant;
- documentation;
- licensing;
- compatibility.

Feedback should be specific and actionable.

---

## 22. Review the Work, Not the Person

Good:

> This implementation can race when two telemetry updates arrive simultaneously.

Poor:

> You clearly do not understand concurrency.

Aurex should maintain strong engineering criticism without degrading contributors.

---

## 23. Review Authority

Review and approval are different.

Someone may be technically capable of reviewing a change without having authority to merge it.

```text
REVIEW
   !=
APPROVAL
   !=
MERGE AUTHORITY
   !=
DEPLOYMENT AUTHORITY
```

This aligns directly with the [Organization Structure & Decision Rights](./ORGANIZATION-STRUCTURE-AND-DECISION-RIGHTS.md).

---

## 24. Merge Requirements

Depending on project maturity, merge may require:

- successful CI;
- required review;
- resolved discussions;
- tests;
- DCO check;
- security checks;
- license checks;
- documentation updates.

Critical infrastructure components should require stronger gates than experimental research repositories.

---

## 25. Testing

Contributors should test changes at the appropriate level.

Potential levels:

```text
UNIT
 |
 v
COMPONENT
 |
 v
INTEGRATION
 |
 v
SIMULATION
 |
 v
HARDWARE-IN-THE-LOOP
 |
 v
FIELD VALIDATION
```

Not every project reaches every stage.

Claims must match actual testing.

---

## 26. Energy-System Contributions

Changes capable of affecting physical energy infrastructure require additional caution.

Examples:

- inverter control;
- battery dispatch;
- generator control;
- protection logic;
- grid interaction;
- load shedding.

Such changes should not move directly from:

```text
PULL REQUEST
     |
     v
LIVE FACILITY
```

They should follow the relevant validation and deployment process.

Energy-control changes require stronger validation than ordinary software, documentation, or research changes.

---

## 27. Documentation Requirement

A feature is not complete merely because the code works.

Relevant changes should update:

- user documentation;
- API documentation;
- architecture;
- configuration examples;
- operational instructions;
- changelog where applicable.

> Undocumented capability becomes institutional debt.

---

## 28. Architecture Changes/ADRs

Material architecture decisions should use an ADR where appropriate.

Contributors should be able to understand:

- what was decided;
- why;
- alternatives;
- consequences.

This prevents the architecture from becoming dependent on oral history.

---

## 29. Dependency Contributions

New dependencies require review appropriate to their importance.

Consider:

- license;
- security;
- maintenance;
- provenance;
- size;
- necessity;
- alternatives.

A contributor should not add a large dependency merely to avoid writing a small function.

---

## 30. Security Contributions

Potential vulnerabilities should not initially be posted publicly where doing so would create unnecessary exploitation risk.

They should follow Aurex's private security-reporting mechanism once established.

Task 11 defines that process through the Security & Responsible Technology Policy.

---

## 31. Secrets

Contributors must never intentionally commit:

- passwords;
- API keys;
- private keys;
- tokens;
- production credentials.

If exposed:

> Treat the credential as compromised.

Rotate or revoke it according to the applicable security process.

---

## 32. Data Contributions

Datasets require provenance.

A contributor should identify:

- source;
- ownership;
- permission;
- license;
- privacy constraints;
- security considerations.

"Found online" is not sufficient provenance.

Operational energy data must be treated carefully because it may expose people, facilities, commercial activity, grid behavior, or sensitive infrastructure.

---

## 33. AI-Assisted Contributions

AI tools may assist contributors.

The contributor remains responsible for:

- correctness;
- security;
- licensing;
- provenance;
- testing;
- documentation.

AI-generated work receives no exemption from review.

AI capability does not automatically create decision authority.

---

## 34. Documentation Contributions

Documentation contributions should be treated as first-class engineering work.

This includes:

- architecture explanations;
- tutorials;
- diagrams;
- specifications;
- operational guides;
- translations;
- examples.

Good documentation expands the number of people capable of using and improving Aurex technology.

---

## 35. Research Contributions

Research contributions should identify:

- research question;
- methodology;
- assumptions;
- data;
- limitations;
- results;
- reproducibility where practical.

Aurex should accept negative results where they are methodologically sound.

---

## 36. Contribution Decision

A contribution may be:

```text
ACCEPTED

ACCEPTED WITH CHANGES

REQUESTED FOR REVISION

DEFERRED

REJECTED
```

Rejection is not necessarily a judgment on contributor capability.

A technically valid contribution may still conflict with:

- architecture;
- scope;
- security;
- roadmap;
- licensing;
- maintenance capacity.

---

## 37. Rejection Standard

Where practical, rejection should explain why.

Example:

> The implementation works, but introduces a vendor-specific dependency into the interoperability layer. We need this capability behind the existing abstraction.

That teaches the contributor how the system is designed.

---

## 38. Maintainers

Maintainers are stewards, not owners of community territory.

Responsibilities may include:

- triage;
- reviews;
- merges;
- releases;
- documentation quality;
- contributor support;
- security escalation;
- roadmap input;
- technical consistency.

Maintainer authority must be explicitly granted.

This document does not appoint any maintainer.

---

## 39. Maintainer Appointment

Maintainer status should follow evidence of:

```text
CONTRIBUTION
      +
TECHNICAL COMPETENCE
      +
RELIABILITY
      +
CODE OF CONDUCT
      +
PROJECT UNDERSTANDING
      |
      v
MAINTAINER CANDIDACY
```

Not friendship.

Not job title alone.

Not number of followers.

Appointment requires an explicit governance or repository-authority decision.

---

## 40. Maintainer Scope

A maintainer may be responsible for only part of a system.

Example:

```text
PROJECT
|
+-- Device Integrations
+-- Data Platform
+-- Documentation
```

Authority should match expertise and accountability.

No maintainer scope should be assumed until it is explicitly granted.

---

## 41. Contributor Progression

Aurex should create a visible path:

```text
PARTICIPANT
     |
     v
CONTRIBUTOR
     |
     v
REGULAR CONTRIBUTOR
     |
     v
MAINTAINER
     |
     v
TECHNICAL LEADERSHIP
```

Progression is not guaranteed by time served.

It follows demonstrated contribution and institutional need.

---

## 42. Recognition

Aurex should recognize contributors through appropriate mechanisms such as:

- Git history;
- release notes;
- contributor lists;
- acknowledgements;
- maintainer records;
- research authorship where justified.

Recognition should reflect actual contribution.

---

## 43. No Contribution Purchasing Authority

Financial sponsorship does not automatically create technical authority.

Similarly:

```text
DONATION
   !=
MERGE RIGHTS

FUNDING
   !=
ARCHITECTURE CONTROL

PARTNERSHIP
   !=
TECHNICAL VETO
```

Formal agreements may establish legitimate decision arrangements, but these must be explicit.

---

## 44. Contributor Conflicts of Interest

Contributors should disclose material interests when relevant.

Example:

A contributor proposing a proprietary vendor dependency while employed by that vendor should disclose the relationship.

The contribution can still be technically excellent.

Disclosure enables fair evaluation.

---

## 45. Disputes

Technical disagreements should first be resolved through:

1. evidence;
2. documentation;
3. technical discussion;
4. responsible maintainer decision;
5. escalation where necessary.

Personal authority should not replace technical reasoning where evidence can resolve the question.

---

## 46. Appeals

Significant contribution disputes should eventually have an escalation path.

Conceptually:

```text
CONTRIBUTOR
     |
     v
MAINTAINER
     |
     v
TECHNICAL LEAD
     |
     v
TECHNICAL GOVERNANCE
```

Not every rejected pull request needs institutional arbitration.

Appeals are for material disputes.

---

## 47. Inactivity

Maintainer permissions should not necessarily remain permanent.

Long inactivity may trigger:

- status review;
- access reduction;
- transfer of responsibility;
- emeritus recognition.

This protects repositories from abandoned authority.

---

## 48. Offboarding

When a contributor or maintainer leaves a privileged role:

- permissions should be reviewed;
- credentials revoked where appropriate;
- responsibilities transferred;
- open work documented;
- institutional records updated.

Their historical contributions remain attributed.

---

## 49. Community Health

Aurex should monitor whether contributors encounter:

- unclear documentation;
- unanswered issues;
- hostile reviews;
- excessively slow merges;
- inaccessible maintainers;
- unclear roadmap;
- excessive bureaucracy.

A technically open repository can still be socially impossible to contribute to.

---

## 50. Contribution Metrics

Useful metrics may eventually include:

- active contributors;
- first-time contributors;
- review time;
- issue response time;
- accepted contributions;
- upstream contributions;
- maintainer concentration;
- abandoned PRs.

Metrics should diagnose ecosystem health, not become vanity statistics.

---

## 51. Repository Contribution Baseline

A mature public Aurex repository should progressively expose:

```text
README.md
LICENSE
CONTRIBUTING.md
CODE_OF_CONDUCT.md
SECURITY.md
Issue templates
Pull request template
Maturity status
Maintainers / ownership
```

These repository files should point to institutional policies where appropriate rather than duplicating entire frameworks.

This task does not create those files automatically.

---

## 52. Institutional vs Repository Documentation

This distinction is important.

### Institution level

Defines Aurex-wide rules:

```text
Aurex Digital Solutions / Organization Docs
```

### Repository level

Defines how those rules apply to a specific project.

For example:

```text
INSTITUTIONAL
CONTRIBUTING FRAMEWORK
        |
        v
PROJECT
CONTRIBUTING.md
        |
        v
COMPONENT-SPECIFIC
DEVELOPER GUIDE
```

Repository-level CONTRIBUTING guides should implement rather than duplicate this institution-wide framework.

That prevents policy duplication.

---

## 53. Contribution Governance Principle

The entire framework can be summarized as:

> Participation should be open. Responsibility should be earned. Authority should be explicit. Changes should be reviewable. Decisions should be traceable.

---

## 54. Current Aurex Reality

At Aurex's current maturity, contribution governance should remain lightweight.

The immediate practical baseline is:

```text
README
   |
   v
CODE OF CONDUCT
   |
   v
LICENSE
   |
   v
CONTRIBUTING GUIDE
   |
   v
ISSUES
   |
   v
BRANCH
   |
   v
PULL REQUEST
   |
   v
REVIEW
   |
   v
MERGE
```

Do not install enterprise bureaucracy before a contributor community exists.

---

## 55. How Task 11 Continues This Framework

Task 10 opens Aurex to participation.

Task 11 is now:

**Security & Responsible Technology Policy**

It defines:

- security governance;
- threat modelling;
- secure development;
- vulnerability disclosure;
- secrets management;
- identity and access;
- dependency security;
- supply-chain security;
- incident response;
- infrastructure security;
- operational technology and energy-system security;
- AI safety and responsible automation;
- responsible release rules for sensitive energy infrastructure work.

Task 11 establishes the security boundary contributors must respect.

## 56. How Task 12 Continues This Framework

Task 11 defines secure and responsible technology boundaries.

Task 12 now defines the wider ethical, sovereignty, and public-interest framework that guides how Aurex technology should serve African energy systems and communities.

The next completed artifact is:

[Task 12 - Ethics, Sovereignty & Public-Interest Framework](./ETHICS-SOVEREIGNTY-AND-PUBLIC-INTEREST-FRAMEWORK.md)

Task 13 begins the Operations phase through the Risk Management Framework. Task 14 - Operating Model, Task 15 - Organization Roadmap, and Task 16 - Funding & Financial Framework are now complete. Task 17 - Partnership & Stakeholder Framework is now complete as a Draft v1.0 foundational artifact. Task 18 - Research & Innovation Framework is the next step.

---

## 57. Institutional Build Status

```text
01 Founding Thesis                         COMPLETE / DRAFT v1.0
02 Official Problem Statement              COMPLETE / DRAFT v1.0
03 Vision, Mission & Purpose               COMPLETE / DRAFT v1.0
04 Values & Institutional Principles       COMPLETE / DRAFT v1.0
05 Code of Conduct                         COMPLETE / DRAFT v1.0
06 Organization Charter                    COMPLETE / DRAFT v1.0
07 Governance Framework                    COMPLETE / DRAFT v1.0
08 Organization Structure & Decision Rights COMPLETE / DRAFT v1.0
09 Open-Source & Licensing Framework       COMPLETE / DRAFT v1.0
10 Contributing Framework                  COMPLETE / DRAFT v1.0
11 Security & Responsible Technology Policy COMPLETE / DRAFT v1.0
12 Ethics, Sovereignty & Public-Interest Framework COMPLETE / DRAFT v1.0
13 Risk Management Framework               COMPLETE / DRAFT v1.0
14 Operating Model                         COMPLETE / DRAFT v1.0
15 Organization Roadmap                    COMPLETE / DRAFT v1.0
16 Funding & Financial Framework           COMPLETE / DRAFT v1.0
17 Partnership & Stakeholder Framework     COMPLETE / DRAFT v1.0
18 Research & Innovation Framework         NEXT
19 Programme Governance Framework          PLANNED
20 Legal & Institutional Readiness         PLANNED
21 Organization Documentation Baseline v1.0 PLANNED
```

Task 10 is complete as a Draft v1.0 foundational artifact.

Previous document: [Open-Source & Licensing Framework](./OPEN-SOURCE-AND-LICENSING-FRAMEWORK.md)

Home: [Documentation Index](./README.md)

Next document: [Security & Responsible Technology Policy](./SECURITY-AND-RESPONSIBLE-TECHNOLOGY-POLICY.md)
