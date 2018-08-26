---
layout: consultants
title: PMP-Certifierade konsulter
slug: PMP
description: >
  PMI-PMP är en av världens mest kända och välrenommerade certifieringen för projektledare. Här nedan kan du se vilka av våra konsulter som är certifierade Project Management Professionals av [Project Management Institute](https://www.pmi.org)
---

<ul class="tags">
<li class="tag"><a href="/consultants">{{ strings.all | default:"Alla" }}</a></li>
{% for tag in site.featured_tags %}{% if tag.slug != page.slug %} <li class="tag"><a href="/tag/{{ tag.slug }}">{{ tag.slug }}</a></li>{% endif %}{% endfor %}
</ul>
