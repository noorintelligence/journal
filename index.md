---
layout: default
title: Field Notes & Build Log
---

# 🛠️ Field Notes & Daily Ship Log

Public record of daily technical builds, architectural decisions, model evaluation experiments, and technical privacy tools.

---

{% for post in site.posts %}
<div class="post-card">
  <div class="post-meta">{{ post.date | date: "%B %d, %Y" }}</div>
  <h2><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h2>
  <p>{{ post.content | strip_html | truncatewords: 30 }}</p>
</div>
{% endfor %}
