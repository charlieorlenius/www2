---
layout: consultants
title: Våra konsulter
menutitle: Våra konsulter
heading: Våra konsulter
show_collection: consultants
description: >
  Här ser du Konsultkooperativets alla konsultprofiler, läs gärna mer om våra erfarna, professionella och kompetenta konsulter. Klicka på de olika kompetenslänkarna för att filtrera listan
menu: true
order: 2
lang: sv
permalink: /consultants
---

<ul class="tags">
<li class="tag"><a href="/consultants">{{ strings.all | default:"Alla" }}</a></li>
{% for tag in site.featured_tags %} <li class="tag"><a href="/tag/{{ tag.slug }}">{{ tag.slug }}</a></li>{% endfor %}
</ul>