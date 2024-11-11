---
layout: page
permalink: /publications/
title: publications
description: journal papers, conference papers, patents and thesis'.
nav: true
nav_order: 3
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

# Journal papers

<div class="publications">
  {% bibliography --query @*[category_journal=true]* %}
</div>


# Conference papers

<div class="publications">
  {% bibliography --query @*[category_conference=true]* %}
</div>



