---
permalink: /
title: "Daniel Otero Gómez"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I'm a second-year MSc student in Artificial Intelligence at the **University of Amsterdam**, doing research under the supervision of Maria Esteban-Casadevall and Prof. [Erik Bekkers](https://amlab.science.uva.nl/people/ErikBekkers/) at [AMLab](https://amlab.science.uva.nl/). My interests sit at the intersection of representation learning and generative modeling: learning good representations when labels are scarce, and generating data efficiently when compute is. I'm especially interested in geometric inductive priors, such as symmetries and hierarchies, where the data genuinely can leverage them.

Current work
======
* **Equivariant drifting for 3D molecules.** Extending drifting models, a one-step alternative to diffusion, to equivariant molecule generation without the alignment steps that become expensive for large 3D graphs. *In preparation.*
* **Continuous flows for speech recognition.** A non-autoregressive ASR model that refines a noisy draft predicted from the audio into the transcript, rather than generating it from noise. Trained from scratch, with no pretrained text model or guidance, the audio-conditioned source halves the word error rate of the same flow started from noise. Next: distilling it into a flow map for one- or few-step decoding. *In preparation.*
* **Unification of few-step generation methods.** Recent methods for few-step generation are defined in isolation, with their own objective, notation, and theory. I'm putting them in a common framework to clarify what truly separates them, as a first step toward a unified view that connects them to flow matching and diffusion. *Just started.*

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

Past experience
======
* **AI/ML Engineer, EXIT83 Consulting** · 2023–2025. First hire on the AI team. One of my projects, defect detection in sewer inspection footage, showed me how poorly pretrained self-supervised models transfer to unusual domains, and led to my first research on self-supervised pretraining directly on in-domain data.
* **Research collaboration, Brown University** · 2024–2025. Extended that work with Prof. [Randall Balestriero](https://randallbalestriero.github.io/) to more self-supervised methods and domains.
* **BSc in Mathematical Engineering, Universidad EAFIT** · 2018–2023, Medellín, Colombia.

I'm looking for **research positions** after I graduate in 2027, in academia or industry. I'm always happy to talk about research or potential collaborations, so feel free to [email me](mailto:doterog320@gmail.com).
