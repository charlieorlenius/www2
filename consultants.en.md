---
layout: consultants
title: Our consultants
menutitle: Our consultants
heading: Our consultants
show_collection: consultants
description: >
  Here are all consultants at Konsultkooperativets, please read more about our experienced, professional and competent consultants. Click on the different compence links to filter the list.listan
menu: true
order: 3
lang: en
permalink: /consultants
---

<a href="/consultants">All</a>&nbsp;{% for tag in site.featured_tags %} / <a href="/tag/{{ tag.slug }}">{{ tag.slug }}</a>{% endfor %}
