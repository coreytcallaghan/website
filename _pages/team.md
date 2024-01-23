---
title: "Team"
layout: teams
sitemap: false
permalink: /team/
---


{% for team_member in site.data.team_members %}
## {{ team_member.name }}

<div class="team-member">
  <img src="{{ team_member.image }}" alt="{{ team_member.name }}">
  <div>
    <strong>{{ team_member.position }}</strong>
    <p>
      {{ team_member.description }}
    </p>
    <p>
      <a href="{{ team_member.github }}">GitHub</a> |
      <a href="{{ team_member.inaturalist }}">iNaturalist</a>
    </p>
  </div>
</div>
{% endfor %}

{% comment %}Alumni Members{% endcomment %}
{% for alumni_member in site.data.alumni_members %}
## {{ alumni_member.name }}

<div class="alumni-member">
  <img src="{{ alumni_member.image }}" alt="{{ alumni_member.name }}">
  <div>
    <strong>{{ alumni_member.position }}</strong>
    <p>
      {{ alumni_member.description }}
    </p>
  </div>
</div>
{% endfor %}

