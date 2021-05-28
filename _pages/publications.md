---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

## Papers
<p float='left'>
	<img src="https://qiyan98.github.io/images/social-nce.png" width="600"/> 
</p>

**Social NCE: Contrastive Learning of Socially-aware Motion Representations**
<br/>
Yuejiang Liu, **Qi Yan**, Alexandre Alahi
<br/>
Abbreviated version accepted at *NeurIPS Workshop on Self-Supervised Learning, 2020.*
<br/>
[[arXiv](https://arxiv.org/abs/2012.11717)] [[code](https://github.com/qiyan98/social-nce-stgcnn)]

<hr style="border:1px solid gray"/> 

<p float='left'>
	<img src="https://qiyan98.github.io/images/JET2020_0.png" width="250"/> 
	<img src="https://qiyan98.github.io/images/JET2020_1.png" width="350"/>
</p>
**[Tribo-Dynamic Simulation and Motion Control of a Rotating Manipulator Based on the Load and Temperature Dependent Friction](https://journals.sagepub.com/doi/10.1177/1350650120954943)**
<br/>
**Qi Yan**, Rui Li, Xianghui Meng
<br/>
*Proceedings of the Institution of Mechanical Engineers, Part J: Journal of Engineering Tribology*, September 2020
<br/>
[[code](https://github.com/qiyan98/Manipulator-dynamics)]

<hr style="border:1px solid gray"/> 

<p float='left'>
	<img src="https://qiyan98.github.io/images/RAL2020.png" width="250"/>
</p>
**[Measurement Scheduling for Cooperative Localization in Resource-Constrained Conditions](https://ieeexplore.ieee.org/abstract/document/8972554/)**
<br/>
**Qi Yan**, Li Jiang, Solmaz S. Kia
<br/>
*IEEE Robotics and Automation Letters*, April 2020 
<br/>
[[arXiv](https://arxiv.org/abs/1912.04709)] [[video](https://www.youtube.com/watch?v=5KAiav6astY)] [[code](https://github.com/qiyan98/CL_Measurement_Scheduling)]
<br/>

<hr style="border:1px solid gray"/> 