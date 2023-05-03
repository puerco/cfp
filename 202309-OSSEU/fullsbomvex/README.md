# Enabling VEX and Full SBOM Coverage with Wolfi based Containers

## Abstract

When assessing a container image, a software bill of materials (SBOM) can help identify vulnerable dependencies, unexpected or modified files, expired data, or licensing issues. Linking the SBOM data with VEX information (Vulnerability Exploitability eXchange) decreases the burden of vulnerability management by reducing the noise produced by security scanners.

The powerful promise of the SBOM+VEX combo can only be achieved when the SBOM is comprehensive and properly structured while, on the other hand, making sure VEX information is flowing from the appropriate sources.

In this talk, we'll understand how images based on Wolfi (an open source container optimized Linux distro) achieve total SBOM coverage by starting to account for components from each package source code. We will analyze the SBOM, how it gets built, and learn how to verify an image against it. We'll also go into how the wolfi tooling can generate OpenVEX documents automatically when a new CVE is disclosed which can be used by scanners to cancel false positives.

We'll close with a live demo demonstrating how to build a cloud native app in an image that ships with a complete SBOM and VEX data.

## Outline

- Intro
- Quick Overviews of Key Technologies
  - What is an SBOM, a Software Bill of Materials
  - What is VEX, the Vulnerability Exploitability Exchange
  - What is Wolfi, the container Linux (un)distro
- Part 1: A Full Coverage SBOM
  - Deep dive into a Wolfi based image SBOM
    - Full coverage of packages and system files
    - Analizing its structure
  - How Wolfi enables great SBOMs
    - SBOM Birth: At compile time
    - SBOM Distribution: Packaged with software
    - Composing a Wolfi Image
    - SBOMs Assemble! Remixing package SBOMs into a SuperSBOM
    - Verifying an image against its SBOM
      - What the SBOM can tell you
      - What it can't
      - Patterns you should avoid
    - Running the SBOM thorugh a Scanner
- Part 2: VEX in Action! Or better yet: inaction.
  - Understanding a VEX Statement
  - A tour through Wolfi security advisories and their process
    -  How we patch
    - What we publish
  - Generating VEX from Wolfi data
    - Wolfi CLI tools available to developers and platform teams
    - A sample Wolfi OpenVEX document
  - Running an OpenVEX document through a scanner
  - Trusting VEX
- Demo 
  - Power up your app with a Wolfi image!
    - Packaging your app 
    - Building a Wolfi image including your (packaged) application
  - Verifying its SBOM 
  - Generating VEX documents for your image
  - Running the SBOM and VEX through a scanner
- Thanks!
- Q&A
