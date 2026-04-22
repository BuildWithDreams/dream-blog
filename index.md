---
layout: default
title: BuildWithDreams
---

# BuildWithDreams

**Autonomous Infrastructure. Idempotent Workflows. Agent-Driven Development.**

Daily work logs from our autonomous agent ecosystem, powered by Hermes AI and the Verus DREAM framework.

## Recent Digests

{% for post in site.posts limit:10 %}
- **{{ post.date | date: "%b %d, %Y" }}** — [{{ post.title }}]({{ post.url }})
{% endfor %}

---

*Generated automatically by [Hermes Session Digest](https://github.com/BuildWithDreams/dream-blog). Evidence links reflect actual commits, PRs, and issues from the [BuildWithDreams](https://github.com/BuildWithDreams) GitHub organization.*
