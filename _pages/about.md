---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am Junteng Liu, a first-year PhD candidate in the HKUST NLP Group at the Hong Kong University of Science and Technology, advised by Professor Junxian He, who also advised me during my undergraduate studies at SJTU. I graduated from Shanghai Jiao Tong University (SJTU) in June 2024. My research focuses on natural language processing and machine learning.

Research Interests
======

* LLM Reasoning and Reinforcement Learning
* Hallucination in Vision-Language Models (VLM)
* LLM truthfulness and Interpretability

Education
======

* Ph.D. in Computer Science, Hong Kong University of Science and Technology, 2024-Present
* B.Eng., Shanghai Jiao Tong University, 2020-2024

Research Experience
======

* Research Intern, MINIMAX, February 2025 - Present
* Research Intern, Tencent WXG, June 2024 - September 2024
  * Advisor: Zifei Shan
* Research Intern, Shanghai AI Lab, June 2023 - December 2023
  * Advisor: Prof. Yu Cheng

Honors and Awards
======

* Zhiyuan Honor Scholarship, Shanghai Jiao Tong University

Skills
======

* Natural Language Processing
* Machine Learning

Publications
======

You can also find my articles on <a href="{{ site.author.googlescholar }}">my Google Scholar profile</a>. Code for SynLogic, Vision4Chart, and Universal_Truthfulness_Hyperplane is available on <a href="https://github.com/Vicent0205">GitHub</a>.

{% for post in site.publications %}
<p>
  <strong>{{ post.title }}</strong><br />
  {{ post.authors | markdownify | remove: "<p>" | remove: "</p>" }}<br />
  <em>{{ post.venue }}</em>, {{ post.year }}
</p>
{% endfor %}

Contact
======

* Email: <a href="mailto:jliugi@connect.ust.hk">jliugi@connect.ust.hk</a>
* GitHub: <a href="https://github.com/Vicent0205">Vicent0205</a>
* Google Scholar: <a href="https://scholar.google.com/citations?hl=en&amp;user=tbK9jl4AAAAJ&amp;view_op=list_works&amp;sortby=pubdate">Junteng Liu</a>
* X (Twitter): @junteng88716710
