---
layout: page
permalink: /repositories/
title: Repositories
description: Research code and computational projects.
nav: true
nav_order: 3
---

## Research Code

<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for repo in site.data.repositories.github_repos %}
    {% include repository/repo.liquid repository=repo %}
  {% endfor %}
</div>
