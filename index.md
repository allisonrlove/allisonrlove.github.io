---
title: Allison Love
layout: base
date: 2024-12-02
---

{% include layout/profile-intro.html %}

{% assign home_cards = site.pages | where: "homepage", true %}
{% include cards/card-grid.html cards=home_cards grid-class="home-cards" show-tags=false heading-level=2 %}
