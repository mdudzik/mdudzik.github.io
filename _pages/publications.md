---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

<!-- New style rendering if publication categories are defined -->
{% if site.publication_category %}
  {% for category in site.publication_category  %}
    {% assign title_shown = false %}
    {% for post in site.publications reversed %}
      {% if post.category != category[0] %}
        {% continue %}
      {% endif %}
      {% unless title_shown %}
        <h2>{{ category[1].title }}</h2><hr />
        {% assign title_shown = true %}
      {% endunless %}
      {% include archive-single.html %}
    {% endfor %}
  {% endfor %}
{% else %}
  {% for post in site.publications reversed %}
    {% include archive-single.html %}
  {% endfor %}
{% endif %}

## Research

- O Vinyals, I Babuschkin, WM Czarnecki, M Mathieu, A Dudzik, J Chung, ..., [Grandmaster level in StarCraft II using multi-agent reinforcement learning](https://www.nature.com/articles/s41586-019-1724-z)\
nature 575 (7782), 350-354
	2019
- O Vinyals, I Babuschkin, J Chung, M Mathieu, M Jaderberg, ..., [Alphastar: Mastering the real-time strategy game starcraft II](https://deepmind.google/discover/blog/alphastar-mastering-the-real-time-strategy-game-starcraft-ii/) DeepMind blog 2, 20 2019
- J Abramson, A Ahuja, I Barr, A Brussee, F Carnevale, M Cassin, ..., [Imitating interactive intelligence](https://arxiv.org/abs/2012.05672) [arXiv:2012.05672](https://arxiv.org/abs/2012.05672) 2020 [PDF](https://arxiv.org/pdf/2012.05672)
- AJ Dudzik, P Veličković, [Graph neural networks are dynamic programmers](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=DdFjaEEAAAAJ&citation_for_view=DdFjaEEAAAAJ:9yKSN-GCB0IC)\
Advances in neural information processing systems 35, 20635-20647 2022 [PDF](https://proceedings.neurips.cc/paper_files/paper/2022/file/8248b1ded388fcdbbd121bcdfea3068c-Paper-Conference.pdf)
- B Gavranović, P Lessard, A Dudzik, T von Glehn, JGM Araújo, ..., [Categorical deep learning: An algebraic theory of architectures](https://arxiv.org/abs/2402.15332) [arXiv:2402.15332](https://arxiv.org/abs/2402.15332)
	2024
- W Bounsi, B Ibarz, A Dudzik, JB Hamrick, L Markeeva, A Vitvitskyi, ..., [Transformers meet Neural Algorithmic Reasoners](https://arxiv.org/abs/2406.09308) [arXiv:2406.09308](https://arxiv.org/abs/2406.09308)
	2024
- B Gavranović, P Lessard, AJ Dudzik, T von Glehn, JGM Araújo, ..., [Position: Categorical Deep Learning is an Algebraic Theory of All Architectures](https://openreview.net/forum?id=EIcxV7T0Sy)\
Forty-first International Conference on Machine Learning 2024 [PDF](https://openreview.net/pdf?id=EIcxV7T0Sy)
- B Ibarz, V Kurin, G Papamakarios, K Nikiforou, M Bennani, R Csordás, ..., [A generalist neural algorithmic learner](https://proceedings.mlr.press/v198/ibarz22a.html)
Learning on graphs conference, 2: 1-2: 23 2022 [PDF](https://proceedings.mlr.press/v198/ibarz22a/ibarz22a.pdf)
- AJ Dudzik, T von Glehn, R Pascanu, P Veličković, [Asynchronous algorithmic alignment with cocycles](https://proceedings.mlr.press/v231/dudzik24a.html)
Learning on Graphs Conference, 3: 1-3: 17 2024 [PDF](https://proceedings.mlr.press/v231/dudzik24a/dudzik24a.pdf)
- P Monteagudo-Lago, A Rosinski, AJ Dudzik, P Veličković, [Asynchrony Invariance Loss Functions for Graph Neural Networks](https://openreview.net/forum?id=eeEMjpO2Kv)
ICML 2024 Workshop on Geometry-grounded Representation Learning and Generative Modeling
2024 [PDF](https://openreview.net/pdf?id=eeEMjpO2Kv)
- D Cartwright, A Dudzik, M Manjunath, Y Yao, [Embeddings and immersions of tropical curves](https://link.springer.com/article/10.1007/s13348-015-0149-8)
Collectanea mathematica 67, 1-19
	2016
## PhD Thesis

- A Dudzik , [Quantales and hyperstructures: Monads, mo'problems](https://arxiv.org/abs/1707.09227)
[arXiv:1707.09227](https://arxiv.org/abs/1707.09227) 2017 [PDF](https://arxiv.org/pdf/1707.09227)
- AJ Dudzik, [Quantales and hyperstructures](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=DdFjaEEAAAAJ&citation_for_view=DdFjaEEAAAAJ:UeHWp8X0CEIC)
University of California, Berkeley
	2016

## Other

- A Dudzik, [Tannaka-Krein Duality for Finite Groups](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=DdFjaEEAAAAJ&citation_for_view=DdFjaEEAAAAJ:qjMakFHDy7sC) 
2011


