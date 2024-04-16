---
title: "Query Recovery from Easy to Hard: Jigsaw Attack against SSE"
collection: publications
permalink: /publication/2024-02-02-paper-title-number-3
excerpt: ''
date: 2024-02-02
venue: 'USENIX Security (A* conference)'
paperurl: 'https://arxiv.org/abs/2403.01155'
citation: ''
---

Searchable symmetric encryption schemes often unintentionally disclose certain sensitive information, such as access, volume, and search patterns. Attackers can exploit such leakages and other available knowledge related to the user's database to recover queries. We find that the effectiveness of query recovery attacks depends on the volume or frequency distribution of keywords. Queries containing keywords with high volumes or frequencies are more susceptible to recovery, even when countermeasures are implemented. Attackers can also effectively leverage these "special" queries to recover all others.
By exploiting the above finding, we propose a Jigsaw attack that begins by accurately identifying and recovering those distinctive queries. Leveraging the volume, frequency, and co-occurrence information, our attack achieves 90\% accuracy in three tested datasets, which is comparable to previous attacks (Oya et al., USENIX22 and Damie et al., USENIX21). With the same runtime, our attack demonstrates an advantage over the attack proposed by Oya et al (approximately 15\% more accuracy when the keyword universe size is 15k). Furthermore, our proposed attack outperforms existing attacks against widely studied countermeasures, achieving roughly 60\% and 85\% accuracy against the padding and the obfuscation, respectively. In this context, with a large keyword universe (>=3k), it surpasses current state-of-the-art attacks by more than 20\%. 
