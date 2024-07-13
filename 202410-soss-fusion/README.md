# Ace the Base: Meeting the Open Security Baseline with Minder

The OpenSSL Security Baseline proposes a framework for a common security posture across open source projects. 

## Description

The baseline requirements are designed to match the OpenSSF's project lifecycle: each level has been designed to provide increasing levels of protection with as little effort as possible. They range from secure repository configuration to the production of security metadata such as SBOMs and SLSA attestations.

These requirements may sound daunting but the path forward is bright! 

The OpenSSF community has been working hard to create tools, specifications, and libraries to help harden the global software supply chain. While we have built amazing tooling to automate compliance, orchestration can still be challenging. Understanding at scale which resources are falling short of the baseline expectations needs coordination and remediation. Luckily this is where Minder comes in!

Minder is an open source platform that monitors your repositories, builds, and artifacts to ensure they match a declared security posture. In contrast to other tools, it reconciles the state of your resources to match your desired state.  Join Puerco for a live demo of meeting baseline compliance!


## Benefits to the Ecosystem

Protecting open source is a daunting task, there is an enormous diversity in how each of the projects handles their software releases, manages their repositories protects their serving infrastructure, and so on. By establishing a common security framework, the open source community can share its experiences to harden its supply chain together. 

By pursuing the same goals projects can contribute not only to a common knowledge pool but also provide feedback and patches to the tools designed to automate the required checks.

Minder can help orchestrate all of these tools. Leveraging Kubernetes' powerful reconciliation model, Minder can observe resources and apply remediations to meet a desired state.

The project has created a specific security profile to meet the OpenSSF Secirotyu Baseline requirements. By applying the profile, open source projects will be able to automate the baseline requirements and ensure that any drift in compliance is automatically remediated.

With Minder, we plan to help projects achieve Baseline compliance quickly and easily as projects will not need to worry about most of the requirements.

## Talk outline

- Intro
  - About Me 
  - About Stacklok

- The OpenSSF Security Baseline
  - Motivation
  - Requirements
  - Pumping Life into the Ecosystem
  - OpenSSF Projects t Work!

- Remediate with Minder
  - Intro to Minder
    - Operating model
    - Custome Rules
  - The OpenSSF Security Baseline Profile
    - Included Rules and Remediations

- Demo Time

- Future Plans
  - Required Features

- Thank You
- Questions
  



