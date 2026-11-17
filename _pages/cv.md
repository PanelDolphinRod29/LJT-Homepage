---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Education

- **Ph.D. in Computer Science**, Hong Kong University of Science and Technology, 2024–Present; HKUST NLP Group; supervised by Professor Junxian He.
- **B.Eng.**, Shanghai Jiao Tong University (SJTU), 2020–2024; graduated in June 2024; previously advised by Professor Junxian He during undergraduate studies at SJTU.

## Research experience

- **Research Intern**, MINIMAX, February 2025–Present.
- **Research Intern**, Tencent WXG, June 2024–September 2024; advisor: Zifei Shan.
- **Research Intern**, Shanghai AI Lab, June 2023–December 2023; advisor: Prof. Yu Cheng.

## Skills and research interests

- Natural language processing
- Machine learning
- LLM reasoning and reinforcement learning
- Hallucination in vision-language models (VLMs)
- LLM truthfulness and interpretability

## Publications

{% assign publications = site.publications | sort: "pub_order" | reverse %}
<ul>
  {% for post in publications %}
    {% include archive-single-cv.html %}
  {% endfor %}
</ul>

## Honors and awards

- Zhiyuan Honor Scholarship, Shanghai Jiao Tong University.
