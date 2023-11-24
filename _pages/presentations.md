---
layout: page
permalink: /presentations/
title: presentations
description: 
nav: true
nav_order: 3
---
<!-- _pages/presentations.md -->
<div class="publications">

{% bibliography -f {{ site.scholar.bibliography }} --query @*[paper=false] %}

</div>
