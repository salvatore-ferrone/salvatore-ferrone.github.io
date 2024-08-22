---
layout: "page"
title: About
permalink: /about/
---

Welcome. One day, I may have many posts here. For now, here is a link to a great collection of human knowledge: [wikipedia](https://wikipedia.org)


<ul>
{% for post in site.posts %}
    <li>
        <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
{% endfor %}
</ul>