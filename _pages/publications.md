---
layout: page
permalink: /publications/
title: Publications
description: 
nav: true
nav_order: 2
class: hide-title
---
<p>The publications are grouped into two sections: conference and journal papers.
<br> * Denotes Equal Contribution</p>

<!-- Main Publications Section -->
<div class="section-title">
  Conference Publications
</div>

<div class="publications">
  {% bibliography --group_by none --query @*[keyword=conference]* %}
</div>

<div class="section-title">
  Journal Publications
</div>

<div class="publications">
   {% bibliography --group_by none --query @*[keyword=journal]* %}
</div>
