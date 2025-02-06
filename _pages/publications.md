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

## Published Research

- S. Hazratpour and E. Riehl, A 2-categorical proof of Frobenius for fibrations defined from a generic point, [Mathematical Structures in Computer Science](https://www.cambridge.org/core/journals/mathematical-structures-in-computer-science/article/2categorical-proof-of-frobenius-for-fibrations-defined-from-a-generic-point/8A9A180160D0833C108E51B0B5D1E6F2), Published online 2024:1-23,  [arXiv:2210.00078](https://arxiv.org/abs/2210.00078)
- N. Kudasov, E. Riehl, and J. Weinberger, Formalizing the &infin;-categorical Yoneda lemma,
[CPP 2024: Proceedings of the 13th ACM SIGPLAN International Conference on Certified Programs and Proofs](https://dl.acm.org/doi/10.1145/3636501.3636945), 274-290, [arXiv:2309.08340](https://arxiv.org/abs/2309.08340)
- P. Hackney, V. Ozornova, E. Riehl, and M. Rovelli, [Pushouts of Dwyer maps are (&infin;,1)-categorical](https://msp.org/agt/2024/24-4/p11.xhtml),
Algebraic &amp; Geometric Topology 24-4 (2024), 2171--2183. [arXiv:2205.02353](https://arxiv.org/abs/2205.02353)
- P. Hackney, V. Ozornova, E. Riehl, M. Rovelli, An (&infin;, 2)-categorical pasting theorem, Trans. Amer. Math. Soc. 376 (2023), 555–597, [arXiv:2106.03660](https://arxiv.org/abs/2106.03660)
- E. Riehl and M. Wattal, [On &infin;-cosmoi of bicategories](https://emilyriehl.github.io/files/bicategories.pdf), La Matematica 1, (2022), 740–764, [arXiv:2108.11786](https://arxiv.org/abs/2108.11786)

- O Vinyals, I Babuschkin, WM Czarnecki, M Mathieu, A Dudzik, J Chung, ..., [Grandmaster level in StarCraft II using multi-agent reinforcement learning](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=DdFjaEEAAAAJ&citation_for_view=DdFjaEEAAAAJ:u5HHmVD_uO8C)
Nature 575 (7782), 350-354
5053	2019
- O Vinyals, I Babuschkin, J Chung, M Mathieu, M Jaderberg, ..., Alphastar: Mastering the real-time strategy game starcraft ii
DeepMind blog 2, 20
574	2019
- J Abramson, A Ahuja, I Barr, A Brussee, F Carnevale, M Cassin, ..., Imitating interactive intelligence

arXiv preprint arXiv:2012.05672
74	2020
- B Ibarz, V Kurin, G Papamakarios, K Nikiforou, M Bennani, R Csordás, ..., A generalist neural algorithmic learner

Learning on graphs conference, 2: 1-2: 23
71	2022
- AJ Dudzik, P Veličković, Graph neural networks are dynamic programmers

Advances in neural information processing systems 35, 20635-20647
70	2022
- D Cartwright, A Dudzik, M Manjunath, Y Yao, Embeddings and immersions of tropical curves

Collectanea mathematica 67, 1-19
25	2016
- B Gavranović, P Lessard, A Dudzik, T von Glehn, JGM Araújo, ..., Categorical deep learning: An algebraic theory of architectures

arXiv preprint arXiv:2402.15332
12	2024
- AJ Dudzik, T von Glehn, R Pascanu, P Veličković, Asynchronous algorithmic alignment with cocycles

Learning on Graphs Conference, 3: 1-3: 17
10	2024
- W Bounsi, B Ibarz, A Dudzik, JB Hamrick, L Markeeva, A Vitvitskyi, ..., Transformers meet Neural Algorithmic Reasoners

arXiv preprint arXiv:2406.09308
7	2024
- B Gavranović, P Lessard, AJ Dudzik, T von Glehn, JGM Araújo, ..., Position: Categorical Deep Learning is an Algebraic Theory of All Architectures

Forty-first International Conference on Machine Learning
7	
- A Dudzik , Quantales and hyperstructures: Monads, mo'problems

arXiv preprint arXiv:1707.09227
5	2017
- AJ Dudzik, Quantales and hyperstructures

University of California, Berkeley
2	2016
- P Monteagudo-Lago, A Rosinski, AJ Dudzik, P Veličković, Asynchrony Invariance Loss Functions for Graph Neural Networks

ICML 2024 Workshop on Geometry-grounded Representation Learning and …
2024
- A DUDZIK, TANNAKA-KREIN DUALITY FOR FINITE GROUPS

2011


