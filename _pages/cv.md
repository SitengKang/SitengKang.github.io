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

Work experience
======
* Summer 2023: Applied Scientist Internship @ Amazon
  * 
  
* Summer 2022: Applied Scientist Internship @ Amazon
  * Built Sequential event models to identify bad-actor account based on their activities at Amazon, thereby preventing abusive content from entering the community
    * Implemented an end-to-end data loading pipeline for industrial-scale data using Spark-SQL and Python.
    * Developed sequential models using PyTorch, which encompassed RNN, LSTM, and bi-directional LSTM architectures.
    * Identified additional bad-actor accounts that had not been observed by the existing production models
    * Reduced the number of events required for identification by more than half through the sequential models

* Summer 2018: Machine Learning Engineer Intership @ Accenture AI Lab
  * Developed an attention-based OCR model using TensorFlow that recognizes text and numbers from receipts, facilitating the determination of reimbursement for employees.
    
Research experience
======
* Poisoning Attack on Reinforcement Learning @ University of Illinois Chicago
  * Introduced a novel data poisoning attack method in offline-to-online reinforcement learning, revealing its vulnerabilities.
    * Leveraged bi-level optimization techniques to promote distribution shift, causing a significant performance drop during online fine-tuning while maintaining integrity during offline training.
    * Confirmed effectiveness across four environments, highlighting its ability to operate with minimal budget and without requiring white-box access to the victim model.
  * Supervised by Prof. Xinhua Zhang
  * Currently under review.

* Poisoning Attack on Generative Model @ University of Illinois Chicago
  * Proposed a poisoning attack on generative models in the context of replay based continual learning such as DGR.
    * Poison attacked the DGR model through input-aware backdoor attack, promoting catastrophic forgetting on the victim model, trained on permutated MNIST, EMNIST, and CIFAR-10 dataset.
    * Proved the attack to be escapable from Neural Cleanse, the SOTA in defending backdoor attacks.
  * Supervised by Prof. Xinhua Zhang
  * Results published in ICML(2023)

* Recommendation System @ Brown University
  * Proposed an innovative solution to the cold-start problem by leveraging side information such as user's age, gender, address, etc
    * Theoretically validated the empirical bounds of Cartesian Rademacher complexity on nuclear norm constrained models by reformulating the empirical risk minimization (ERM) for bivariate regression into a linear combination of quadratic and linear terms.
    * Designed and implemented the experiment using bivariate regression model.
  * Supervised by Prof. Eli Upfal

    
* Pattern Recognition @ Pennsylvania State University
  * Predicting extreme weather from radar images.
    * Extract skeleton information from radar images in the NOAA dataset.
    * Utilized OpenCV to identify bow echoes from skeleton information.
    * Designed a time series model for predicting severe weather conditions using the bow-echo information.
  * Supervised by Prof. James Wang

* Cryptography @ Purrdue University
  * Analyzed the robustness of algorithms against parallel attacks by computing the space-time complexity of Argon2iA, Argon2iB, and greedy attacks.
  * Supervised by Prof. Jeremiah Blocki
  * Results published in CRYPTO(2019)

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
  

