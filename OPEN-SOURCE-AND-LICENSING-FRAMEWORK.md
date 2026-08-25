# Task 9 - Open-Source & Licensing Framework

## Aurex Digital Solutions

**Version:** 1.0  
**Status:** Foundational Draft / Draft v1.0  
**Institution:** Aurex Digital Solutions  
**Phase:** Technical Governance  
**Purpose:** Define Aurex Digital Solutions' draft institutional policy direction for open-source software, licensing, contributor intellectual property, third-party dependencies, documentation, data, trademarks, security-sensitive materials, and open technical collaboration.

**Navigation:** [Previous: Organization Structure & Decision Rights](./ORGANIZATION-STRUCTURE-AND-DECISION-RIGHTS.md) | [Home: Documentation Index](./README.md) | [Next: Contributing Framework](./CONTRIBUTING-FRAMEWORK.md)

Task 8 established who holds responsibility and decision authority.

Task 9 establishes the legal and operational rules governing how Aurex creates, uses, modifies, distributes, and contributes open technology.

This framework is institutional policy direction. It is not legal advice, not a final legal opinion, not a claim that Aurex has completed legal incorporation, and not a claim that all unresolved intellectual-property ownership questions have been settled.

> Open source is not simply public code. It is software distributed under permissions defined by a license.

For Aurex, this distinction matters because future infrastructure may combine Aurex-developed software with upstream open-source projects, vendor integrations, standards, documentation, data, AI models, research outputs, and potentially proprietary components.

---

## 1. Purpose

This framework establishes Aurex's draft institutional approach to:

- open-source software;
- licensing;
- copyright;
- third-party dependencies;
- upstream projects;
- documentation;
- datasets;
- AI models and artifacts;
- contributor intellectual property;
- license compatibility;
- software provenance;
- trademarks;
- proprietary exceptions;
- security-sensitive materials.

The objective is:

> Open by default where responsible, interoperable by design, legally compliant, and explicit about exceptions.

This document guides future decisions. It does not automatically apply a license to this repository or to any existing Aurex codebase.

---

## 2. Why Open Source Matters to Aurex

Aurex is attempting to address infrastructure fragmentation.

Building another closed ecosystem would contradict that objective.

Open-source development can support:

```text
TRANSPARENCY
      +
INTEROPERABILITY
      +
COLLABORATION
      +
REUSE
      +
AUDITABILITY
      +
LOCAL CAPABILITY
      +
VENDOR DIVERSITY
      |
      v
SUSTAINABLE DIGITAL INFRASTRUCTURE
```

But open source does not automatically guarantee any of these outcomes.

Good architecture, security, governance, maintenance, and legal clarity are still required.

---

## 3. Aurex Open-Source Principle

The institutional principle is:

> Aurex will prefer open standards, open interfaces, reusable open-source components, and openly governed technical collaboration where doing so supports interoperability, security, sustainability, and the public interest.

This is intentionally not:

> Everything Aurex creates must always be public.

Some information may legitimately require protection.

---

## 4. Open by Default, Restricted by Reason

For Aurex-developed technical work:

```text
CAN THIS BE OPEN?
       |
       +-- YES
       |    |
       |    v
       |  OPEN
       |
       +-- NO
            |
            v
     DOCUMENT WHY
```

Possible reasons for restriction include:

- cybersecurity risk;
- personal information;
- sensitive infrastructure information;
- contractual confidentiality;
- third-party licensing restrictions;
- legitimate commercial considerations;
- legal obligations;
- unreleased vulnerability information.

The burden should be on explaining the exception rather than assuming secrecy.

---

## 5. Open Source vs Merely Public Source Code

Aurex should use the term open source carefully.

Publicly visible source code is not necessarily open source.

For example:

```text
SOURCE CODE ON GITHUB
        +
NO LICENSE
        =
COPYRIGHT PROTECTED CODE

NOT automatically open source
```

A project should only be described as open source when its licensing actually grants appropriate rights to use, modify, and redistribute it.

Public visibility without an explicit license may allow inspection, but it does not provide the permissions normally associated with open-source software.

---

## 6. Asset Classification

Aurex should distinguish different intellectual assets.

```text
AUREX OUTPUTS
|
+-- Software
+-- Documentation
+-- Specifications
+-- Data
+-- Research
+-- AI models/artifacts
+-- Designs
+-- Media
+-- Trademarks
```

These should not automatically share one license.

Different asset types require different legal treatment.

---

## 7. Software Licensing Strategy

For Aurex-developed software intended to form reusable digital infrastructure, the preferred default candidate should be a permissive open-source license.

A strong default candidate is:

**Apache License 2.0**, commonly identified by the SPDX identifier **Apache-2.0**.

Why it fits infrastructure work:

- commercial use is permitted;
- modification is permitted;
- redistribution is permitted;
- private use is permitted;
- it contains an express patent license from contributors;
- it supports commercial and community adoption;
- it is widely understood in technology ecosystems.

However:

> Apache-2.0 is the preferred default candidate, not a blindly mandatory license for every repository.

Every repository still requires classification.

No actual repository-wide license is adopted merely because this framework identifies Apache-2.0 as a preferred candidate.

---

## 8. Copyleft and Project Strategy

Copyleft licenses such as the GNU General Public License (GPL), GNU Lesser General Public License (LGPL), GNU Affero General Public License (AGPL), and Mozilla Public License (MPL) can be excellent when the objective is to require derivative or network-used software to remain under compatible open terms.

But Aurex's strategic objectives may include:

- utility adoption;
- hardware-vendor integration;
- institutional collaboration;
- commercial ecosystem participation;
- reusable infrastructure;
- interoperability across public, private, and community systems.

A highly restrictive licensing posture could sometimes create adoption friction.

Therefore licensing should follow the strategic purpose of the project, not ideology.

---

## 9. License Decision Process

Before creating or publicly releasing a repository:

```text
WHAT ARE WE PUBLISHING?
        |
        v
WHO SHOULD USE IT?
        |
        v
WHAT RIGHTS SHOULD THEY HAVE?
        |
        v
WHAT OBLIGATIONS SHOULD APPLY?
        |
        v
WHAT DEPENDENCIES EXIST?
        |
        v
LICENSE COMPATIBILITY
        |
        v
SELECT LICENSE
        |
        v
DOCUMENT DECISION
```

Material exceptions from the default candidate should be documented.

Where the legal effect is uncertain, Aurex should seek qualified legal review before release.

---

## 10. Recommended License Classes

Aurex should eventually maintain an approved-license register.

Initial categories may include:

### Preferred

Common licenses suitable for Aurex's intended infrastructure use.

Potential examples:

- Apache-2.0;
- MIT License;
- BSD 2-Clause License;
- BSD 3-Clause License.

### Conditional

Licenses requiring technical or legal review because their obligations may materially affect distribution, integration, network use, or derivative works.

Potential examples:

- GPL family licenses;
- LGPL family licenses;
- AGPL family licenses;
- MPL family licenses;
- project-specific open-source licenses.

### Restricted

Licenses incompatible with intended distribution, institutional obligations, procurement requirements, or deployment context.

### Prohibited

Unlicensed, unlawfully copied, provenance-uncertain, confidential, or otherwise unacceptable material.

The exact approved list should be maintained rather than assumed indefinitely.

---

## 11. Documentation Licensing

Documentation is not software.

For public Aurex documentation, a Creative Commons license may be more appropriate than a software license.

A potential default candidate is:

**Creative Commons Attribution 4.0 International**, commonly identified as **CC BY 4.0**.

This generally allows reuse and adaptation with attribution.

But institutional governance documents require thought.

Aurex may want people to read and reference its Charter and frameworks without allowing altered documents to be represented as official Aurex policy.

That concern is partly handled through trademark, authenticity, repository governance, and publication controls rather than simply choosing a restrictive copyright license.

This framework does not automatically license existing documentation under CC BY 4.0.

---

## 12. Research Publications

Research outputs may use licenses appropriate to:

- papers;
- figures;
- datasets;
- code;
- supplementary materials;
- models;
- notebooks.

The paper and its accompanying code do not necessarily require the same license.

Publication agreements, funder requirements, journal policies, and collaborator agreements must also be respected.

---

## 13. Data Licensing

Data requires its own governance.

Before releasing a dataset, Aurex must ask:

```text
DO WE OWN IT?

DO WE HAVE THE RIGHT TO RELEASE IT?

DOES IT CONTAIN PERSONAL DATA?

DOES IT REVEAL SENSITIVE INFRASTRUCTURE?

DO CONTRACTS RESTRICT IT?

COULD RELEASE CREATE SECURITY RISK?
```

Only after those questions should an open-data license be considered.

Potential data-license choices should be evaluated against ownership, privacy, public-interest, security, and contractual constraints.

---

## 14. Operational Energy Data

Aurex should not assume energy telemetry is public.

Examples include:

- facility load;
- generator operation;
- grid measurements;
- equipment status;
- customer consumption;
- asset location;
- network topology;
- control settings;
- outage and event logs.

Some of this information may create:

- privacy risk;
- commercial risk;
- infrastructure-security risk;
- operational risk.

Therefore:

> Open-source software does not imply open operational data.

This distinction should be permanent.

---

## 15. Specifications and Standards

Aurex may eventually publish:

- APIs;
- data models;
- protocol profiles;
- reference architectures;
- conformance specifications;
- interoperability profiles.

Where appropriate, specifications should be openly accessible so multiple implementers can build compatible systems.

This directly supports interoperability.

Specifications may require different copyright and patent policies from ordinary documentation, especially if they are intended to become implementable standards.

---

## 16. Third-Party Dependencies

Every dependency introduces:

```text
CODE
+
LICENSE
+
SECURITY
+
MAINTENANCE
+
SUPPLY-CHAIN RISK
```

Therefore dependency selection is a governance decision.

Before introducing a material dependency, consider:

- license;
- project health;
- security history;
- maintenance status;
- community;
- release cadence;
- alternatives;
- compatibility;
- provenance.

---

## 17. Dependency Inventory and SBOM

Aurex projects should progressively maintain machine-readable dependency information.

Longer term this should include a:

**Software Bill of Materials (SBOM)**.

Conceptually:

```text
AUREX APPLICATION
|
+-- Component A
|   +-- License
+-- Component B
|   +-- License
+-- Library C
|   +-- License
+-- Library D
    +-- License
```

This supports both licensing and cybersecurity.

---

## 18. License Compatibility

A dependency being open source does not automatically mean Aurex can combine it with any other component however it wants.

Licenses can impose different obligations.

Therefore:

> License compatibility must be evaluated before distribution, not after the product has already been built.

This is especially important when mixing copyleft and permissively licensed components.

---

## 19. Upstream-First Principle

Aurex should adopt:

> Upstream before permanent fork.

If Aurex improves an upstream open-source project:

```text
DISCOVER NEED
      |
      v
IMPLEMENT IMPROVEMENT
      |
      v
CAN IT BENEFIT UPSTREAM?
      |
      v
CONTRIBUTE UPSTREAM WHERE APPROPRIATE
```

Permanent private forks create:

- maintenance burden;
- divergence;
- upgrade difficulty;
- duplicated engineering.

Forks may still be justified, but the reason should be documented.

---

## 20. Relationship with OpenEMS and Other Upstream Projects

Aurex may build upon, integrate with, test, extend, or contribute to established open-source projects such as OpenEMS and other upstream energy, grid, IoT, data, and infrastructure projects.

The rule is:

> Aurex must respect the upstream project's license, governance, attribution, trademarks, contribution rules, and community norms.

Using open-source software does not make Aurex the owner of that upstream technology.

Aurex should clearly distinguish:

```text
UPSTREAM PROJECT
        +
AUREX CONTRIBUTION
        +
AUREX INTEGRATION
        =
COMBINED SOLUTION
```

without misrepresenting authorship, control, endorsement, or ownership.

---

## 21. Fork Governance

When Aurex forks a project, document:

- upstream repository;
- upstream license;
- reason for fork;
- differences;
- synchronization strategy;
- responsible maintainer;
- intended duration;
- upstream contribution strategy.

A fork should not silently become disconnected infrastructure.

---

## 22. Contributor Intellectual Property

Aurex needs certainty that contributors have the right to contribute what they submit.

The basic rule is:

> Contributors may only submit work they are legally entitled to contribute under the project's license.

Contributors must not copy:

- employer-owned code without permission;
- proprietary source;
- incompatible licensed material;
- copyrighted material from unrelated repositories;
- confidential information;
- source code or data whose provenance they cannot explain.

---

## 23. DCO vs CLA

Aurex will eventually need an inbound contribution mechanism.

Two common models are:

### Developer Certificate of Origin

A Developer Certificate of Origin (DCO) model asks contributors to certify that they have the right to submit the contribution.

It is often implemented using a commit sign-off line such as:

```text
Signed-off-by:
```

### Contributor License Agreement

A Contributor License Agreement (CLA) asks contributors to grant specified rights through a separate agreement.

For a collaborative infrastructure institution, DCO is an attractive initial model because it is lightweight and familiar in open-source communities.

But the final decision should consider Aurex's future legal entity, IP strategy, repository risk, contributor base, and enforcement readiness.

Therefore:

> Preferred initial direction: DCO, subject to legal readiness review.

---

## 24. Inbound = Outbound Principle

Where appropriate:

> Contributions should generally be accepted under terms compatible with the license under which Aurex distributes the project.

This keeps contribution rights understandable.

Exceptions require explicit review.

---

## 25. Copyright Ownership

Aurex must distinguish:

```text
COPYRIGHT OWNERSHIP
        !=
OPEN-SOURCE LICENSE
```

Aurex can own copyright and still release software openly.

Likewise, multiple contributors can retain copyright while licensing contributions under common project terms.

The exact ownership model should later align with Aurex's legal entity, contributor framework, employment or contractor agreements, and project strategy.

---

## 26. Copyright Headers

Do not blindly insert copyright headers into every source file.

Repository-level licensing and provenance may be more maintainable.

Where headers are required, use a consistent approved format.

Header policy should be documented per repository or per asset class.

---

## 27. NOTICE Files

Some licenses, including Apache-2.0 projects, may involve preservation of notices in certain circumstances.

Aurex should maintain appropriate:

- `LICENSE`;
- `NOTICE`;
- attribution information;
- third-party notices;

where required.

The presence of a `NOTICE` file should reflect actual notice obligations, not template copying.

---

## 28. Repository Licensing Requirements

Every public Aurex code repository should eventually answer:

```text
WHO OWNS THIS?

WHAT LICENSE APPLIES?

HOW CAN I CONTRIBUTE?

HOW DO I REPORT SECURITY ISSUES?

WHO MAINTAINS IT?

WHAT IS ITS MATURITY?
```

Typical repository-level files may include:

```text
README.md
LICENSE
NOTICE
CONTRIBUTING.md
CODE_OF_CONDUCT.md
SECURITY.md
CHANGELOG.md
```

Not every repository needs every file, but the questions must be answered somewhere authoritative.

This framework does not create those files automatically.

---

## 29. Repository Maturity Labels

Aurex should prevent GitHub visibility from being mistaken for production readiness.

Repositories should identify maturity.

Potential lifecycle:

```text
EXPERIMENTAL
      |
      v
RESEARCH
      |
      v
PROTOTYPE
      |
      v
PILOT
      |
      v
SUPPORTED
      |
      v
MAINTENANCE
      |
      v
ARCHIVED
```

This directly implements Aurex's Engineering Integrity principle.

---

## 30. Proprietary Components

Aurex may sometimes need proprietary technology.

Examples could include:

- vendor SDKs;
- licensed datasets;
- specialized optimization software;
- hardware drivers;
- commercial cloud services;
- proprietary test equipment interfaces.

The principle is:

> Proprietary components may be used when justified, but their presence, dependency implications, and interoperability consequences must be understood.

Aurex is open-first, not blindly anti-proprietary.

---

## 31. Vendor Lock-In Review

Before adopting a strategic proprietary dependency, ask:

- Can it be replaced?
- Is data export possible?
- Is the interface documented?
- What happens if the vendor disappears?
- What happens if pricing changes?
- Can another implementation provide the same function?
- Does adoption weaken interoperability or institutional independence?

This implements:

> Open standards over unnecessary proprietary dependence.

---

## 32. Trademark Governance

Open-source licensing does not automatically grant trademark rights.

Aurex should eventually protect names and marks such as:

**Aurex Digital Solutions**

and potentially programme identities.

A fork of Aurex software may have software rights without necessarily having the right to impersonate the institution.

This protects authenticity.

---

## 33. Branding and Open Source

A useful distinction:

```text
CODE
can be open

BRAND
can remain controlled
```

This allows reuse while protecting users from misleading claims of official Aurex endorsement, origin, certification, or institutional approval.

---

## 34. AI-Generated Code

AI-generated code introduces provenance questions.

Contributors using AI tools remain responsible for ensuring submissions:

- are technically reviewed;
- do not knowingly reproduce incompatible code;
- do not expose confidential information;
- comply with project licensing;
- meet security standards;
- can be explained, tested, and maintained.

Aurex should not treat AI output as provenance-free.

---

## 35. AI Models

AI models require separate classification because licenses and terms can govern:

- model weights;
- code;
- datasets;
- outputs;
- usage restrictions;
- deployment restrictions;
- attribution or sharing obligations.

A model marketed as "open" may not satisfy normal open-source software definitions.

Therefore every model requires license and risk review before incorporation into critical Aurex systems.

---

## 36. Security vs Openness

Open development does not require immediate disclosure of exploitable vulnerabilities.

Security issues should follow responsible disclosure.

```text
VULNERABILITY DISCOVERED
        |
        v
PRIVATE SECURITY CHANNEL
        |
        v
ASSESS
        |
        v
FIX
        |
        v
COORDINATE RELEASE
        |
        v
DISCLOSE APPROPRIATELY
```

Task 11 will formalize this through the Security & Responsible Technology Policy.

---

## 37. Sensitive Infrastructure Repositories

Some technical information may require controlled access.

Examples:

- production credentials;
- network topology;
- private keys;
- detailed security configurations;
- vulnerability information;
- sensitive facility diagrams;
- operational control logic that could create infrastructure risk if misused.

These should never be made public merely to satisfy an open-source philosophy.

---

## 38. Secrets Policy

Absolute baseline:

> Credentials, tokens, passwords, certificates, and private keys must not be committed to public repositories.

If accidentally exposed, assume compromise and rotate or revoke appropriately.

Deleting the latest commit alone may not remove the secret from repository history.

Future repository templates should include secret-scanning and security-reporting guidance.

---

## 39. Contribution Back to the Ecosystem

Aurex should measure open-source success not only by what it publishes but also by what it contributes upstream.

Potential contributions:

- code;
- device integrations;
- African grid requirements;
- documentation;
- bug reports;
- testing;
- interoperability specifications;
- translations;
- research;
- implementation experience.

This makes Aurex a participant in the ecosystem rather than merely a consumer.

---

## 40. Open-Source Sustainability

Publishing code is easy.

Maintaining it is infrastructure stewardship.

Before declaring a project supported, Aurex should consider:

```text
MAINTAINER
      +
DOCUMENTATION
      +
RELEASE PROCESS
      +
SECURITY RESPONSE
      +
TESTING
      +
COMMUNITY
      +
LONG-TERM OWNERSHIP
```

An abandoned repository is not successful infrastructure.

---

## 41. Archival Policy

Projects that are no longer maintained should be clearly marked.

Archival should state:

- maintenance status;
- last supported version;
- known risks where appropriate;
- migration path if available;
- replacement project if applicable.

Never leave users believing abandoned infrastructure is actively supported.

---

## 42. Licensing Decision Authority

Under the current governance model:

### Routine use of approved licenses

May eventually be delegated to repository or project maintainers.

### New or unusual licenses

Require institutional review.

### License conflicts

Require escalation.

### Material proprietary exceptions

Require appropriate technical and institutional approval.

### Core institutional IP licensing changes

Should be treated as strategic or reserved decisions depending on significance.

At the founding stage, final approval authority must remain consistent with the Governance Framework and Organization Structure & Decision Rights document.

---

## 43. License Register

Aurex should eventually maintain:

```text
Project
Asset type
Copyright holder
License
Dependencies
License exceptions
Approval
Date
Maintainer
```

This becomes part of institutional IP governance.

---

## 44. Open-Source Compliance Gate

Before public release:

```text
SOURCE REVIEW
      |
      v
DEPENDENCY INVENTORY
      |
      v
LICENSE REVIEW
      |
      v
ATTRIBUTION
      |
      v
SECRETS CHECK
      |
      v
SECURITY CHECK
      |
      v
DOCUMENTATION
      |
      v
RELEASE
```

This can later become automated through CI/CD.

---

## 45. Licensing Is Not Legal Incorporation

This distinction is important at Aurex's current stage.

This framework can define preferred licensing policy.

But ownership and enforcement ultimately depend on the legal persons or entities holding rights.

Therefore:

> Final institutional IP ownership arrangements must be reconciled during Task 20 - Legal & Institutional Readiness.

Until then, Aurex should avoid making claims that the licensing framework has already settled legal incorporation, ownership assignment, employment IP, contractor IP, or contributor rights questions.

---

## 46. Recommended Initial Aurex Policy

The recommended initial policy direction is:

1. Treat open source as a core infrastructure strategy, not a slogan.
2. Use Apache-2.0 as the preferred default candidate for Aurex-developed infrastructure software unless project strategy, dependencies, legal review, or ecosystem requirements justify another license.
3. Use CC BY 4.0 as a potential default candidate for public documentation where appropriate, while protecting official institutional identity and authenticity.
4. Do not treat operational energy data as open merely because related software is open.
5. Require each public repository to state license, maturity, maintainership, contribution path, and security-reporting path.
6. Prefer DCO as the initial contribution mechanism, subject to legal readiness review.
7. Maintain dependency inventory and license-compatibility review as release gates.
8. Contribute upstream where appropriate rather than creating permanent divergence.
9. Keep trademarks and official branding controlled even where code is open.
10. Escalate unresolved ownership, incorporation, contributor, and enforcement questions to Task 20.

This is a policy direction, not automatic relicensing.

---

## 47. Relationship to Existing Aurex Principles

This framework implements existing Aurex principles:

### Openness

Open where responsible, not public by accident.

### Interoperability

Prefer standards, interfaces, and reusable components that prevent unnecessary fragmentation.

### Engineering Integrity

Label maturity honestly and avoid implying production readiness where evidence is absent.

### Authority Must Be Explicit

Do not assume legal rights, contributor rights, operational authority, or trademark permissions.

### Cybersecurity Is Infrastructure

Keep secrets, vulnerabilities, and sensitive infrastructure information protected.

### Documentation Is Infrastructure

Make license decisions, dependency obligations, notices, and exceptions traceable.

---

## 48. How Task 10 Continues This Framework

Task 10 is now:

**Contributing Framework**

It defines:

- who may contribute;
- how contributions are proposed, reviewed, accepted, rejected, and maintained;
- DCO or CLA implementation details;
- contribution quality expectations;
- technical review process;
- documentation review process;
- maintainer responsibilities;
- decision escalation;
- security reporting;
- code-of-conduct enforcement;
- contributor recognition;
- repository governance;
- contribution pathways for researchers, engineers, institutions, utilities, vendors, and community participants.

Task 10 converts this licensing direction into a practical participation model.

---

## 49. Institutional Build Status

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
11 Security & Responsible Technology Policy NEXT
12 Ethics, Sovereignty & Public-Interest Framework PLANNED
13 Risk Management Framework               PLANNED
14 Operating Model                         PLANNED
15 Organization Roadmap                    PLANNED
16 Funding & Financial Framework           PLANNED
17 Partnership & Stakeholder Framework     PLANNED
18 Research & Innovation Framework         PLANNED
19 Programme Governance Framework          PLANNED
20 Legal & Institutional Readiness         PLANNED
21 Organization Documentation Baseline v1.0 PLANNED
```

Task 9 is complete as a Draft v1.0 foundational artifact.

Previous document: [Organization Structure & Decision Rights](./ORGANIZATION-STRUCTURE-AND-DECISION-RIGHTS.md)

Home: [Documentation Index](./README.md)

Next document: [Contributing Framework](./CONTRIBUTING-FRAMEWORK.md)
