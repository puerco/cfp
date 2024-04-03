
## Teach Your SBOM New Tricks With Bomshell

## Description: 

One of the widest gaps hindering Software Bill of Materials (SBOM) adoption is the diverse structure and content in the documents exchanged today.  

SBOM ingestion is tough: Is your SBOM in SPDX or CycloneDX? Which version? Is it encoded in JSON or tag-value? Do you have a single document or many? Is that SBOM complete, or do you need to enrich it? Is it flat or a full dependency tree?

It seems that every supplier, every tool, and every ecosystem produces a different document which, in turn, isn't compatible with your SBOM systems.
 
Meet bomshell! 

bomshell, a project originally funded by DHS, is a scripting language for SBOM based on CEL. It lets you create programs to work with their contents, regardless of format. bomshell can query SBOMs for data and extract the parts you need. It can combine documents and reshape them into new ones that look exactly the way you need them. Again in any format.

This talk will be rich in demos showing all of bomshell capabilities.

### Goals:

- Help attendees with SBOM consumption by leveraging bomshell scripts
- Rise SBOM awarness, especially about the fact thatthat formats are not important
- Maybe get more contributors for protobom!

### Non-goals:

- SBOM generation
- Introduction to SBOM

## Talk Outline

- About Me
- The current SBOM landscape
  - Different formats
  - An exploration of varying SBOM structures
  - A look at tool specialization
- The solution? Mix and reshape SBOM data
- Enter bomshell
  - What is it?
  - History
  - The bomshell Parts
    - CEL: Common Expression Language
    - protobom 
      - How protobom abstracts SBOMs
- Let’s save the day (useful examples)
  - Extract files from SBOM
  - Extract packages from SBOM
  - Use Identifiers: Find all container images in the Kuerbetnes SBOM. 
    - Find all rpm packages in a container images
  - Extract license data
  - Combine two SBOMs
    - Explore the resulting document
- Download Links
- Questions?
- Thank you
