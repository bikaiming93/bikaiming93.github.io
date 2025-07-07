# /teams/index.md
---
layout: default
title: Meet the Lab
permalink: /Teams/
---

Welcome to our Lab!

<section class="team-overview">
  {% assign members = page.members | default: site.data.team %}
  {% for member in members %}
    <div class="team-member">
      <!-- same HTML for photo, name, bio, etc. -->
    </div>
  {% endfor %}
</section>
