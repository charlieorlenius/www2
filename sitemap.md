---
layout:
permalink: /sitemap.xml
---
<?xml version="1.0" encoding="UTF-8"?>
<urlset xmlns="http://www.sitemaps.org/schemas/sitemap/0.9" xmlns:xhtml="http://www.w3.org/1999/xhtml">
  {% for post in site.posts %}
    {% if post.url contains "404" %}{% else %}
      <url>
        <loc>{{site.url}}{{ post.url }}</loc>
        {% for version in site.languages %}
          {% if version == site.default_lang %}
            <xhtml:link rel="alternate" hreflang="{{ version }}" href="{{site.url}}{{ post.url }}" />
          {% else %}
            <xhtml:link rel="alternate" hreflang="{{ version }}" href="{{site.url}}/{{ version }}{{ post.url }}" />
          {% endif %}
        {% endfor %}
        <lastmod>{{ post.date | date_to_xmlschema }}</lastmod>
        <changefreq>weekly</changefreq>
      </url>
    {% endif %}
  {% endfor %}
  {% for page in site.pages %}
    {% if page.url contains "404" or page.url contains "/assets/" or page.url contains "sitemap" %}{% else %}
      <url>
        <loc>{{site.url}}{{ page.url }}</loc>
        {% for version in site.languages %}
          {% if version == site.default_lang %}
            <xhtml:link rel="alternate" hreflang="{{ version }}" href="{{site.url}}{{ page.url }}" />
          {% else %}
            <xhtml:link rel="alternate" hreflang="{{ version }}" href="{{site.url}}/{{ version }}{{ page.url }}" />
          {% endif %}
        {% endfor %}
        <changefreq>weekly</changefreq>
      </url>
    {% endif %}
  {% endfor %}
</urlset>