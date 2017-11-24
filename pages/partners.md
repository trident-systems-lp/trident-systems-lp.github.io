---
layout: page
title: "Our Industry Partners"
permalink: "/about-us/partners/"
---
The Limited Partners in the Trident Systems Limited Partnership are quota owners representing a significant proportion of quota in inshore finfish and deepwater tier 2 stocks:

{% for partner in site.data.partners %}
+ [{{ partner.name }}]({{ partner.url }})
{% endfor %}
