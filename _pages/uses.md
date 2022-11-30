---
permalink: /uses/
title: "Intended use"
author_profile: false
sidebar:
  title: "Menu"
  nav: side
---

Our overarching aim is to promote responsibility in criminal justice ML. The potential benefits of creating this repository include:

  1. **Development of new methods (e.g., fairness, explainability) grounded in real-world scenarios.**
  Compared to common benchmarks, the [variety of datasets on this website](/datasheets) can allow researchers to tackle challenging, domain-specific, and overall more realistic use-cases. Examples include predicting rare but critically important labels (e.g., [PIRUS]({% post_url 2022-08-19-pirus %})), spatial-temporal patterns (e.g., [CPII]({% post_url 2022-08-19-cpii %})), and finding counterfactuals (e.g., [JUSTFAIR]({% post_url 2022-08-19-justfair %})). The datasets may provide a hard but particularly useful challenge for algorithmic fairness, as they require carefully disentangling of disproportionality from bias and discrimination. Understanding and addressing such real-world challenges is critical for responsible work in the criminal justice domain, and is much needed in deployed applications.[^1][^2]

  2. **Investigation of the criminal justice system.** While some of the datasets have already been used by criminologists, ML methods have rarely been applied. For this line of research, we highly recommend engaging with the relevant literature and domain experts to ensure proper context and interpretation of results.

  3. **Development of new benchmarks inspired by real-world use-cases.**

Increasing visibility of the surveyed datasets can also lead to _intentional_ and _unintentional_ misuse.
We condemn any deliberate misuse such as training harmful algorithms on the datasets.
For unintentional misuse,[^3] highlights irresponsible use of recidivism data, and the harms caused by ignoring context.
One may wonder if it would be better to simply not draw attention to the datasets.
We disagree as informed responsible engagement with the data can lead to significant societal benefits, like uncovering the bias propagated by "innocuous" technical systems.[^2][^4] We believe that transparency and the public nature of the surveyed datasets will promote more open rigorous debate about the limitations, and appropriate use of ML in criminal justice, thus counteracting misuse.

[^1]: Miri Zilka, Holli Sargeant, Adrian Weller. Transparency, governance, and regulation of algorithmic tools deployed in the criminal justice system: A UK case study. AIES 2022.
[^2]: Aaron Sankin, Dhruv Mehrota, Surya Mattu, and Annie Gilbertson. [Crime prediction software promised to be free of biases. New data shows it perpetuates them](https://themarkup.org/prediction-bias/2021/12/02/crime-prediction-software-promised-to-be-free-of-biases-new-data-shows-it-perpetuates-them).
[^3]: Michelle Bao, Angela Zhou, Samantha Zottola, Brian Brubach, Sarah Desmarais, Aaron Horowitz, Kristian Lum, and Suresh Venkatasubramanian. It’s COMPASlicated: The messy relationship between RAI datasets and algorithmic fairness benchmarks. NeurIPS (Datasets & Benchmarks) 2021.
[^4]: Danielle Ensign, Sorelle A Friedler, Scott Neville, Carlos Scheidegger, and Suresh Venkata-Subramanian. Runaway feedback loops in predictive policing. FAccT 2018.
