# True Security: Unforgeable Baseline Compliance

## Description

A year ago, with input from projects across different foundations, we set on a mission to delineate a minimum set of security requirements that could realistically be implemented by open source projects. No matter their size.

Thus, the Open Source Project Security Baseline was born.

With the Baseline maturing rapidly, it's time to check and enforce its requirements! For the Baseline to provide true security, cryptographically secure evidence has to be produced by projects which can, in turn, be tied to commits and built software artifacts. 

Enter attestations!

By leveraging the In-Toto attestation framework and the Sigstore transparency log, this talk will show how to achieve unforgeable OSPS Baseline compliance through attested evidence that can securely be associated with repos, binaries, and container images.

It all sounds harder than it is. The talk will feature practical ways of achieving high compliance levels with only a handful of attestations from the OpenSSF family of tools, showing alternatives for each requirement.

The talk will conclude with an enforcement example, gating on build and deployment processes when repos and artifacts are not Baseline compliant.

## Outline

- Welcome (1 min)
    - About Me
- A quick overview of the baseline control areas (1 min)
- Dissecting an Attestation (2 min)
- Attesting requirements: (7 min)
    - Attesting to project documentation, legal and governance
        - Security Insights
        - Scorecard
        - Leverage that SBOM!
    - Attesting to repository security
        - SLSA Source Track, gittuf/gitsign
        - More scorecard!
        - ... plus some custom magic dust
    - Project End-of-Life / End-of-Supprt
        - OpenEoX and others
    - Attesting Vulnerabilities and Communicating Impact
        - Communicating Vulnerabilities
            - SPDX / CycloneDX
            - Intoto VULN predicate
            - OSV!
        - Impact: Enter VEX
            - Attesting and communicating impact with OpenVEX
    - Tracking dependencies and related projects
        - Using your SBOM (Yes, really!)
            - Protobom into the SBOM contents
    - Pack and ship:
        - Signing it all with sigstore
        - Packing all attestations

- Enforcing Baseline through the SDLC (7 min)
    - Gating Your Build Process
    - Checking compliance before shipping
    - Checking at runtime

- Conclusions / Thanks / Get involved  (1 min)


