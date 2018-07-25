---
layout: page
title: Publications
permalink: /publications/
---

<h1>Journal Articles</h1>
{% assign journals = site.publications | where: "type" , "journal" | sort: 'date' | reverse %}
{% for pub in journals %}
  {% include publication.html %}
{% endfor %}

<h1>Book Chapters</h1>
{% assign bookchapters = site.publications | where: "type" , "bookchapter" | sort: 'date' | reverse %}
{% for pub in bookchapters %}
  {% include publication.html %}
{% endfor %}

<h1>Conference Papers</h1>
{% assign conferences = site.publications | where: "type" , "conference" | sort: 'date' | reverse %}
{% for pub in conferences %}
  {% include publication.html %}
{% endfor %}
