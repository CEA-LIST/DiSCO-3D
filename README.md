# DiSCO-3D: Discovering and Segmenting Sub-Concepts from Open-Vocabulary Queries in NeRF

![Teaser](img/intro.jpg)

DiSCO-3D is a novel method designed to solve the task of 3D Open-Vocabulary Sub-Concepts Discovery (OV-SD) by bridging the gap between unsupervised semantic segmentation and open-vocabulary segmentation in Neural Radiance Fields (NeRF). It provides scene-aware and query-adaptive semantic segmentations in complex 3D environments.

🎉 Accepted at ICCV 2025 — See you in Hawaii! 🎉
## 🔍 Overview

3D semantic segmentation is crucial for high-level scene understanding in applications like robotics and autonomous systems. Traditional approaches either focus on:

    Open-Vocabulary Segmentation (OVS): segmenting one object class per query, or

    Unsupervised Semantic Segmentation (USS): clustering a scene without prior knowledge.

DiSCO-3D tackles both simultaneously, enabling fine-grained sub-concept discovery from general open-vocabulary queries (e.g., furniture, seatings), without any additional supervision or model modifications.
## 📽️ Demo Videos
Task	Video Path
Open-Vocabulary Sub-Concepts Discovery	img/videos/ovsd.mp4
Architecture Overview	img/videos/global.mp4
OVSD Baseline Comparison	img/videos/ovsd-baselines.mp4
Open-Vocabulary Segmentation	img/videos/ovs.mp4
Unsupervised Semantic Segmentation	img/videos/uss.mp4
## 🧠 Key Contributions

    New Task: Defines the 3D Open-Vocabulary Sub-Concepts Discovery (OV-SD) problem.

    Plug-and-Play: Compatible with existing Neural Fields (e.g., LeRF, OpenNeRF).

    Joint Segmentation Strategy: Combines OVS and USS for improved performance.

    Multi-query Support: Handles disjoint, overlapping, and nested queries.

    Strong Performance: Achieves SoTA on OV-SD and its edge cases.


## 📄 Paper & Supplementary Material

    - 📄 Paper & Supplementary Material: Coming soon


## 🧪 Installation & Usage

    ⚠️ Evaluation Code coming soon.

## 🧾 Citation

If you find this project useful, please cite:

'''
@inproceedings{petit2024ring,
title={RING-NeRF: Rethinking Inductive Biases for Versatile and Efficient Neural Fields},
author={Petit, Doriand and Bourgeois, Steve and Pavel, Dumitru and Gay-Bellile, Vincent and Chabot, Florian and Barthe, Loic},
journal={European Conference on Computer Vision (ECCV)},
year={2024}
}
'''

## 👥 Authors

    - Doriand Petit¹²

    - Steve Bourgeois¹

    - Vincent Gay-Bellile¹

    - Florian Chabot¹

    - Loïc Barthe²

¹ Université Paris-Saclay, CEA List, France
² IRIT, Université Toulouse III, CNRS, France
## 🙏 Acknowledgements

This work was made possible thanks to the use of the CEA List FactoryIA supercomputer, supported by the Île-de-France Regional Council.

The website design was adapted from:

    Michaël Gharbi

    Ref-NeRF

    nerfies

## 📬 Contact

For questions or collaborations, reach out via GitHub.
