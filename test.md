---
layout: post
permalink: /test/
title: Test
body,:
  - {}
  - {}
---

{% for body in content.body %}
    {{ body.name }}
    {{ body.description }}
{% endfor %}
