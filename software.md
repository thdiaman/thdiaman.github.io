---
layout: page
title: Software
permalink: /software/
---

{% assign tools = site.software | sort: 'order' %}

<div class="row">
  {% for tool in tools %}
    <div class="col-md-4 col-lg-4 col-sm-6 col-xs-12">
      <a href="{{ tool.name }}"><img class="aligncenter" src="{{ tool.image }}" style="height: 120px;"/></a>
      <h2><a href="{{ tool.name }}">{{ tool.name }}</a></h2>
      <p>{{ tool.description }}</p>
      <a href="{{ tool.name }}">Learn more</a>
      <br/><br/>
    </div>
  {% endfor %}
</div>


