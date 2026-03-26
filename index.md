---
layout: default
title: Home
---

# Wilkommen auf unserem Reiseblog

Wir dokumentieren hier unsere Reisen und Abenteuer in der Natur.

## Beiträge

<ul>
    {% for post in site.posts %}
        <li>
            <a href="{{ post.url }}">{{ post.title }}</a>
            ({{ post.date | date: "%d.%m.%Y" }})
        </li>
    {% endfor %}
</ul>
