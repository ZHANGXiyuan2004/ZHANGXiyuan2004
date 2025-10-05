---
title: "Rapid Screening and Phase Diagram Prediction of Superionic Conductor Materials"
excerpt: "Utilized active learning and generative models to accelerate the discovery of stable Li-N-S system superionic conductors. <br/><img src='/images/superionic-conductor.jpg'>"
collection: portfolio
---

* [cite_start]**Role:** First Principal Investigator [cite: 28]
* [cite_start]**Duration:** Jan 2025 - May 2025 [cite: 29]
* [cite_start]**Advisor:** Prof. Hong Zhu (Shanghai Jiao Tong University) [cite: 27]

### Description
[cite_start]This project aimed to accelerate the discovery of novel superionic conductors in the Li-N-S system[cite: 30]. [cite_start]We used a small dataset to fine-tune a universal potential function model (MatterSim) and then used it in an active learning loop with a generative model (MatterGen) to efficiently screen for stable materials[cite: 30].

### My Contributions
* [cite_start]**Active Learning Loop:** I constructed the entire active learning cycle to iterate between the model and the data[cite: 31]:
    1.  [cite_start]Fine-tuned MatterSim using a small set of labeled material data[cite: 31].
    2.  [cite_start]Used MatterGen to generate a large pool of unlabeled candidate materials[cite: 31].
    3.  [cite_start]Employed the fine-tuned MatterSim and a Query-by-Committee (QBC) method to assess the uncertainty of the candidates[cite: 31].
    4.  [cite_start]Selected the most uncertain candidates for expensive DFT calculations, then added the newly labeled data back into the training set to start the next cycle[cite: 31].

### Outcomes
* [cite_start]Selected for the Shanghai Jiao Tong University UM-SJTU Joint Institute's 2025 Undergraduate Research Program[cite: 31].
