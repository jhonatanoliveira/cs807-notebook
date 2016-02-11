---
published: true
title: Second Research Task
layout: post
---
The second research task is going to be on *The past/future*. The chosen topic is *memcomputing* (see [this article](https://www.technologyreview.com/s/507721/the-computer-that-stores-and-processes-information-at-the-same-time/) for an introduction).
In resume, memcomputing is a non-Turing architecture for computers. It uses passive elements including capacitors, inductors, and resistors, instead of active ones, a transistor, for instance.

Next, I will present a proposal structure for this paper. Here are some ideas for flow and content but it does not reflect the final version of the paper.

- The Problem
    - von Neumann bottleneck: the rate at which data is transferred between the CPU and the memory units is the true limiting factor of computa- tional speed
- Possible solutions and their problems
    - Parallelism:
        - Requires multiple cores (extra complexity with individual limitations). If not using multiple cores: specialized units (GPUs) (extra complexity and different limitations).
    - Quantum Computer:
        - Non feasible: despite much effort in the past two decades, a practical quantum computer able to outperform a classical computer even in its most simple operations has yet to be fabricated
- An alternative computer
    - The wish list for
        - intrinsically massively-parallel
        - storing and computing units are the same
    - Why transistors can not attend the wish list
        - three terminal active device: relatively high power consumption and low density
    - Memcomputing
        - Memelements
            - two-terminal electronic devices whose resistance, capacitance or inductance keeps track of the system’s past dynamics.
            - Three classes:
                - Memristive
                - Memcapacitive
                - Meminductive
            - By definition, memelements store information in analog form in their response characteristics (in addition to the ability of memcapacitive and meminductive systems to store information in the electric and magnetic field energies, respectively):
                - memcapacitive: electric magnetic field
                - meminductive:  electric magnetic field
                - memresitive: changing the resistance
