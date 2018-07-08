---
#
# See the Github wiki for how to edit content on this page and markdown styles you can use:
# link here
#
# Title and Description display on page and in meta
title: Related guides
description: Activity-specific guides to help you throughout the service lifecycle.
#
# Don't edit items below - they control the page layout
layout: page
page-type: subpage
page-description: yes
sidebar-type: /service-design
permalink: /service-design/related/index.html
#
---

{% for item in site.data.navigation %}

  {% for subitem in item.subitems %}

    {% if subitem.title == "Related guides" %}

      {% for section in subitem.tertitems %}

        {% if section.target == true %}

* <a title="{{ section.title }}" href="{{ section.linkto}}" target="_blank">{{ section.title }}</a>
  {{ section.description }}

        {% else %}

* [{{ section.title }}]({{ section.linkto  | relative_url }})
  {{ section.description }}

        {% endif %}

      {% endfor %}

    {% endif %}

  {% endfor %}

{% endfor %}


<hr>

<a href="#">Return to top</a>
