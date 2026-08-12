# 🛠️ Field Notes & Daily Ship Log

Public record of daily technical builds, architectural decisions, model evaluation experiments, and technical privacy tools.

---

### 📚 Published Builds

{% for post in site.posts %}
- **[{{ post.date | date: "%b %d, %Y" }}]** [{{ post.title }}]({{ post.url | relative_url }})
{% endfor %}
