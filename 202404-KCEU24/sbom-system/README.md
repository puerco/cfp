# Meet the new Kubernetes SBOM System!

Kubernetes was one of the first big open source projects to publish a Software Bill of Materials with the artifacts it releases every quarter. Since the first SPDX SBOM we published in 2020, a lot has changed and the Kubernetes Release Engineering team has kept adding improvements to our SBOM and the other Supply Chain Security tools that power our release process.

In mid-2023, SIG Release. together with SIG Security, planned a revamp of the Kubernetes security documents. And so, from the monolithic SBOM, the project now has a modern and agile SBOM system where data is split into leaner documents.

In this talk, Adolfo and Carlos will tour the new SBOM system. They’ll explain how all assets of a big complex software project can be accounted for and how our SBOMs connect to each other. You will also learn how to use the same tooling to model your project. 

Finally, we’ll learn about the distribution and security features SIG Release built into the SBOM system.

Join us, it’ll be SBOMtastic!

## Outline

- Part 1. Intro
    - Hello and Personal Intros
    - Quick Overviews of Key Technologies
        - What is an SBOM, a Software Bill of Materials
        - What a Kubernetes release looks like

    - The Previous Monolithic SBOM
        - Overview
        - How this work pioneered SBOM.
        - Limitations, how things changed since 2020

- Part 2. The new SBOM system!
  - Main goals
    - Modularity
    - Efficiency
    - Easy discoverability
    - but all linked together: An SBOM system

  - The documents
    - The Source SBOM
    - An SBOM per image
    - The "artifacts" SBOM.
    - Hey, what is that inside that RPM!
  - How we distribute SBOMs
    - sbom.k8s.io
    - registry.k8s.io
      - And look, they are signed!
    - github releases
    - System package repositories

- Part 3. Demos and Hands-On
    - Make the SBOM system work for you
    - Explore a kubernetes release
        - An inventory of dependencies
        - Licensing overview
    - How to pair the SBOMs with VEX
    - How to pair the SBOMs with provenance metadata

    - Learn how to generate your own
    - Use bom to SBOM!
    - Did you know that publish-release can SBOM?

- Thanks!
- Q&A

