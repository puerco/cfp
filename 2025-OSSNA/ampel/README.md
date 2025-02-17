# Builds You (and Others) Can Trust: Meet the AMPEL Policy Engine

## Description

For years, the supply chain security community has been working hard to generate security metadata about repositories, software builds, vulnerability reports, releases, and SBOMs that describe how software is composed.

Transparent build processes with visible supply chains are great, but all that information has been remarkably difficult to use. Until now!

Meet AMPEL, the Amazing Multi-Purpose Policy Engine. Ampel is the missing piece in the supply chain ecosystem: an open source policy engine that natively understands in-toto attestations, can verify keyless Sigstore signatures and understands any attestation predicate type. 

Ampel is embeddable and can look into SBOMs and warn about bad dependencies, understand security scans and gate builds when vulnerabilities are present, or stop artifacts from publishing when they don't meet any security framework. 

Ampel is slowly building an ecosystem: Starting with the bnd attester, the Ampel universe has tools that can work across the SLDC to secure CI/CD systems.

In this talk, we'll explore how Ampel can ensure compliance at every step through verifiable evidence to obtain a hardened SLDC, all with practical examples.

## Talk Outline

- Intro / About me
- The visible supply chain
  - What to look for
  - Generating evidence
  - Trusting the data
- Security Frameworks
  - 101
    - Controls, their definition and compliance
  - The OSPS Security Baseline
- Meet Ampel
  - Informing control compliance through attestations
  - How policies are built
  - Verifying Evidence
  - Checking identities through Sigstore signatures
- Embedding ampel
  - Use cases
  - At the repository level
  - Gating builds
  - Verifying artifacts before release
- Demo
- The Ampel Universe
  - bnd: the Swiss army knife of attestations
  - Other integrations
  - Embedding Ampel
- Call for contributors
- Thanks!
- Questions?
