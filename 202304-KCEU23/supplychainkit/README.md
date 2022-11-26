# Secure Your Project With the SIG Release Supply Chain Kit

### Talk Summary

An introduction to the supply chain security tools 
created and maintained by SIG Release and where they
fit in your project's release process.

### Goals:

- Help people understand basic Supply Chain Concepts  
- Spread the word about the work K8s release engineering is doing
- Show the tools we have produced
- Showcase how we are helping other projects

### Non Goals:

- Explain how kubernetesis released
- General purpose sigstore intro 

## Talk Structure

- Intro (5 min)
  - About me
  - About Kubernetes SIG Release
- The challenges we face when releasing Kubernetes (5 min)
  - Custom tooling
  - Community driven release process
  - State of the art (or how there are no tools!)
- The SIG Release Toolkit (10 min)
  - Quick Intro
  - Software Bill of Materials
    - What is SBOM?
    - The Tool: bom
    - Real Workd example: The Istio SBOM!
  - Signed SLSA provenance attestations
    - What is Provenance?
    - The Tool: tejolote
    - Real World Example: Vitess Provenance!
  - Signed container images and artifacts
    - Why sign?
    - The Tools: cosign + k8s signer
    - Real World Example: Cilium signed images!
  - Secure GitHub release pages
    - Why is it important?
    - The Tool: publish release
    - Real World Example: The Kubernetes image promoter releases
  - Others! (release notes)
    - Real World Example: Knative release notes!
- Demo Time! (7 min)
  - The SIG Release Actions Repository!
  - How to integrate
- The SIG Release Guide (3 min) 
- Conclusion (5 min)
    - Takeaways
    - Joing k8s release engineering!
    - Thank you
    - Q&A
