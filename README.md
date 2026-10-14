# Awesome-Synthesized-Training-Data-Engines

## Top Synthesized Training Data Engines Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Privacy-Preserving Data Generation, Synthetic Tabular/Image Data & Training Data Fabrication*  

**Last updated: March 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Synthesized Training Data Engines**. These tools generate artificial data that preserves the statistical properties of real datasets while protecting individual privacy — enabling ML model training, software testing, and data sharing without exposing sensitive information.



**Examples** include Gretel.ai, Mostly AI, Synthesis AI, Tonic.ai, Hazy, Parallel Domain, Synthetaic, DataGen, YData, and Mindtech (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, differential privacy guarantees, and transparent synthetic data generation — ideal for data scientists prioritizing privacy, developers building ML pipelines, and organizations avoiding per-record API costs.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Gretel.ai](https://gretel.ai/)**  

  Privacy-preserving synthetic data platform for tabular, text, and time-series data. Features built-in evaluation for fidelity, privacy, and memorization. Open-sources several components including `gretel-synthetics` (differentially private learning) and `sdmetrics` (quality evaluation) .



- **[Mostly AI](https://mostly.ai/)**  

  Commercial platform for privacy-preserving tabular synthetic data with differential privacy guarantees. Their engine is available as `mostlyai-engine` on GitHub .



- **[Synthesis AI](https://synthesis.ai/)**  

  Synthetic data platform for computer vision, generating labeled image and video datasets for ML training.



- **[Tonic.ai](https://www.tonic.ai/)**  

  Developer-focused synthetic data tool with privacy constraints for test data generation and de-identification.



- **[Hazy](https://hazy.com/)**  

  Enterprise-grade platform for secure synthetic data pipelines with privacy guarantees.



- **[Parallel Domain](https://paralleldomain.com/)**  

  Synthetic data generation for autonomous driving and robotics simulation.



- **[Synthetaic](https://synthetaic.com/)**  

  AI platform for generating synthetic data from satellite and geospatial imagery.



- **[DataGen](https://datagen.com/)**  

  Synthetic data platform for computer vision and biometric applications.



- **[YData](https://ydata.ai/)**  

  Synthetic data platform with open-source `ydata-synthetic` library for GAN-based tabular and time-series generation .



- **[Mindtech](https://mindtech.ai/)**  

  Synthetic data platform specializing in human-centric AI training data.



## Open-Source GitHub Projects



- **[SDV (Synthetic Data Vault)](https://github.com/sdv-dev/SDV)**  

  The most popular open-source framework for generating synthetic tabular, relational, and time-series data. Includes **CTGAN** (Conditional GAN for tabular data), **TVAE**, **Copulas**, and **DeepEcho** (mixed-type multivariate time series). Extensive evaluation metrics via **SDMetrics** (quality, fidelity, statistical similarity) .



- **[ydata-synthetic](https://github.com/ydataai/ydata-synthetic)**  

  Open-source GAN-based synthetic data generator for tabular and time-series data. 1,500+ GitHub stars .



- **[synthcity](https://github.com/vanderschaarlab/synthcity)**  

  Library for generating and evaluating synthetic tabular data for privacy, fairness, and data augmentation. 419+ GitHub stars, actively maintained. Includes multiple generative models and evaluation frameworks .



- **[dpmm (Differentially Private Marginal Models)](https://github.com/sassoftware/dpmm)**  

  Open-source Python library from SAS for generating synthetic tabular data with differential privacy guarantees. Implements **PrivBayes**, **MST**, and **AIM** marginal models. Presented at TPDP 2025. Follows best practices for end-to-end privacy guarantees .



- **[DPSynth](https://github.com/MukulBijalwan/DPSynth)**  

  R package for differentially private synthetic data with guaranteed utility. Provides DP Gaussian mixture models, DP Gaussian copulas, DP histogram marginals, and PATE synthesizer for mixed-type data. Includes standardized utility evaluation, disclosure risk auditing, and privacy budget accounting .



- **[OpenDP SmartNoise](https://github.com/opendp/smartnoise-sdk)**  

  Differential privacy tools for generating and evaluating synthetic data. Part of the OpenDP initiative .



- **[DataSynthesizer](https://github.com/DataResponsibly/DataSynthesizer)**  

  Open-source differentially private synthetic data generator from the Data Responsibly project.



- **[synthcity](https://github.com/vanderschaarlab/synthcity)** (alternate reference)  

  A library for generating and evaluating synthetic tabular data for privacy, fairness and data augmentation .



- **[mostlyai-engine](https://github.com/mostly-ai/mostlyai-engine)**  

  Open-source synthetic data engine from Mostly AI .



- **[MetaSyn](https://github.com/sodascience/metasyn)**  

  Transparent generation of synthetic tabular data with privacy guarantees. Includes `metasyn-disclosure-control` plugin for preventing data leakage .



- **[synthflow](https://github.com/shlomihod/synthflow)**  

  Python package designed to facilitate the end-to-end production of differentially private synthetic data .



- **[Anonymeter](https://github.com/statice/anonymeter)**  

  A unified framework for quantifying privacy risk in synthetic data according to the GDPR .



- **[TabDDPM](https://github.com/amazon-science/tab-ddpm)**  

  Official implementation of "TabDDPM: Modelling Tabular Data with Diffusion Models" (ICML 2023). 370+ GitHub stars .



- **[FewShotTabLLM](https://github.com/BMW-InnovationLab/FewShotTabLLM)**  

  Few-shot, training-free generation framework for tabular data leveraging LLMs. Outperforms CTGAN, TVAE, TabDDPM, and BeGReaT on representativeness, realism, and privacy preservation. Presented at IEEE COMPSAC 2026 .



### Additional Strong Open-Source Options



- **[CTGAN](https://github.com/sdv-dev/CTGAN)** — Conditional GAN for generating synthetic tabular data. 1,338+ GitHub stars .

- **[mimesis](https://github.com/lk-geimfari/mimesis)** — Robust Python data generator producing fake data in multiple languages. 4,498+ GitHub stars .

- **[DataMimic](https://github.com/rapiddweller/datamimic)** — Model-driven test data generation platform with GDPR compliance and Python integration .

- **[Harlequin](https://github.com/lparolari/harlequin)** — Color-driven generation of synthetic data for referring expression comprehension .

- **[Blenderline](https://github.com/maxvandenhoven/blenderline)** — Blender pipeline for generating synthetic images of production lines .

- **Simulation Engines** — CARLA, AirSim, NVIDIA Isaac Sim, Unity Perception for synthetic sensor data .

- **Image/Video Generators** — Stable Diffusion, Stable Video Diffusion, Diffusers for synthetic image generation .



**Frameworks for building custom systems**: Combine **SDV** for tabular and time-series synthesis, **dpmm** or **DPSynth** for differential privacy guarantees, **synthcity** for privacy-fairness evaluation, **FewShotTabLLM** for training-free LLM-based generation, and **Anonymeter** for privacy risk quantification to build a complete self-hosted synthetic data stack.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Synthetic data generation tools must comply with data protection regulations (GDPR, CCPA), industry standards, and ethical AI guidelines. **Synthetic data may still leak information about real individuals unless generated with formal privacy guarantees (e.g., differential privacy).**

- Self-hosted open-source solutions require proper security hardening, privacy budget management, and ongoing validation of synthetic data quality.



---



**Made for data scientists, privacy engineers, ML practitioners, and developers building synthetic data generation platforms.**  

Let's make synthesized training data more open, privacy-preserving, and responsible.
