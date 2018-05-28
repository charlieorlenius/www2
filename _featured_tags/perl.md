---
layout: consultants
title: Konsulter med perl-kompetens
slug: perl
description: >
  Perl bla bla
accent_color: '#268bd2'
accent_image:
  background: '#202020'
  overlay:    false
---

<a href="/consultants/">Alla</a>{% for tag in site.featured_tags %}{% if tag.slug != page.slug %} / <a href="/tag/{{ tag.slug }}">{{ tag.slug }}</a>{% endif %}{% endfor %}
