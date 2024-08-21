---
layout: "page"
title: About
permalink: /about/
---

Welcome. Here are all the posts:


<ul>
{% for post in site.posts %}
    <li>
        <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
{% endfor %}
</ul>