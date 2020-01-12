---
layout: qal
title: Quantum Algorithms and Lower Bounds
---

Workshop on Quantum Algorithms and Lower Bounds
================

Date and venue
----------------
13--14 Feb. 2020

W1008 Building West 8 10F, Ookayama Campus, Tokyo Institute of Technology
([access](https://www.titech.ac.jp/english/maps/ookayama/ookayama.html), The entrance is at #19 of West area)

Speakers
----------------
* Alexandru Gheorghiu (California Institute of Technology)
* Robert T. König (Technical University of Munich)
* François Le Gall (Nagoya University)
* Ryuhei Mori (Tokyo Institute of Technology), Organizer
* Tomoyuki Morimae (Kyoto University)
* Ansis Rosmanis (Nagoya University)
* Kazuya Shimizu (Tokyo Institute of Technology)
* Seiichiro Tani (NTT Corporation)
* Jevgēnijs Vihrovs (University of Latvia)

Schedule
----------------
TBA.

Abstracts
----------------
### Alexandru Gheorghiu (California Institute of Technology)

Title: Computationally-secure and composable remote quantum state preparation

Abstract: Quantum computers are expected to efficiently solve certain problems that are believed to be computationally intractable to classical computers. This raises the question: how can classical users efficiently verify the results produced by quantum computers? In this talk I will present a protocol between a classical polynomial-time verifier and a quantum polynomial-time prover that allows the verifier to securely delegate to the prover the preparation of certain quantum states. Throughout the protocol, the prover remains oblivious as to which state it was instructed to prepare. I will then show how this remote state preparation primitive can be used by the verifier to delegate general quantum computations to the prover and verify their results.
The talk is based on joint work with Thomas Vidick: <https://arxiv.org/abs/1904.06320>

### Robert T. König (Technical University of Munich)

Title: Obstacles to State Preparation and Variational Optimization from Symmetry Protection

Abstract: Local Hamiltonians with topological quantum order exhibit highly entangled ground states that cannot be prepared by shallow quantum circuits. Here, we show that this property may extend to all low-energy states in the presence of an on-site Z2 symmetry. This proves a version of the No Low-Energy Trivial States (NLTS) conjecture for a family of local Hamiltonians with symmetry protected topological order. A surprising consequence of this result is that the Goemans-Williamson algorithm outperforms the Quantum Approximate Optimization Algorithm (QAOA) for certain instances of MaxCut, at any constant level. We argue that the locality and symmetry of QAOA severely limits its performance. To overcome these limitations, we propose a non-local version of QAOA, and give numerical evidence that it significantly outperforms standard QAOA for frustrated Ising models on random 3-regular graphs.
This is joint work with Sergey Bravyi, Alexander Kliesch and Eugene Tang.

### François Le Gall (Nagoya University)

Title: Quantum Distributed Computing

Abstract:
The subject of this talk will be quantum distributed computing, i.e., distributed computing when the processors of the network can exchange quantum information. After describing the basics of distributed computing, I will explain a result obtained with Frédéric Magniez (arXiv:1804.02917) on quantum algorithms computing the diameter of the network. I will then present others results (arXiv:1810.10838 and arXiv:1908.11488) that show separations between the computational powers of quantum and classical distributed algorithms in several fundamental models of distributed computing. I will conclude my talk by mentioning interesting and important open questions in quantum distributed computing.


### Tomoyuki Morimae (Kyoto University)

Title: Fine-grained quantum supremacy

Abstract: It is known that several sub-universal quantum computing models, such as the Boson sampling model, IQP model,
and the one-clean qubit model, are hard to classically sample unless the polynomial hierarchy collapses.
All these results, however, prohibit only polynomial-time classical simulations. In this talk, we show impossibilities of
classically simulating quantum computing even in some exponential time assuming several fine-grained complexity conjectures
such as SETH.
