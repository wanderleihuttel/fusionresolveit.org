---
layout: page
lang: en
title: List of CVE
---

{% include nav.html %}

<ul>
  {% for cve in site.data.sitetext[page.lang].cve.list %}
    <li style="list-style-type: none;">
      <span style="font-size: 12px; color: grey;"><i>The {{ cve.date  | date: "%-d %B %Y" }}</i></span>
      <h2><a href="{{ cve.link }}"><i class="fas fa-sign-in-alt text-primary"></i> {{ cve.cve }}</a></h2>
    </li>
  {% endfor %}
</ul>
{% if site.data.sitetext[page.lang].cve.list == False %}
  {{ site.data.sitetext[page.lang].cve.nocve }}
{% endif %}
