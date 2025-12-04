---
layout: test
permalink: /test/
title: Test
body:
  - { name: "test1", description: "test1" }
  - { name: "test2", description: "test2" }
---

{%-  for item in page.body -%}
    {{ item.name }}
{%- endfor -%}
