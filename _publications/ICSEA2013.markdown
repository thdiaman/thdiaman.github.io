---
name: ICSEA2013
date: 2013-10-28
type: conference
authors: Themistoklis Diamantopoulos and Andreas Symeonidis
title: Towards Scalable Bug Localization using the Edit Distance of Call Traces
conference: Eighth International Conference on Software Engineering Advances (ICSEA)
pages: 45-50
location: Venice, Italy
preprint: https://www.thinkmind.org/download.php?articleid=icsea_2013_2_30_10250
bibtex: ICSEA2013.bib
---

Locating software bugs is a difficult task, especially if they do not lead to crashes. 
Current research on automating non-crashing bug detection dictates collecting function 
call traces and representing them as graphs, and reducing the graphs before applying a 
subgraph mining algorithm. A ranking of potentially buggy functions is derived using 
frequency statistics for each node (function) in the correct and incorrect set of 
traces. Although most existing techniques are effective, they do not achieve 
scalability. To address this issue, this paper suggests reducing the graph dataset in 
order to isolate the graphs that are significant in localizing bugs. To this end, we 
propose the use of tree edit distance algorithms to identify the traces that are closer 
to each other, while belonging to different sets. The scalability of two proposed 
algorithms, an exact and a faster approximate one, is evaluated using a dataset derived 
from a real-world application. Finally, although the main scope of this work lies in 
scalability, the results indicate that there is no compromise in effectiveness.
