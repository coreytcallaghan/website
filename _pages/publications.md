---
title: "Publications"
layout: gridlay
sitemap: false
permalink: /publications/
years: [2016, 2017, 2018, 2019, 2020, 2021, 2022]
---

<style>
.jumbotron{
    padding:3%;
    padding-bottom:10px;
    padding-top:10px;
    margin-top:10px;
    margin-bottom:30px;
}
</style>

<div class="jumbotron">
### Peer-reviewed articles
{% bibliography --query @article %}
</div>

<div class="jumbotron">
### Book chapters
{% bibliography --query @inproceedings %}
</div>

<div class="jumbotron">
### Other publications
{% bibliography --query @report %}
</div>
