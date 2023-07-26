---
title: "Team"
layout: teams
sitemap: false
permalink: /team/
---

## Current Team 

{% for team_member in site.data.team_members %}
<div class="team-member">
  <img src="{{ team_member.image }}" alt="{{ team_member.name }}">
  <div class="team-member-info">
    <h3>{{ team_member.name }}</h3>
    <h5>{{ team_member.position }}</h5>
    <p>{{ team_member.description }}</p>
    <div class="team-member-links">
      <a href="{{ team_member.github }}">GitHub</a>
      <a href="{{ team_member.inaturalist }}">iNaturalist</a>
    </div>
  </div>
</div>
{% endfor %}

## Alumni

{% for alumni_member in site.data.alumni_members %}
<div class="team-member alumni">
  <img src="{{ alumni_member.image }}" alt="{{ alumni_member.name }}">
  <div class="team-member-info">
    <h3>{{ alumni_member.name }}</h3>
    <h5>{{ alumni_member.position }}</h5>
    <p>{{ alumni_member.description }}</p>
    <div class="team-member-links">
      <a href="{{ alumni_member.github }}">GitHub</a>
      <a href="{{ alumni_member.inaturalist }}">iNaturalist</a>
    </div>
  </div>
</div>
{% endfor %}
