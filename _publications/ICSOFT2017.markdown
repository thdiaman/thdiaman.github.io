---
name: ICSOFT2017
date: 2017-07-01
type: conference
authors: Valasia Dimaridou, Alexandros-Charalampos Kyprianidis, Michail Papamichail, Themistoklis Diamantopoulos and Andreas L. Symeonidis
title: 'Towards Modeling the User-perceived Quality of Source Code using Static Analysis Metrics'
conference: 12th International Conference on Software Technologies (ICSOFT)
pages: 73-84
location: Madrid, Spain
preprint: https://issel.ee.auth.gr/wp-content/uploads/2017/08/ICSOFT.pdf
bibtex: ICSOFT2017.bib
---

Nowadays, software has to be designed and developed as fast as possible, while
maintaining quality standards. In this context, developers tend to adopt a
component-based software engineering approach, reusing own implementations and/or
resorting to third-party source code. This practice is in principle cost-effective,
however it may lead to low quality software products. Thus, measuring the quality of
software components is of vital importance. Several approaches that use code metrics
rely on the aid of experts for defining target quality scores and deriving metric
thresholds, leading to results that are highly context-dependent and subjective. In
this work, we build a mechanism that employs static analysis metrics extracted from
GitHub projects and defines a target quality score based on repositories' stars and
forks, which indicate their adoption/acceptance by the developers' community. Upon
removing outliers with a one-class classifier, we employ Principal Feature Analysis
and exam ine the semantics among metrics to provide an analysis on five axes for a
source code component: complexity, coupling, size, degree of inheritance, and quality
of documentation. Neural networks are used to estimate the final quality score given
metrics from all of these axes. Preliminary evaluation indicates that our approach
can effectively estimate software quality.
