---
title: Flow Engineering
author: Lorenzo Drumond
date: 2024-02-20T18:29:12
last: 2024-02-20T18:35:20
zk_id: f13e3b0ddaaf071b5fbda9ebc730f632
tags: #coding #engineering #artificial_intelligence #few_shot #flow #procedure #computer_science #learning #codium #LLM #AI #tests #code #programming #ML #one_shot
---


# Flow Engineering
Flow engineering is a procedure that guides a model's (LLM) problem-solving process by splitting it into well-defined steps.

E.g. AlphaCodium (code generating bot)

Steps:

1. A programming question is fed to an underlying LMM, and it's asked to summarise the problem.
2. AlphaCodium defines things like inputs and outputs.
3. The model generates code that aligns with the specifications just described.
4. AlphaCodium generates many test cases from the specification, and runs through possible solutions to check if the code is working as expected
5. The model keeps generating different solutions until they pass all the tests, or it fails

This is split into a _pre-processing_ phase, where the system analyzes the problem in natural language, and a _code-iteration_ stage, where it runs possible solutions against public and AI-generated tests

# References
- https://go.theregister.com/feed/www.theregister.com/2024/02/19/codium_ai_interview/
