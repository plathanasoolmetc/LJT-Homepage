---
permalink: /about/
title: "About"
author_profile: true
---

I am **Junteng Liu**, a Ph.D. candidate in Computer Science at the **Hong Kong University of Science and Technology (HKUST)** and a member of the **HKUST NLP Group**, advised by **Prof. Junxian He**. I received my B.Eng. from **Shanghai Jiao Tong University (SJTU)** in June 2024, where I was also advised by Prof. He.

My research lies at the intersection of **natural language processing** and **machine learning**. I am particularly interested in:

- LLM reasoning and reinforcement learning;
- hallucination in vision-language models;
- LLM truthfulness and interpretability.

## Education

- **Ph.D. in Computer Science**, Hong Kong University of Science and Technology, 2024–present
- **B.Eng.**, Shanghai Jiao Tong University, 2020–2024

## Research Experience

- **Research Intern, MINIMAX**, February 2025–present
- **Research Intern, Tencent WXG**, June 2024–September 2024  
  Advised by Zifei Shan.
- **Research Intern, Shanghai AI Lab**, June 2023–December 2023  
  Advised by Prof. Yu Cheng.

## Publications

My publications are recorded here as well as on the dedicated [Publications page]({{ '/publications/' | relative_url }}). My name is shown in **bold**.

{% assign about_publications = site.publications | sort: "date" | reverse %}
{% for post in about_publications %}
  {% include archive-single.html %}
{% endfor %}

## Research Skills

My work covers foundation-model evaluation, verifiable reasoning-data synthesis, representation analysis, hallucination mitigation, chart understanding, and research on reasoning, truthfulness, and interpretability in large models.

## Honors

- **Zhiyuan Honor Scholarship**, Shanghai Jiao Tong University

## Contact

- Email: [jliugi@connect.ust.hk](mailto:jliugi@connect.ust.hk)
- [Google Scholar](https://scholar.google.com/citations?hl=en&user=tbK9jl4AAAAJ&view_op=list_works&sortby=pubdate)
- [GitHub](https://github.com/Vicent0205)
- [X / Twitter](https://x.com/junteng88716710)
