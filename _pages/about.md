---
permalink: /
title: "Daniel Otero Gómez"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I'm a second-year MSc student in Artificial Intelligence at the **University of Amsterdam**, doing research under the supervision of Maria Esteban-Casadevall and Prof. [Erik Bekkers](https://amlab.science.uva.nl/people/ErikBekkers/) at [AMLab](https://amlab.science.uva.nl/). My work sits at the intersection of representation learning and generative modeling: learning good representations when labels are scarce, and generating data efficiently when compute is. I'm especially interested in geometric inductive priors, such as symmetries and hierarchies, where the data genuinely can leevrage them.

Before Amsterdam, I spent almost three years as the first hire on the AI team at EXIT83 Consulting. One of my projects there, defect detection in sewer inspection footage, showed me how poorly pretrained self-supervised models transfer to unusual domains, which led to my first research on self-supervised pretraining directly on in-domain data. I later extended this work with Prof. [Randall Balestriero](https://randallbalestriero.github.io/) (Brown University); it received the Best Paper Award at the LatinX in AI Workshop @ NeurIPS 2024. I hold a BSc in Mathematical Engineering from Universidad EAFIT, Colombia.

Current work
======
* **Equivariant drifting for 3D molecules.** Extending drifting models, a one-step alternative to diffusion, to equivariant molecule generation without the alignment steps that become expensive for large 3D graphs. *In preparation.*
* **Continuous flows for speech recognition.** A non-autoregressive ASR model that refines a noisy draft predicted from the audio into the transcript, rather than generating it from noise. Trained from scratch, with no pretrained text model or guidance, the audio-conditioned source halves the word error rate of the same flow started from noise. Next: distilling it into a flow map for one- or few-step decoding. *In preparation.*
* **Few-step and discrete drifting.** Ongoing work that I'll extend in my MSc thesis to a fully discrete setting based on Markov kernels.

Research interests
======
* **Representations for generation.** How can good representations make generative models better: faster training, fewer sampling steps, higher sample quality?
* **Generation for representations.** Can learning to generate in latent space be a route to semantic representation learning, yielding a single model whose embeddings are both semantically rich and well suited for generation?
* **Geometric priors.** Symmetry and hierarchy as inductive biases.

I'm primarily interested in fundamental methods, motivated by (but not tied to) AI for science, climate modeling, and world models.

Recent highlights
======
* **Fall 2026** · Leading the course-wide seminars for **Deep Learning 1** at UvA, focused on implementation and on going deeper into topics from the lectures, including recent advances that build on the foundations covered in class ([materials](https://github.com/daoterog/uva_dl1_seminars_2026)).
* **September 2026** · Started the second year of my MSc and joined **Machine Learning 1** as a Teaching Assistant, teaching 4h of class per week.
* **Summer 2026** · Modernized the coding assignments for **Deep Learning 1** at UvA: added a new part on diffusion models, automated grading, and refactored the codebase for readability and easy setup.
* **Spring 2026** · Started working on equivariant drifting models for 3D molecule generation with AMLab researchers. Also worked on touch prediction and localization with vision foundation models.
* **September 2025** · Started my MSc in Artificial Intelligence at the University of Amsterdam.
* **June 2025** · Awarded the **Colfuturo Scholarship**, ranking 4th out of 1,000+ applicants.
* **December 2024** · Presented a paper at the *Self-Supervised Learning: Theory and Practice* Workshop @ **NeurIPS 2024**, and received **Best Paper** and an **Oral Presentation** at the *LatinX in AI (LXAI)* Workshop @ NeurIPS 2024.
* **July 2024** · Presented my first research project at the *LXAI* Workshop @ **ICML 2024**.

I'm looking for **research positions** after I graduate in 2027, in academia or industry. I'm always happy to talk about research or potential collaborations, so feel free to [email me](mailto:doterog320@gmail.com).
