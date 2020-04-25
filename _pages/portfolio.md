---
title: Portfolio
layout: collection
permalink: /portfolio/
collection: portfolio
entries_layout: grid
classes: wide
---


{{ content }}

<div class="entries-{{ page.entries_layout }}">
  {% include documents-collection.html collection=page.collection sort_by=page.sort_by sort_order=page.sort_order type=page.entries_layout %}
</div>
