---
title: "Inject Less, Recover More: Unlocking the Potential of Document Recovery in Injection Attacks Against SSE"
collection: publications
permalink: /publication/2024-02-03-paper-title-number-1
excerpt: ''
date: 2024-02-03
venue: 'IEEE CSF (A conference)'
paperurl: 'https://eprint.iacr.org/2024/515'
citation: ''
---

Searchable symmetric encryption has been vulnerable to inference attacks that rely on uniqueness in leakage patterns. However, many keywords in datasets lack distinctive leakage patterns, limiting the effectiveness of such attacks. The file injection attacks, initially proposed by Cash et al. (CCS 2015), have shown impressive performance with 100\% accuracy and no prior knowledge requirement. Nevertheless, this attack fails to recover queries with underlying keywords not present in the injected files. To address these limitations, our research introduces a novel attack strategy called LEAP-Hierarchical Fusion Attack (LHFA) that combines the strengths of both file injection attacks and inference attacks. Before initiating keyword injection, we introduce a new approach for inert/active keyword selection. In the phase of selecting injected keywords, we focus on keywords without unique leakage patterns and recover them, leveraging their presence for document recovery. Our goal is to achieve an amplified effect in query recovery. We demonstrate a minimum query recovery rate of 1.3 queries per injected keyword with a 10\% data leakage of a real-life dataset, and initiate further research to overcome challenges associated with non-distinctive keywords.
