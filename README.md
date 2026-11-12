# Demo: DTC

*description of the project*

**Timeframe** 2026-10-29 - 2027-02-04

## Overview

This repository was created via the **Design Assistant**.  
It contains the template files and in-scope pages needed to get started.

GitHub Pages: [https://cra-test-arc.canada.ca/demo-dtc-2026](https://cra-test-arc.canada.ca/demo-dtc-2026)

---
## Update procedures

Add information on how to manage your repo here.

---
## Design phase roadmap:

- [x] Initial content inventory and repo setup
- [ ] Prototype: co-design navigation and content
- [ ] SME review and accuracy check
- [ ] Validation usability testing (including accessibility review)
- [ ] Refine prototype (if required)
- [ ] Spot check usability (if required)

**Updated:**  2026-11-12

## Information Architecture
```mermaid
flowchart TD;
    node1(Canada.ca)
    node2(Taxes)
    node3(Tax credits and benefits for individuals)
    node4(Disability tax credit #40;DTC#41;)
    node5(What is the DTC)
    node6(Who is eligible)
    node7(How to apply)
    node8(CRA's review)
    node9(CRA's decision)
    node10(Claiming the credit – Disability tax credit #40;DTC#41;)
    node11(Get support for an issue)
    node12(Demystifying the disability tax credit)
    node1 --> node2
    node2 --> node3
    node3 --> node4
    node4 --> node5
    node4 --> node6
    node4 --> node7
    node4 --> node8
    node4 --> node9
    node4 --> node10
    node4 --> node11
    node4 --> node12

    classDef inscope stroke:#7636ab,stroke-width:3px
    class node4,node5,node6,node7,node8,node9,node10,node11,node12 inscope
```
