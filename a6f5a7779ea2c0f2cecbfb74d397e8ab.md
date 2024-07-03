---
title: Public Key Infrastructure
author: Lorenzo Drumond
date: 2024-07-03T12:42:02
last: 2024-07-03T12:45:11
zk_id: a6f5a7779ea2c0f2cecbfb74d397e8ab
tags: #integrity #PKI #confidentiality #authorisation #errors #authentication #cryptography #auditing #authenticity #security #model #basics
---


# Public Key Infrastructure

When deploying a system that uses public key cryptography, determining how to trust and distribute public keys becomes a challenge that adds extra engineering complexity and costs to the system. A public key by itself contains no information; some format that contains any other required identity and metadata information needs to be specified.

Deciding on what identity information to include and how it is to be verified should be considered, as should the lifetime of keys and how to enforce key expirations, if needed. There are administrative and policy considerations that need to be made; PKI is largely not a cryptographic problem, but it does have cryptographic impact.

Key rotation is one of the challenges of PKI. It requires determining the cryptoperiod of a key (how long it should be valid for); a given key can generally only encrypt or sign so much data before it must be replaced (so that it doesn’t repeat messages, for example). In the case of TLS ([[how-does-tls-work]]) many organisations are using certificates with short lifetimes. This means that if a key is compromised and revocation isn’t effective, the damage will be limited. Key rotation problems can also act as DoS attack: if the rotation is botched, it can leave the system unusable until fixed.



# References
