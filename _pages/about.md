---
permalink: /
title: "Welcome"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a third-year PhD Student the University of Stuttgart, Germany advised by [Prof. Andreas Bulling](https://perceptualui.org/people/bulling/). My research focuses broadly on multi-modal deep models at the intersection of computer vision and natural language processing. Specifically, I develop novel AI model especially geared towards conversational tasks such as visual and video dialog. Furthermore, I research efficient mechanisms of marrying graph neural networks with large multi-modal transformers to mitigate their lack of inductive bias while training on limited amounts of data. Finally, I develop pre-training strategies of multi-modal foundation models specifically geared towards improving the downstream visual/video conversational tasks.
I hold a BSc and a MSc degrees in the elite study program Simulation Technology at the University of Stuttgart. The latter was awarded with distinction and received the [outstanding work award](https://www.simtech.uni-stuttgart.de/press/IC-SimTech-honors-outstanding-theses-00001/) from the Industrial Consortium SimTech (IC SimTech).

News
======
* [01.11.2023] Reviewing for ACL Rolling Review (October Cycle 2023)
* [24.10.2023] 🔥 One paper got accepted at WACV 2024. Hawaii, USA
* [29.09.2023] Reviewing for CHI 2024
* [15.04.2023] Reviewing for ACM MM 2023
* [02.02.2023] Reviewing for the Journal of Artificial Intelligence 2023
* [16.08.2022] 🔥 One paper got accepted at COLING 2022 (**oral presentation**). Gyeongju, Republic of Korea
* [27.03.2022] 🔥 One paper got accepted at the ACL 2022 Workshop Representation Learning for NLP (RepL4NLP). Dublin, Ireland
* [01.04.2021] 🥇 My master's thesis received the the outsanding work award from IC SimTech
* [28.02.2021] 🎓 I defended my MSc Thesis **with distinction**

Publications
======
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
