---
layout: single
title: "Network Science Approaches for Public Policy"
permalink: /projects/network-science/
author_profile: true
---

{% include base_path %}

Understanding how diseases spread through social networks and how to optimally deploy limited intervention resources is crucial for effective public health policy. The COVID-19 pandemic highlighted the need for sophisticated models that can capture both the complex patterns of human contact and the strategic allocation of vaccines and other countermeasures. My work in this area at RAND focused on developing advanced methodological tools for network analysis and using realistic contact networks to evaluate different intervention strategies.

## Deep Generative Modeling for Network Science

<div style="text-align: center;">
    <img src="/images/NDSSL_Projection.png" alt="" style="width: 50%; height: auto; margin-bottom: 20px;">
</div>

Agent-based models increasingly require large-scale synthetic populations with rich demographic and behavioral information, but this data is often scattered across incompatible datasets. I led the development of novel deep learning approaches to address four key challenges in addressing this problem: synthetic network generation, network rescaling, data imputation, and network fusion.

The centerpiece was developing "Graph Generation by Iterated Link Prediction" - a new algorithm using graph neural networks to create synthetic social contact networks. Unlike traditional Exponential Random Graph Models, this method scales to networks with millions of nodes and edges.

We demonstrated these methods using the NDSSL dataset (1.6 million individuals in Portland, OR) and FluPaths dataset (rich behavioral data from RAND's American Life Panel). The approach successfully generated synthetic networks preserving key statistical properties while being orders of magnitude faster than traditional methods.

This work provides tools for creating ensemble simulations, testing model sensitivity, and developing representative datasets for different cities without privacy concerns. The methodology and code are available on [GitHub](https://github.com/RANDCorporation/dgmnet), with the full technical report avilable as a [RAND Working Report](https://www.rand.org/pubs/working_papers/WRA1671-1.html).

## Network-Based Vaccination Strategy Analysis

<div style="text-align: center;">
    <img src="/images/SEIR_vacc_fraction.png" alt="" style="width: 75%; height: auto; margin-bottom: 20px;">
</div>

Motivated by the imminent availability of COVID-19 vaccines, this project compared the efficacies of different network-based vaccination strategies using real-world contact data. It is a well-known result in network science that, depending on the network topology, targeted strategies, where more connected nodes are vaccinated first, can sometimes far outperform the strategy where nodes are vaccinated uniformly at random.

I investigated these hypotheses using a real-world person-to-person contact network derived from mobile device data obtained from the company Uber Media. Rather than attempting to faithfully simulate the spread of COVID-19 on this network, I instead simulated two rather simple contagion models (SIR and SEIR). Consequently, this work simulated a very idealized contagion model, albeit on a realistic network, providing insights into how network structure affects vaccination strategy effectiveness while maintaining computational tractability.

The research demonstrated that strategic vaccination of highly connected individuals can dramatically reduce disease spread compared to random vaccination, but also revealed important nuances about when and why these strategies work best. This has implications not just for COVID-19 but for future pandemic preparedness and the optimal deployment of limited medical countermeasures in networked populations.

This work resulted in both policy-oriented analysis for decision-makers and detailed technical implementation for the research community. The complete code and methodology are available on [GitHub](https://github.com/gshartnett/network_vaccination), with policy implications detailed in a [RAND Perspective](https://www.rand.org/pubs/perspectives/PEA1068-1.html), and the full technical results published in the [Journal of Complex Networks](https://doi.org/10.1093/comnet/cnab042).

---

[← Back to Projects](/projects/)