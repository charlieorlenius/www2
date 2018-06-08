---
layout: page
title: Konsultkooperativet - member owned consultant company in Gothenburg
menutitle: Hem
heading: Konsultkooperativet<br><small>fria teknik- och managementkonsulter</small>
description: Cooperative consultant company and broker for freelancing cosultants. Owned and controlled equally by its members.
lang: en
permalink: /
---

![Full-width image](assets/img/samverkan07.jpg){:.lead}

# Sweden's first cooperative* for self-employed consultants

Konsultkooperativet is an honest, democratic and open cooperative for freelancing technology and management consultants. We welcome all consultants who want real power to change, who are tired of brokers who charges too much, and of partnership companies, where all are not treated equal. Konsultkooperativet does not have any majority owners, or unfair terms - you are welcome to check our [by-laws](/stadgar.pdf)!

Sounds interesting? [Contact us](mailto:konsult@konsult.coop) to apply for membership.

(*) According to the definition by the International Cooperative Alliance (ICA)

## Latest blog posts
{% for post in site.posts limit:5 %}
  {% assign currentdate = post.date | date:list_group_by %}
  {% if currentdate != date %}
    {% unless forloop.first %}</ul>{% endunless %}
    <h2 id="{{ list_group_by | slugify }}-{{ currentdate | slugify }}" class="hr">{{ currentdate }}</h2>
    <ul class="related-posts">
    {% assign date = currentdate %}
  {% endif %}
  {% include post-list-item.html post=post format=list_entry %}
  {% if forloop.last %}</ul>{% endif %}
{% endfor %}


# Cooperative consultant broker
Konsultkooperativet can be seen as a consultant broker not acting for profit. The cooperative's main target is to make sure all members have assignments, by acting as a broker. The cooperative aims at signing contracts directly with end customers, when possible without involvement of external brokers.

# What happens with the organisation's profit?
Konsultkooperativet brokes [assignments](/konsultuppdrag) to its member companies. For this service the organisation charges a commision fee based on invoiced hours. The profit the organisation makes is paid back to the member companies pro rata the member's revenue through the organisation. To qualify for pay back of commision fees, the member must have been a member for at least one year, and also have paid a stake to the organisation. After the pay back, the goal for the organisation is to have a commisson level of less than 6%.
According to the organisation's by-laws, the organisation should make zero profit.

# Why cooperative instead of a limited company?
Konsultkooperativet is an "ekonomisk förening", this type of organisation was chosen since it makes it simple to secure equality, democracy and transparency. In an "ekonomisk förening" every memeber has one vote each. A member can never get more power over the organisation than anyone else.
In most aspects (e.g. taxeation), an "ekonomisk förening" is equal to a limited company.

# Membership benfits
As a memebr of Konsultkooperativet you will get access to our network. The organisation also manages team building events and conferences as required by the memebers. The organisation also maanges invoicing and contracts for the assignments.
Konsultkooperativet also has common insurances and administrative systems. The insurance covers, e.g., liabilities for advices given by consultants. [Read more on membership benefits here](/members/).
