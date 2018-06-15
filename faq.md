---
layout: page
permalink: "/faq/"
path: "faq"
css: "article2"
title: "FAQ"
---
## Questions
{% for item in site.data.faq -%}
- [{{ item.question }}](#faq{{ forloop.index }})
{% endfor %}
---
{% for item in site.data.faq %}
## {{ item.question }} {#faq{{ forloop.index }}}
{{ item.answer }}
{% endfor %}