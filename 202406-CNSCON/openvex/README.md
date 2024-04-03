# We’re VEXing the Cloud Native Landscape. Bring Your Code!

## Description

Notorious events such as the xz backdoor often lead to a surge in user inquiries, with repetitive questions becoming a common occurrence. What's more, when a vulnerability doesn't affect your software, scanners may generate false positives. It's a recurring challenge for any application security team.

Enter VEX, the Vulnerability Exploitability eXchange, a complementary format to SBOM allowing developers to communicate the impact of vulnerabilities on their software. VEX also provides insights into the triage status and facilitates automation to address false positives in security scanners.

In this presentation, we'll delve into how the Kubernetes ReleEng Team, in collaboration with TAG Security, bootstrapped OpenVEX feeds throughout the CNCF ecosystem.

Using these initiatives as a roadmap, we'll show how to effortlessly build a new feed and showcase the automation of VEX data, and illustrate through hands-on demos, how consumers and security tools can leverage it effectively.

## Talk Outline

- About Me
- OpenVEX: The Lighter OpenVEX
  - What is VEX?
    - The problems that VEX solves
      - Easier Triaging
      - Sewcure Releases
      - Automating Communications 
      - Controlling Security Tools
    - VEX Documents and Statements
    - VEX Statuses
  - The Four VEXes
  - Why OpenVEX
  - What is OpenVEX
    - Spec
    - Tools
    - Libraries
- VEXing Cloud Native
  - CNCF Security Slam
  - A look into a VEXed project: Ingress Nginx (or gateway api)
- Starting your feed
  - vexctl overview
  - Gerneating a Document
  - Adding Statements
- Pairing SBOMs and OpenVEX Data 
- Attesting and Attaching Documents
  - Signing
  - Uploading to OCI Registries
  - Retieving
- Discovery
- A VEX Dashboard
- Consumption in Scanners

