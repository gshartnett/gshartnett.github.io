---
layout: single
title: "Nuclear Weapons Effects Modeling"
permalink: /projects/nuclear-weapons-effect/
author_profile: true
---

{% include base_path %}

Understanding the effects of nuclear weapons on civilian infrastructure is critical for national security planning and policy development. As our society becomes increasingly dependent on electronic systems and interconnected networks, the potential for widespread disruption from electromagnetic effects grows. My work in this area at RAND focused on developing better computational tools and models to help defense analysts and policymakers understand these vulnerabilities.

## High-Altitude Nuclear Explosions (HANE) Research

I contributed to research examining the effects of a high-altitude nuclear explosion (HANE) on satellite systems. The project required analyzing how modern satellite technology differs in vulnerability compared to the systems that existed during the original Cold War-era studies. This research highlighted the growing vulnerability of our space-based systems and the need for updated protective measures as satellites become increasingly critical for both civilian and military operations. The full report is available at [RAND RRA3028-3](https://www.rand.org/pubs/research_reports/RRA3028-3.html).

## Karzas-Latter-Seiler EMP Modeling Project

I developed a new numerical implementation of the classic Karzas-Latter-Seiler model for simulating electromagnetic pulse effects from high-altitude nuclear explosions. This foundational model, originally developed in the 1960s, describes how high-energy gamma rays from a nuclear weapon interact with the Earth's atmosphere at high altitude, creating what's known as the Compton effect on a massive scale. The resulting electromagnetic pulse can affect electronic systems over continental distances.

The project involved translating the original analytical model into modern Python code, implementing efficient algorithms for solving the complex electromagnetic field equations, and ensuring the results matched known benchmarks and historical data. One of the key challenges was interpreting and understanding decades-old scientific literature and notation, then making this complex physics accessible to policy analysts and non-specialists who need to use these tools for practical decision-making.

This work provides defense analysts and policymakers with updated computational tools for assessing EMP vulnerabilities and better understanding nuclear weapon effects. By making the code open-source and well-documented, it serves as a foundation for developing protective measures and mitigation strategies, while also providing educational resources for training the next generation of defense analysts.

The complete implementation is available as a RAND Working Paper ([WRA879-2](https://doi.org/10.7249/WRA879-2)), published on arXiv ([arXiv:2402.14864](https://arxiv.org/abs/2402.14864)), and the full code is available on [GitHub](https://github.com/gshartnett/karzas-latter-seiler/).

---

[← Back to Projects](/projects/)