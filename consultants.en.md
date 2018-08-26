---
layout: consultants
title: Our consultants
menutitle: Our consultants
heading: Our consultants
show_collection: consultants
description: >
  Here are all consultants at Konsultkooperativets, please read more about our experienced, professional and competent consultants. Click on the different compence links to filter the list.listan
menu: true
order: 2
lang: en
permalink: /consultants
---

<ul class="tags">
<li class="tag"><a href="/consultants">{{ strings.all | default:"All" }}</a></li>
{% for tag in site.featured_tags %} <li class="tag"><a href="/tag/{{ tag.slug }}">{{ tag.slug }}</a></li>{% endfor %}
</ul>
