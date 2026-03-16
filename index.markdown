---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults


layout: default
title: Melina Parker Portfolio
---
[Home](/) | [About](/about/) | [Posts](/#posts)

# Melina Parker

Welcome to my portfolio.

## Posts

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%Y-%m-%d" }}
{% endfor %}