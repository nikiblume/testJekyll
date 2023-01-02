---
title: "ZoKratesPlus"
date: 2019-04-18T15:34:30-04:00
permalink: /
layout: splash
#header:
#  image: /assets/images/zokrates-logo-header.png
header:
  #overlay_image: /assets/images/zokrates-logo-header-landscape-smaller.png
  overlay_image: /assets/images/digital-background-white.png
  #overlay_image: /assets/images/technology-7111756.jpg
  overlay_filter: 0.2 # same as adding an opacity of 0.5 to a black background
  #caption: "Photo credit: [**Unsplash**](https://unsplash.com)"
  actions:
    - label: "More Info"
      url: "/#zokrates"
excerpt: "Zero-knowledge-based Business Solutions"        
categories:
  - blog
tags:
  - Jekyll
  - update
toc: true
toc_label: "Contents"
toc_icon: "cog"
toc_sticky: true 
#classes: wide
comments: true

feature_row:
  - image_path: /assets/images/gears.jpg
    alt: "placeholder image 1"
    title: "Application"
    excerpt: "Overview of zero knowledge based business solutions."
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--inverse"
  - image_path: /assets/images/read.jpg
    alt: "placeholder image 2"
    title: "Education"
    excerpt: "Learn how to use ZoKrates for your business."
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--inverse"
  - image_path: /assets/images/hands.jpg
    title: "Community"
    excerpt: "Learn about our fastly growing community."
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--inverse"


---
{% include feature_row %}


Zero knowledge proofs (ZKPs) have been receiving increased interest in the blockchain community and beyond, mostly for reasons of both improving scalability and enhancing privacy in decentralized applications. Higher-level languages and tooling like ZoKrates make creating verifiable off-chain programs and linking them to smart contracts possible even for the non-crypto-expert, hiding some of the complexities associated with programming ZKPs. First-of-a-kind applications, for example, accounting and netting in peer-to-peer energy grids, demonstrate the enormous power and benefits when combining blockchains and ZKPs. Still, many more applications are  to be developed and learned from. 

ZoKratesPlus is a publicly funded project for validating zero knowledge proofs and supporting technologies like ZoKrates in real-world business processes. Objectives include the identification of key application contexts, nurturing the ZKP application developer community, and advancing ZoKrates and related zero knowledge based technologies towards true innovation and value creation.

We call to focus attention on real-world, practical applications of ZKPs and invite everyone interested to participate in this new validation project. ZoKratesPlus will develop general guidelines and best practices for using ZKPs and "disseminate knowledge about transacting with zero knowledge".


# ZoKrates
ZoKrates is a developer-friendly language and tool suite that allows you to easily extend your DApp through privacy-preserving and [scalable off-chain computations](https://www.ise.tu-berlin.de/fileadmin/fg308/publications/2018/2018_eberhardt_ZoKrates.pdf) without compromising key on-chainn qualities. Thereby, you can reduce transaction costs and balance between privacy and transparency. 

![ZoKrates in KYC](https://raw.githubusercontent.com/ZoKratesPlus/zokratesplus.github.io/master/zokrates.png)

A [ZoKrates](https://github.com/Zokrates/ZoKrates) program written in a [domain specific language](https://zokrates.github.io/language/variables.html) is compiled into an abstraction (flattened code), which is compatible with existing zkSNARK proof systems. Proving and verification keys are generated in the setup phase. Subsequently, a prover runs the program and applies the proving key to generate a proof that is later verified with the verification key.


## Application Contexts

Call for participation: a curated overview of zero knowledge based business solutions.

|                                      | Prototype | Pilot  | In Production |
|:-------------------------------------|:----------|:-------|:-----------|
| **Book Keeping<br/> (Transaction Aggregation)**          |           |        | [Polygon Nightfall](https://zokratesplus.github.io/transaction_aggregation.html)    |
| **Know Your Customer<br/> (Credential Verification)**    | [zkMe](https://zokratesplus.github.io/anonymous_credentials.html)      |        |            |
| **Energy Grids<br/> (Accounting / Netting)**       |           | [BloGPV](https://zokratesplus.github.io/accounting_energy_grids.html) |            |
| **ERP (State Management)**      |           |        | [Baseline](https://zokratesplus.github.io/baseline_protocol.html)   |
| **Shared IP<br/> (Federated Learning)**               | [zkFL](https://zokratesplus.github.io/federated_learning.html)         |        |            |


## Contact
You work with ZKPs/ZoKrates and your project is missing? You are interested in or plan to use ZKPs/ZoKrates? Please [reach out](./contact.html) and share your practical zero knowledge experience or needs.


## Resources

A growing list of zero knowledge based business solutions:

*   [Nightfall](https://github.com/EYBlockchain/nightfall_3) for transaction aggregation. 
*   [Polygon](https://polygon.technology/solutions/polygon-nightfall/) which uses nightfall.
*   [Credential verification](https://github.com/JonathanHeiss/ZoKrates-Credential-Verification) with ZoKrates.
*   [Paper](https://arxiv.org/pdf/2209.09584.pdf) on credential verification.
*   [W3C recommendations](https://www.w3.org/TR/vc-data-model/) for verifiable credentials.
*   [Paper on book keeping](https://www.ise.tu-berlin.de/fileadmin/fg308/publications/2020/preprint-ICBC-Eberhard.pdf) in energy grids.
*   [Project on book keeping](https://github.com/JacobEberhardt/decentralized-energy-trading) in energy grids.
*   [Federated learning](https://arxiv.org/pdf/2206.11641.pdf) paper.
*   Federated learning [proof of concept](https://github.com/NikolasHaimerl/Advancing-Blockchain-Based-Federated-Learning-Through-Verifiable-Off-Chain-Computations).
*   [Baseline protocol](https://docs.baseline-protocol.org) for state management.


