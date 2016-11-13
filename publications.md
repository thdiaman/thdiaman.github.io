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


<h1>Conference Papers</h1>
{% assign conferences = site.publications | where: "type" , "conference" | sort: 'date' | reverse %}
{% for pub in conferences %}
{% include publication.html %}
{% endfor %}



<!--
{% for publication in site.data.publications reversed %}
  {% assign pub = publication[1] %}
  {% if pub.type == "journal" %}
  <p>
    {{ pub.text }}<br/>
    {% if pub.abstract %}
      <style> input#cb{{ pub.id }}:checked ~ span#abs{{ pub.id }} { display:block; } </style>
      <label id="abstract" for="cb{{ pub.id }}">Abstract</label><input type="checkbox" id="cb{{ pub.id }}">
    {% endif %}
    |
    {% if pub.bibtex %}
      <a href="{{ pub.bibtex }}">Bibtex</a>
    {% endif %}
    {% if pub.abstract %}
      <span id="abs{{ pub.id }}">{{ pub.abstract }}</span>
    {% endif %}
  </p>
  {% endif %}
{% endfor %}



<h1>Journal Articles</h1>
Christoforos Zolotas, Themistoklis Diamantopoulos, Kyriakos Chatzidimitriou and Andreas Symeonidis "From requirements to source code: a Model-Driven Engineering approach for RESTful web services", Automated Software Engineering, pp. 1--48, September 2016<br/>
<a href="ASE2016.bib">Bibtex</a> | <a href="ASE2016.txt">Abstract</a> | <a href="http://issel.ee.auth.gr/wp-content/uploads/2016/09/ReqsToCodeMDE.pdf">Preprint</a>

Themistoklis Diamantopoulos and Andreas Symeonidis, "Localizing Software Bugs using the Edit Distance of Call Traces", International Journal On Advances in Software, 7, (1), pp. 277--288, October 2014<br/>
<a href="IJAS2014.bib">Bibtex</a> | <a href="IJAS2014.txt">Abstract</a> | <a href="http://www.thinkmind.org/download.php?articleid=soft_v7_n12_2014_22">Preprint</a>


<h1>Conference Papers</h1>

Michail Papamichail, Themistoklis Diamantopoulos and Andreas L. Symeonidis, "User-Perceived Source Code Quality Estimation based on Static Analysis Metrics", 2016 IEEE International Conference on Software Quality, Reliability and Security (QRS), Vienna, Austria, August 2016<br/>
<a href="QRS2016.bib">Bibtex</a> | <a href="QRS2016.txt">Abstract</a> | <a href="http://ieeexplore.ieee.org/document/7589790/">Preprint</a>
	
Themistoklis Diamantopoulos, Klearchos Thomopoulos and Andreas L. Symeonidis, "QualBoa: Reusability-aware Recommendations of Source Code Components", IEEE/ACM 13th Working Conference on Mining Software Repositories (MSR), pp. 488-491, Texas, USA, May 2016<br/>
<a href="">Bibtex</a> | <a href="">Abstract</a> | <a href="">Preprint</a>

Themistoklis Diamantopoulos, Antonis Noutsos and Andreas L. Symeonidis, "DP-CORE: A Design Pattern Detection Tool for Code Reuse", 6th International Symposium on Business Modeling and Software Design (BMSD), pp. 160-169, Rhodes, Greece, June 2016<br/>
<a href="">Bibtex</a> | <a href="">Abstract</a> | <a href="">Preprint</a>
-->
