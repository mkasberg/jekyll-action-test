---
---

Hello, world!

This is a test page!

{% assign date = '2020-04-13T10:20:00Z' %}

- Original date - {{ date }}
- With timeago filter - {{ date | timeago }}

**Posts**

{% for post in site.posts %}
* <a href="{{ post.url }}">{{ post.title }}</a>
{% endfor %}
