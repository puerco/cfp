# An Inner Look Into What SBOMs Really Tell Us

### Talk Structure

A journey into the innards of SBOM information. Illustrated with
visualizations from bom: The kubernetes sbom tool

### Goals:

* Helping folks understand what is inside an SBOM
* Educate about how SBOMs represent software
* Help attendees understand what a good quality SBOM needs

### Non Goals:

* How to generate an SBOM (implicit)
* Tool recomendations or advertising

## Talk Structure

Length: 35m

- Intro (5 m)
 - About me
 - About SPDX
 - About Kubernetes SIG Release
   - What we've done
   - bom: The Kubernetes SBOM tool
     - How to view SBOMs with bom
- What is an SBOM (Software Bill of Materials)? (5 m)
  - What a Bill of Materials Means
  - Some uses of SBOMs:
    - Integrity
    - Compelteness
    - Licensing
    - Dependencies (What everybody wants)
- How SBOMs represent Software (4 m)
  - Files
  - Packages and Nesting
  - Relationships
- An Ideal Case (1 m)
- Common Errors and Flaws (10 m)
  - Empty SBOMs
  - Not complete
    - No Licensing information
    - No Versions
    - No Security References 
  - SBOMs With No Structure
  - Wrong or No relationships
  - Some Self Criticism
    - The Kubernetes SBOM
    - From Work: How Chainguard is SBOMin'
- How We (in SPDX) are Remediating It (5 m)
  - Criticism of SPDX about no guidance
  - Reponse: Semantic Representations
- Conclusion (5 m)
    - Takeaways
    - Thank you
    - Q&A
