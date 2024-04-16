---
title: "CCA-1 Secure Updatable Encryption with Adaptive Security"
collection: publications
permalink: /publication/2023-03-03-paper-title-number-8
date: 2023-03-03
venue: 'ASIACRYPT (A conference)'
paperurl: 'https://eprint.iacr.org/2022/1339'
---

Updatable encryption (UE) enables a cloud server to update ciphertexts using client-generated tokens. There are two types of UE: ciphertext-independent (c-i) and ciphertext-dependent (c-d). In terms of construction and efficiency, c-i UE utilizes a single token to update all ciphertexts. The update mechanism relies mainly on the homomorphic properties of exponentiation, which limits the efficiency of encryption and updating. Although c-d UE may seem inconvenient as it requires downloading parts of the ciphertexts during token generation, it allows for easy implementation of the Dec-then-Enc structure. This methodology significantly simplifies the construction of the update mechanism. Notably, the c-d UE scheme proposed by Boneh et al. (ASIACRYPT’20) has been reported to be 200 times faster than prior UE schemes based on DDH hardness, which is the case for most existing c-i UE schemes. Furthermore, c-d UE ensures a high level of security as the token does not reveal any information about the key, which is difficult for c-i UE to achieve. However, previous security studies on c-d UE only addressed selective security; the studies for adaptive security remain an open problem.

In this study, we make three significant contributions to ciphertext-dependent updatable encryption (c-d UE). Firstly, we provide stronger security notions compared to previous work, which capture adaptive security and also consider the adversary’s decryption capabilities under the adaptive corruption setting. Secondly, we propose a new c-d UE scheme that achieves the proposed security notions. The token generation technique significantly differs from the previous Dec-then-Enc structure, while still preventing key leakages. At last, we introduce a packing technique that enables the simultaneous encryption and updating of multiple messages within a single ciphertext. This technique helps alleviate the cost of c-d UE by reducing the need to download partial ciphertexts during token generation.


