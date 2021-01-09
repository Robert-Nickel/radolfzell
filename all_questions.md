---
layout: default
---

{% for post in site.posts %}
    <h1>{{ post.title }}</h1>
    {% for answer in post.answers %}
    <h2><a href="{{ answer.link }}">{{ answer.text }}</a></h2>
    {% endfor %}
{% endfor %}