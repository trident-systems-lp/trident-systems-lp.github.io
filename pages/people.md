---
layout: page
title: "Our People"
permalink: "/about-us/people/"
---

{% for group in site.data.groups %}
## Our {{ group.name }}
{% if group.teaser %}{{ group.teaser }}{% endif %}
<div class="people" id="{{ group.name }}">
    {% for person in group.people %}
    <div class="person">
    <img src="{{ site.urlimg }}people/{{ person.img }}">
    {% capture caption %}{{person.name}}{% if person.role %} ({{ person.role }}){% endif %}{% endcapture %}
    <p>{% if person.url %}<a href="{{ site.baseurl }}{{ person.url }}">{{ caption }}</a>{% else %}{{ caption }}{% endif %}</p>
    </div>
    {% endfor %}
</div>
{% endfor %}
