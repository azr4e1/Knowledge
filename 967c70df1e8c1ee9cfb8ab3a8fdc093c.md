---
title: Cryptographic glossary
author: Lorenzo Drumond
date: 2024-07-03T11:15:24
last: 2024-07-03T11:16:21
zk_id: 967c70df1e8c1ee9cfb8ab3a8fdc093c
tags: #glossary #cryptography
---


# Cryptographic glossary

- The plaintext is the original message.
- The ciphertext is traditionally a message that has been transformed to provide confidentiality.
- A cipher is a cryptographic transformation that is used to encrypt or decrypt a message.
- A message authentication code (or MAC) is a piece of data that provides authenticity and integrity. A MAC algorithm is used both to generate and validate this code.
- To encrypt a message is to apply a confidentiality transformation, but is often used to describe a transformation that satisfies all three goals.
- To decrypt a message to reverse the confidentiality transformation, and often indicates that the other two properties have been verified.
- A hash or digest algorithm transforms some arbitrary message into a fixed-size output, also called a digest or hash. A cryptographic hash is such an algorithm that satisfies some specific security goals.
- A peer or party describes an entity involved in the communication process. It might be a person or another machine.

# References
- https://leanpub.com/gocrypto/read#leanpub-auto-chapter-1-introduction
