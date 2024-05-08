---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D in Computer Science, University of Illinois Chicago, 2020-2025 (expected)
* M.S. in Computer Science, Brown University, 2018-2020
* B.S. in Computer Science, B.S. in Mathematics, Minor in Physics, Pennsylvania State University, 2014-2018

Work experiences
======
* Summer 2023: Applied Scientist Internship @ Amazon
  * Built models to predict free-trial to subscription conversion rate on Amazon digital products including Music Unlimited, Prime, Kindle Unlimited, Video Channels, and Audible.
  
* Summer 2022: Applied Scientist Internship @ Amazon
  * Built sequential event models to identify bad-actor account based on their activities at Amazon, thereby preventing abusive content from entering the community.

* Summer 2018: Machine Learning Engineer Intership @ Accenture AI Lab
  * Developed an attention-based OCR model using TensorFlow that recognizes text and numbers from receipts, facilitating the determination of reimbursement for employees.
    
Research experiences
======
* Poisoning Attack on Reinforcement Learning @ University of Illinois Chicago
  * Introduced a novel data poisoning attack on offline-to-online reinforcement learning, revealing its vulnerabilities. 
    * Promoted distribution shift by leveraging bi-level optimization techniques, resulting in more than 20% return drop during online fine-tuning while maintaining integrity during offline training.
    * Validated the effectiveness of the attack across four environments, highlighting its ability to operate with minimal budget without white-box access to the victim model.
  * Supervised by Prof. Xinhua Zhang.
  * Accepted by UAI(2024).

* Poisoning Attack on Generative Model @ University of Illinois Chicago
  * Introduced a poisoning attack on generative models in the context of replay based continual learning such as DGR.
    * Poison attacked the DGR model through input-aware backdoor attack; promoted catastrophic forgetting on the victim model, leading to an accuracy drop on past tasks to below 10%.
    * Proved the attack to be escapable from Neural Cleanse, the SOTA in defending backdoor attacks.
  * Supervised by Prof. Xinhua Zhang.
  * Published in ICML(2023).

* Recommendation System @ Brown University
  * Introduced an innovative solution to the cold-start problem by leveraging side information such as age, gender, etc.
    * Theoretically validated the empirical bounds of Cartesian Rademacher complexity on nuclear norm constrained models by reformulating the empirical risk minimization (ERM) for bivariate regression into a linear combination of quadratic and linear terms.
    * Designed the experiment using bivariate regression model.
  * Supervised by Prof. Eli Upfal.

    
* Pattern Recognition @ Pennsylvania State University
  * Predicting extreme weather from radar images.
    * Extract skeleton information from radar images in the NOAA dataset.
    * Utilized OpenCV to identify bow echoes from skeleton information.
    * Designed a time series model for predicting severe weather conditions using the bow-echo information.
  * Supervised by Prof. James Wang.

* Cryptography @ Purdue University
  * Analyzed the robustness of algorithms against parallel attacks by computing the space-time complexity of Argon2iA, Argon2iB, and greedy attacks.
  * Supervised by Prof. Jeremiah Blocki.
  * Results published in CRYPTO(2019).

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  

Services
======
  <ul>{% for post in site.services reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  

