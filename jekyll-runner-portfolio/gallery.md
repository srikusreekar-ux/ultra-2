---
layout: default
title: Gallery
---

# Gallery

{% for img in site.static_files %}
  {% if img.path contains '/assets/images/gallery/' %}
  ![]({{ img.path }})
  {% endif %}
{% endfor %}
