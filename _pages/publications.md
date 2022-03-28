---
layout: page
permalink: /publications/
title: Publications
description: Selected papers in journals and books    
comment: Selected papers in journals and books. See also <a href="https://scholar.google.com/citations?user=YRGc9WwAAAAJ&hl=en">Google Scholar</a>, <a href="https://arxiv.org/a/lucero_j_1.html">arXiv</a>, <a href="https://www.ncbi.nlm.nih.gov/myncbi/jorge%20carlos.lucero.1/bibliography/public/">PubMed</a>, <a href="https://publons.com/researcher/2897674/jorge-c-lucero/">publons</a>
nav: true
---
<!-- _pages/publications.md -->

<div class="publications">

{%- for y in (1993..2022) reversed %}
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
