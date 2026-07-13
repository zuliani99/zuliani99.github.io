---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Machine Learning Engineer with a solid academic background and hands-on experience in deep learning, time series anomaly detection, and computer vision. Skilled in Python, PyTorch, and key ML frameworks, with a strong focus on applying data-driven solutions to real-world challenges. Experienced in developing end-to-end pipelines for data analysis, model training, and deployment. Passionate about AI applications in industrial and automotive contexts, with a proactive and research-oriented mindset.

[Download the PDF version](/files/RiccardoZuliani_CV.pdf)

Education
======
* M.S. in Computer Science — Data Management and Analysis, Ca' Foscari University of Venice, 2024
  * Thesis: *Active Learning with Dynamical System*
  * Relevant courses: Artificial Intelligence, 3D Geometric Computer Vision, Statistical Inference
* B.S. in Computer Science — Data Science, Ca' Foscari University of Venice, 2021
  * Thesis: *Dash AutoML Benchmark*
  * Relevant courses: Algorithms and Data Structures, Databases, Data Analysis, Predictive Analytics

Work experience
======
* Oct 2024 – Jun 2026: **Machine Learning Engineer & Researcher**, NAIS Engineering Srl — Bologna, Italy
  * Data Analysis: developed multiple web applications to better visualize project results and analyses using the Dash Plotly framework.
  * Data Engineering: built multiple aggregated datasets at different depth levels on Formula 1 engines, with a single record sampled every 0.005 seconds (5 Hz).
  * Neural Network Modelling: developed and evaluated different anomaly detection models on time series datasets.

* Nov 2023 – Jan 2024: **Probability and Statistics Tutor**, Ca' Foscari University of Venice — Venice, Italy
  * Delivered 10 classes on key topics in probability and statistics, helping students succeed in their exam.
  * Assisted 30 students in solving statistical problems both manually and using R.
  * Provided one-on-one support to clarify statistical concepts and methodologies.

Skills
======
* **Core languages**: Python, C++, SQL, R
* **Frameworks &amp; libraries**: PyTorch, OpenCV, Scikit-learn, Hugging Face, Pandas, NumPy, Matplotlib, Seaborn, Dash Plotly, Flask
* **Technologies**: Deep Learning, Machine Learning, Computer Vision, Git, Linux, Docker
* **Languages**: Italian (native), English (B2+, upper-intermediate)

Projects
======
* [Active Learning with Dynamical System](/portfolio/master_project/) — a novel Active Learning methodology that uses a Graph Transduction Game to select the most difficult samples over a subset to add to the labeled set.
* [Silhouette-Based Space Carving](/portfolio/shiluette/) — reconstructed the 3D shape of an object captured from multiple angles during rotation, progressively removing empty space based on object silhouettes.
* [Video Classification with Convolutional Neural Networks](/portfolio/video_cnn/) — a benchmark over a set of different CNNs on the 1M Sports YouTube Video dataset, inspired by the original paper.
* [Dash AutoML Benchmark](/portfolio/bachelor_project/) — a web application to test and evaluate current SOTA AutoML algorithms over a set of Kaggle and OpenML datasets, for both regression and classification tasks.

See all of my work in the [portfolio](/portfolio/).

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
