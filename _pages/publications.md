---
layout: page
permalink: /publications/
title: publications and preliminary results
description:
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

{% bibliography -f {{ site.scholar.bibliography }} --query @*[paper=true] %}
<!-- {% bibliography -f {{ site.scholar.bibliography }} -q @[paper=true] %} -->

</div>
