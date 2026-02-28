---
title: "Scalable MatMul Free LLM Accelerator"
collection: projects
permalink: /projects/MatMulFree
type: "Research Project"
venue: "Hardware Systems Collective "
---

The goal of this project is to create an accelerator for Ternary Large Language Models on FPGA. As apart of this project I am exploring the performance bottlenecks that are unique to ternary large language models. Since Ternary Large Language Models weights take up much less space it is possible that they might not exhibit the same memory bound bottlenecks that 32-64 bit high precision LLMs do, which I have been investigating through different profiling tools. I have also been experimenting with extremely lower precision LLMs with ternary weights an 8 bit integer activations.