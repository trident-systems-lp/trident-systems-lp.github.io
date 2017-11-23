---
layout: page
title: "News"
permalink: "/news/"
header: no
subheadline: "See where we have appeared in the media and our achievements."
---
{% for post in site.catergories.design %}
    <div class="row">
        <div class="small-1 column">
            <p>image</p>
        </div>
        <div class="small-12 column">
            <h5>{{ post.subheadline }}</h5>
            <p>{{ post.title }}</p>
            <p>{{ post.teaser }}</p>
            <p><a class="button tiny radius" href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ site.data.language.more }}</a></p>
        </div>
    </div>
{% endfor %}
