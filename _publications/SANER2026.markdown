---
name: SANER2026
date: 2026-03-19
type: conference
authors: Themistoklis Diamantopoulos, Dimosthenis Natsos, and Andreas Symeonidis
title: 'Towards Online Malware Detection using Process Resource Utilization Metrics'
conference: 33rd IEEE International Conference on Software Analysis, Evolution and Reengineering (SANER)
pages: 1-6
location: Limassol, Cyprus
bibtex: SANER2026.bib
preprint: https://arxiv.org/pdf/2601.10164v1
code: https://github.com/AuthEceSoftEng/online-malware-detection
---

The rapid growth of Cloud Computing and Internet of Things (IoT) has significantly increased the
interconnection of computational resources, creating an environment where malicious software
(malware) can spread rapidly. To address this challenge, researchers are increasingly utilizing
Machine Learning approaches to identify malware through behavioral (i.e. dynamic) cues. However,
current approaches are limited by their reliance on large labeled datasets, fixed model training,
and the assumption that a trained model remains effective over timedisregarding the ever-evolving
sophistication of malware. As a result, they often fail to detect evolving malware attacks that
adapt over time. This paper proposes an online learning approach for dynamic malware detection,
that overcomes these limitations by incorporating temporal information to continuously update its
models using behavioral features, specifically process resource utilization metrics. By doing so,
the proposed models can incrementally adapt to emerging threats and detect zeroday malware
effectively. Upon evaluating our approach against traditional batch algorithms, we find it
effective in detecting zero-day malware. Moreover, we demonstrate its efficacy in scenarios with
limited data availability, where traditional batchbased approaches often struggle to perform
reliably.
