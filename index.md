---
title: Home
layout: home
nav_order: 1
---

# Welcome to My Tech Notes

Hi! I'm Yash. This is where I document my technical learnings, useful scripts, and daily discoveries in software engineering.

## What you'll find here:
- Daily learnings from my software engineering work
- Useful automation scripts and tools
- Technical solutions and tips

## Recent Posts

{% for post in site.posts %}
  - [{{ post.title }}]({{ post.url }})
{% endfor %}
