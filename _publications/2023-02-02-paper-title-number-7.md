---
title: "The Power of Bamboo: On the Post-Compromise Security for Searchable Symmetric Encryption"
collection: publications
permalink: /publication/2023-02-02-paper-title-number-7
date: 2023-02-02
venue: 'NDSS (A* conference)'
paperurl: 'https://www.ndss-symposium.org/ndss-paper/the-power-of-bamboo-on-the-post-compromise-security-for-searchable-symmetric-encryption/'
---

Dynamic searchable symmetric encryption (DSSE) enables users to delegate the keyword search over dynamically updated encrypted databases to an honest-but-curious server without losing keyword privacy. This paper studies a new and practical security risk to DSSE, namely, secret key compromise (e.g., a user's secret key is leaked or stolen), which threatens all the security guarantees offered by existing DSSE schemes. To address this open problem, we introduce the notion of searchable encryption with key-update (SEKU) that provides users with the option of non-interactive key updates. We further define the notion of post-compromise secure with respect to leakage functions to study whether DSSE schemes can still provide data security after the client's secret key is compromised. We demonstrate that post-compromise security is achievable with a proposed protocol called ``Bamboo". Interestingly, the leakage functions of Bamboo satisfy the requirements for both forward and backward security. We conduct a performance evaluation of Bamboo using a real-world dataset and compare its runtime efficiency with the existing forward-and-backward secure DSSE schemes. The result shows that Bamboo provides strong security with better or comparable performance. 


