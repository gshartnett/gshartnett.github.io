---
layout: single
title: "COVID-19 Network Modeling"
permalink: /projects/covid-modeling/
author_profile: true
---

{% include base_path %}

Understanding how diseases spread through social networks and how to optimally deploy limited intervention resources is crucial for effective public health policy. The COVID-19 pandemic highlighted the need for sophisticated models that can capture both the complex patterns of human contact and the strategic allocation of vaccines and other countermeasures. My work in this area at RAND focused on using realistic contact networks to evaluate different vaccination strategies and understand how network structure affects disease transmission and control.

## Network-Based Vaccination Strategy Analysis

Motivated by the imminent availability of COVID-19 vaccines, this project compared the efficacies of different network-based vaccination strategies using real-world contact data. It is a well-known result in network science that, depending on the network topology, targeted strategies, where more connected nodes are vaccinated first, can sometimes far outperform the strategy where nodes are vaccinated uniformly at random.

I investigated these hypotheses using a real-world person-to-person contact network derived from mobile device data obtained from the company Uber Media. Rather than attempting to faithfully simulate the spread of COVID-19 on this network, I instead simulated two rather simple contagion models (SIR and SEIR). Consequently, this work simulated a very idealized contagion model, albeit on a realistic network, providing insights into how network structure affects vaccination strategy effectiveness while maintaining computational tractability.

The research demonstrated that strategic vaccination of highly connected individuals can dramatically reduce disease spread compared to random vaccination, but also revealed important nuances about when and why these strategies work best. This has implications not just for COVID-19 but for future pandemic preparedness and the optimal deployment of limited medical countermeasures in networked populations.

This work resulted in both policy-oriented analysis for decision-makers and detailed technical implementation for the research community. The complete code and methodology are available on [GitHub](https://github.com/gshartnett/network_vaccination), with policy implications detailed in a [RAND Perspective](https://www.rand.org/pubs/perspectives/PEA1068-1.html), and the full technical results published in the [Journal of Complex Networks](https://doi.org/10.1093/comnet/cnab042).

---

[← Back to Projects](/projects/)