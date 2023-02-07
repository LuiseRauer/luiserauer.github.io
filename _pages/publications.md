---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Peer-reviewed
------
* Rauer L, Reiger M, Bhattacharyya M, Brunner PM, Krueger JG, Guttman-Yassky E, Traidl-Hoffmann C, Neumann AU. [Skin microbiome and its association with host cofactors in determining atopic dermatitis severity](https://onlinelibrary.wiley.com/doi/10.1111/jdv.18776). J Eur Acad Dermatol Venereol. 2022 Nov 25. doi: 10.1111/jdv.18776. Epub ahead of print. PMID: 36433676.

Blog posts
------
* Rauer L. [Microbiome (k)nights](https://www.open-bio.org/2022/12/29/microbiome-knights/). OpenBio. https://www.open-bio.org/2022/12/29/microbiome-knights/.
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
