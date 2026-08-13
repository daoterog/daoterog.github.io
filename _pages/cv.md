---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<!-- Upload your PDF to the files/ folder and it will be served at /files/<name>.pdf -->
[Download as PDF](/files/Daniel_Otero_Gomez_CV.pdf)

Education
======
* **M.S. in Artificial Intelligence**, University of Amsterdam, Sep. 2025 – Aug. 2027 (expected)
  * Awarded the Colfuturo Scholarship (Colombian Government), ranked 4th out of 1000+ applicants
  * On track for the ELLIS honours track and graduating *cum laude*
* **B.S. in Mathematical Engineering**, Universidad EAFIT, Medellín, July 2018 – June 2023
  * GPA: 4.61 / 5.0
  * Offered a Software Engineering Internship at Meta (London, UK, Fall 2022)
  * Selected as one of 40 participants across Latin America for Mercado Libre's Machine Learning Bootcamp

Research experience
======
* **Research Project — AMLab, University of Amsterdam**, Sep. 2026 – Present
  * Developing a new approach to non-autoregressive automatic speech recognition using continuous flow-based models

* **Research Collaboration — Université de Montréal (Mila)**, Oct. 2025 – Present
  * Feasible Learning: a per-sample constrained optimization framework designed to guarantee a minimum performance threshold on every training sample
  * Exploring its properties relative to Empirical Risk Minimization and its usefulness when paired with more interpretable optimization goals

* **Research Collaboration — Brown University**, Aug. 2024 – May 2025
  * Collaborated with Prof. Randall Balestriero on self-supervised learning for anomaly detection
  * Earned an oral presentation and best paper award at the LatinX in AI Workshop (NeurIPS 2024)

* **Student Research Assistant — Cooper Open-Source Project**, July 2022 – Dec. 2022
  * Cooper incorporates secondary requirements (e.g. fairness or resource constraints) into the optimization process without tedious penalty tuning
  * Integrated a state-of-the-art algorithm into the library, validating it by reproducing the original experiments

Industry experience
======
* **AI/ML Engineer — EXIT83 Consulting**, Mar. 2023 – Aug. 2025

  *Defect detection in sewer maintenance CCTV videos*
  * Pre-processed 25,000+ videos, curated frames, and trained models on 2.3M+ images on Azure clusters
  * Reduced training cost by 70% by implementing FFCV and migrating training to low-priority clusters
  * Debugged model training and identified critical issues in the data collection strategy
  * Deployed the model using AWS Batch Transform, Lambda Functions, and DynamoDB
  * Solution sped up inspector load by 7x and improved their accuracy by 20%

  *Multiple agent-driven projects*
  * Designed, built, and deployed agentic AI systems that autonomously plan and execute multi-step workflows
  * Created custom tools to research, extract, and synthesize information from diverse data sources
  * Iteratively deployed and refined production systems under real-world data constraints

  *Gesture control on low-resolution edge devices for airplane entertainment systems*
  * Developed a low-compute neural network for low-latency gesture recognition on Time-of-Flight devices
  * Led data collection and curation; implemented a feedback loop that fed hard samples back into training

Skills
======
* **Programming**: Python (proficient), SQL (advanced), TypeScript (good), React (basic)
* **ML/DL**: PyTorch, scikit-learn, WandB, MLflow, submitit, FFCV
* **Infrastructure**: Docker, AWS (Batch Transform, Lambda, DynamoDB), Azure ML clusters
* **Backend & agents**: FastAPI, Express, LangGraph
* **Languages**: English (C2), French (B2), Spanish (native)

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Interests
======
* Playing guitar, cooking, exercising, traveling, and spending time with family and friends
