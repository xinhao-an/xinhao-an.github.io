---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

**Xinhao An** · PhD Candidate in Structural Engineering  
School of Infrastructure Engineering, Dalian University of Technology, China  
[axh1930@mail.dlut.edu.cn](mailto:axh1930@mail.dlut.edu.cn) · [Google Scholar](https://scholar.google.com/citations?user=MEf3nMAAAAAJ&hl=en) · [ResearchGate](https://www.researchgate.net/profile/Xinhao-An)

## Education

**PhD in Structural Engineering**, Dalian University of Technology, China  
September 2023–present · Expected graduation: March 2027  
Supervisor: Assoc. Prof. Jilin Hou  
Thesis in progress: *Structural dynamic load identification based on physics–data hybrid modeling.*

**Visiting PhD Student in Structural Engineering**, Politecnico di Milano, Italy  
September 2025–September 2026  
Department of Civil and Environmental Engineering  
Host supervisor: Prof. Stefano Mariani

**Master of Engineering in Structural Engineering**, Dalian University of Technology, China  
September 2020–June 2023  
Supervisor: Assoc. Prof. Jilin Hou  
Thesis: *Identification of vehicle physical parameters based on dynamic responses.*

**Bachelor of Engineering in Civil Engineering**, Qingdao University of Technology, China  
September 2016–June 2020

## Research experience

- **Digital Twin Engineering for Sustainable Operation of Port Infrastructure**, National Key R&D Program of China, December 2024–November 2029. Research team member; PI: Assoc. Prof. Jilin Hou. Dynamic load identification, response reconstruction, and digital-twin-based state estimation.
- **Structural Health Monitoring of Wind- and Seismic-Resistant Structures**, National Key R&D Program of China, September 2020–June 2021. Research team member; PI: Assoc. Prof. Jilin Hou. Virtual constraints, computer vision, and additional virtual mass methods for damage identification.

## Publications

{% for category in site.publication_category %}
{% assign papers = site.publications | where: "category", category[0] | sort: "date" | reverse %}
{% if papers.size > 0 %}
### {{ category[1].title }}

{% for post in papers %}
- {{ post.citation }} [DOI]({{ post.paperurl }})
{% endfor %}
{% endif %}
{% endfor %}

*\* Corresponding author.*

{% include manuscripts-in-progress.md %}

{% include open-research-data.md %}

## Skills

- **Programming and scientific computing:** MATLAB (signal processing and optimization); Python (PyTorch and NumPy).
- **Structural analysis and simulation:** ANSYS, OpenSeesPy, and basic experience with OpenFAST.
- **Research methods:** signal processing, system identification, structural dynamics, physics–data hybrid modeling, Kalman filtering, and Bayesian inference.
- **Languages:** Chinese (native); English (CET-6).
- **Certification:** National Computer Rank Examination, Level 2, MS Office Applications, China.

## Selected awards and honors

- **November 2026:** First-Class Academic Scholarship, Dalian University of Technology.
- **October 2026:** Doctoral Excellence Scholarship, Dalian University of Technology.
- **October 2024:** Outstanding Graduate Student, Dalian University of Technology.
- **November 2022:** Academician Zhao Guofan Scholarship, Dalian University of Technology.
