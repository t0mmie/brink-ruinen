---
layout: post
permalink: /test/
title: Test
---

{% for body in content.body %}
    {{ body.name }}
    {{ body.description }}
{% endfor %}