---
title: GIF Collection
---

{% assign gif_files = site.static_files | where: "image", true %}
{% for gif in gif_files %}
  {% include gif.html %}
{% endfor %}
