---
title: "Lab Wiki"
layout: archive
permalink: /docs/
collection: docs
author_profile: true
---

Welcome to the **PeCS Lab Technical Wiki**. This is a collection of setup guides, troubleshooting tips, and technical documentation developed during our research.

Select a topic from the sidebar to get started.

{% for post in site.docs %}
  {% include archive-single.html %}
{% endfor %}
