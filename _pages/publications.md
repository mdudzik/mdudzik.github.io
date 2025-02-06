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




