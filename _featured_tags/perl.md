---
layout: consultants
title: Konsulter med perl-kompetens
slug: perl
description: >
  Perl bla bla
---

<a href="/consultants/">Alla</a>{% for tag in site.featured_tags %}{% if tag.slug != page.slug %} / <a href="/tag/{{ tag.slug }}">{{ tag.slug }}</a>{% endif %}{% endfor %}
