---
title: "HINT-VLM: Humanoid Interactive Navigation over Rough Terrain with Embodiment-Grounded Vision-Language Model"
collection: publications
category: conferences
permalink: /publication/2026-11-hint-vlm
excerpt: "Ziwon Yoon, Seok Hwan Kim, Yiyu Chen, Quan Nguyen, Lu Gan, Ye Zhao <img src='/images/publications/hintvlm_teaser.jpg'><br/>"
date: 2026-11-08
venue: 'CoRL 2026 Workshop on Spatial Intelligence and Structured Reasoning for Embodied Navigation (SISREN)'
slidesurl: 'https://yzwfromk.github.io/HINT_VLM/#real-world'
paperurl: 'https://arxiv.org/abs/2611.11665'
---

Humanoid robots have achieved significant progress in locomotion and manipulation, enabling traversal over rough terrain and richer interaction with the environment, such as moving obstacles. However, most traditional navigation methods assume non-interactive environments and focus only on traversal. While Navigation Among Movable Obstacles (NAMO) approaches relax this assumption, prior efforts have largely focused on flat environments and reactive interaction, rather than predicting object movability and planning ahead. These limitations become critical in outdoor rough-terrain scenarios, where robots must jointly reason about terrain traversability and object movability. In this work, we address NAMO for humanoid robots in cluttered outdoor rough terrain by proposing a hybrid planning framework that combines semantic priors from a Vision-Language Model (VLM) with embodied robot interaction data through a Gaussian process (GP) residual model. The GP corrects the VLM-derived movability prior to produce embodiment-grounded probabilistic movability estimates, which are then incorporated into hierarchical uncertainty-aware planning. The proposed approach allows humanoids to jointly leverage locomotion and manipulation for efficient and safe navigation, representing the first solution to NAMO in rough terrain through predictive movability reasoning and probabilistic VLM integration. Project page: [https://yzwfromk.github.io/HINT_VLM/](https://yzwfromk.github.io/HINT_VLM/)
