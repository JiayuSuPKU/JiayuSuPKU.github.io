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
* **PhD in System Biology, Columbia University Columbia University in the City of New York**, 2020 - 2025 (expected)
* **BS in Biological Sciences, Peking University**, 2016 - 2020
* **BS in Mathematics and Applied Mathematics, Peking University**, 2016 - 2020
* **Undergraduate International Student-at-Large (ISAL Scholarship), University of Chicago**, 2018 Fall

Experience
======
* **June 2020 - present: Bioinformatics Engineer, GeneDock Inc.**, Beijing, China
  * Developed R package [gdreports](https://gitlab.genedock.com/sujiayu/gdreports) to allow the automatic generation and customization of PDF and Web reports using R Markdown. 
  * Designed and implemented an end-to-end quality control (QC) and reporting system for whole-genome sequencing (WGS) data.
  * Optimized the cloud computing pipeline for clinical WGS data. Benchmarked and implemented tools for de novo mutation discovery and SV/CNV family joint-calling.

* **Oct. 2017 - July 2020: Research Assistant, Center for Bioinformatics, Peking University**, Beijing, China
  * Projects: 
    1. Statistical modeling of single-cell aging (undergraduate thesis project)
    2. Computational modeling and visualization of cell-cell interaction events
  * Supervisor: [Professor Cheng Li](https://www.ncbi.nlm.nih.gov/pubmed/?term=cheng_li@pku.edu.cn)

* **June 2019 - Sept. 2019: Summer Research Intern, Boston Children's Hospital, Harvard Medical School**, Boston, MA
  * Projects (collaborated with Prof. Cheng Li at PKU):
    1. Single-cell transcriptomic atlas of neutrophils
    2. Neutrophil interaction networks
  * Supervisor: [Professor Hongbo Luo](http://www.childrenshospital.org/Research/Labs/luo-laboratory)
  
Skills
======
* Programming Laguanges: 
  * **Proficient in R**
  * Experience with Python, Java, C, Shell, and MATLAB
* **Well-trained in NGS data analyses**
* Familiar with basics of machine learning, deep learning and statistical inference

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Last update: October 2020
