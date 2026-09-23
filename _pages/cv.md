---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
---

{% include base_path %}

Education
======
* **Ph.D. in Computer Science** (2024-Present) at Hong Kong University of Science and Technology
* **B.Eng.** (2020-2024) at Shanghai Jiao Tong University

Research Experience
======
* **Research Intern, MINIMAX** (February 2025 - Present)
* **Research Intern, Tencent WXG** (June 2024 - September 2024)
* **Research Intern, Shanghai AI Lab** (June 2023 - December 2023)

Research Interests
======
* LLM Reasoning and Reinforcement Learning
* Hallucination in Vision-Language Models
* LLM Truthfulness and Interpretability

Skills
======
* Natural Language Processing
* Machine Learning
* LLM Reasoning
* Reinforcement Learning
* Vision-Language Models
* Hallucination Research
* Interpretability
* Truthfulness

Publications
======
  {% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}

Talks
======
  {% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}

Teaching
======
  {% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}

Service and leadership
======
* Currently signed in to 43 different slack teams
