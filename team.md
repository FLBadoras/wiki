---
title: Team
layout: default
permalink: /team
nav_order: 3
---

# Alle Teammitglieder
{% for team_member in site.team_members %}
  <h2>{{ team_member.name }} - {{ team_member.position }}</h2>
  <p>{{ team_member.content | markdownify }}</p>
{% endfor %}
