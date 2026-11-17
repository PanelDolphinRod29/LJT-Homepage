---
permalink: /
title: "About"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

## Personal details

I am a first-year PhD candidate at the **HKUST NLP Group**, **Hong Kong University of Science and Technology (HKUST)**, advised by **Professor Junxian He**. My research focuses on **natural language processing** and **machine learning**.

- **Name:** Junteng Liu
- **Position:** First-year PhD candidate, HKUST NLP Group, Hong Kong University of Science and Technology
- **Advisor:** Professor Junxian He
- **Research focus:** Natural language processing and machine learning
- **Research interests:** LLM reasoning and reinforcement learning; hallucination in vision-language models (VLMs); LLM truthfulness and interpretability

## Academic background

- **Ph.D. in Computer Science**, Hong Kong University of Science and Technology, 2024–Present.  
  HKUST NLP Group; supervised by Professor Junxian He.
- **B.Eng.**, Shanghai Jiao Tong University (SJTU), 2020–2024; graduated in June 2024.  
  Professor Junxian He previously advised me during undergraduate studies at SJTU.

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

The publication list is also available on the [Publications page]({{ '/publications/' | relative_url }}).

{% include base_path %}

{% assign publications = site.publications | sort: "pub_order" | reverse %}
<ul>
  {% for post in publications %}
    {% include archive-single.html %}
  {% endfor %}
</ul>

## Honors and awards

- Zhiyuan Honor Scholarship, Shanghai Jiao Tong University.

## Contact information

- **Email:** [jliugi@connect.ust.hk](mailto:jliugi@connect.ust.hk)
- **GitHub:** [Vicent0205](https://github.com/Vicent0205)
- **Google Scholar:** [Google Scholar profile](https://scholar.google.com/citations?hl=en&user=tbK9jl4AAAAJ&view_op=list_works&sortby=pubdate)
- **X (Twitter):** [@junteng88716710](https://x.com/junteng88716710)
