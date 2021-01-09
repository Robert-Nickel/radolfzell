---
layout: default
---

{% for post in site.posts %}
# {{ post.title }}
{% for answer in post.answers %}
## [{{ answer.text }}]({{ answer.link }})
{% endfor %}
{% endfor %}