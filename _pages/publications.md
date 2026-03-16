---
layout: page
permalink: /publications/
title: publications
description:  
nav: true
nav_order: 2
---

[Publications](#publications) | [Thesis](#thesis)

---

## publications

<div class="publications-wrapper">
  <div class="publications-main">
    <div class="publications">
      {% bibliography %}
    </div>
  </div>
</div>

[↑ Return to top](#top)

## thesis

<div class="publications-wrapper">
  <div class="publications-main">
    <div class="publications">
      {% bibliography -f thesis -q @* %}
    </div>
  </div>
</div>

[↑ Return to top](#top)

