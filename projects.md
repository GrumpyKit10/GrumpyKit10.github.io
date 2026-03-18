---
layout: default
title: My Projects
---
<h1>My GitHub Projects</h1>

<ul>
  {% for repo in site.github.public_repositories %}
    <li>
      <a href="{{ repo.html_url }}">{{ repo.name }}</a><br>
      <small>{{ repo.description }}</small>
    </li>
  {% endfor %}
</ul>
