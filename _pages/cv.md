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
* Ph.D. in Computer Science, Hong Kong University of Science and Technology, 2024 - Present
* B.Eng. in Computer Science, Shanghai Jiao Tong University, 2020 - 2024

Work Experience
======
* Research Intern, MINIMAX, February 2025 - Present
* Research Intern, Tencent WXG, June 2024 - September 2024
* Research Intern, Shanghai AI Lab, June 2023 - December 2023

Skills
======
* Natural Language Processing
* Machine Learning
* LLM Reasoning and Reinforcement Learning
* Vision-Language Models
* Hallucination Detection
* Model Interpretability

Publications
======
### First Author
<ul>
{% for publication in site.publications reversed %}
  {% if publication.first_author == true %}
    <li>
      {{ publication.title }} - {{ publication.venue }} ({{ publication.date | slice: 0, 4 }})
      <a href="{{ publication.paperurl }}">[PDF]</a>
    </li>
  {% endif %}
{% endfor %}
</ul>

### Co-Author
<ul>
{% for publication in site.publications reversed %}
  {% if publication.first_author != true %}
    <li>
      {{ publication.title }} - {{ publication.venue }} ({{ publication.date | slice: 0, 4 }})
      <a href="{{ publication.paperurl }}">[PDF]</a>
    </li>
  {% endif %}
{% endfor %}
</ul>

Awards
======
* Zhiyuan Honor Scholarship, Shanghai Jiao Tong University
