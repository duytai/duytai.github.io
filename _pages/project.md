---
layout: page
title: Projects
permalink: /projects/
---

#### 1.Fuzzing smart contracts

**Abstract** Smart contracts are Turing-complete programs that execute on the infrastructure of the blockchain, which often manage valuable digital assets. Solidity is one of the most popular programming languages for writing smart contracts on the Ethereum platform. Like traditional programs, smart contracts may contain vulnerabilities. Unlike traditional programs, smart contracts cannot be easily patched once they are deployed. It is thus important that smart contracts are tested thoroughly before deployment. In this work, we present an adaptive fuzzer for smart contracts on the Ethereum platform called sFuzz. Compared to existing Solidity fuzzers, sFuzz combines the strategy in the AFL fuzzer and an efficient lightweight multi-objective adaptive strategy targeting those hard-to-cover branches. sFuzz has been applied to more than 4 thousand smart contracts and the experimental results show that (1) sFuzz is efficient, e.g., two orders of magnitude faster than state-of-the-art tools; (2) sFuzz is effective in achieving high code coverage and discovering vulnerabilities; and (3) the different fuzzing strategies in sFuzz complement each other.

#### 2.Patching smart contracts

**Abstract** Smart contracts are distributed, self-enforcing programs executing on top of blockchain networks. They have the potential to revolutionize many industries such as financial institutes and supply chains. However, smart contracts are subject to code-based vulnerabilities, which casts a shadow on its applications. As smart contracts are unpatchable (due to the immutability of blockchain), it is essential that smart contracts are guaranteed to be free of vulnerabilities. Unfortunately, smart contract languages such as Solidity are Turing-complete, which implies that verifying them statically is infeasible. Thus, alternative approaches must be developed to provide the guarantee. In this work, we develop an approach which automatically transforms smart contracts so that they are provably free of 4 common kinds of vulnerabilities. The key idea is to apply runtime verification in an efficient and provably correct manner. Experiment results with 5000 smart contracts show that our approach incurs minor run-time overhead in terms of time (i.e., 14.79%) and gas (i.e., 0.79%).

#### 3.A General-purpose fuzzer

Under review

#### 4.Smart Contract Specifications

I am working on it
