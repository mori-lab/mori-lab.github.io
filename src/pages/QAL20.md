---
layout: ../layouts/QAL.astro
title: Quantum Algorithms and Lower Bounds 2020
---

Workshop on Quantum Algorithms and Lower Bounds 2020
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
* Seiichiro Tani (NTT Corporation)
* Jevgēnijs Vihrovs (University of Latvia)

Program
----------------

### 13 Feb.

| Time           | Speaker             | Title |
|---------------:|:--------------------|-------|
| Cancelled | Ansis Rosmanis      | Adversary Method Beyond Function Evaluation |
| 14:10 -- 15:10 | Tomoyuki Morimae    | Fine-grained quantum supremacy |
| 15:20 -- 16:20 | Robert T. König     | Obstacles to State Preparation and Variational Optimization from Symmetry Protection |

### 14 Feb.

| Time           | Speaker             | Title |
|---------------:|:--------------------|-------|
|  9:30 -- 10:30 | Alexandru Gheorghiu | Computationally-secure and composable remote quantum state preparation |
| 10:40 -- 11:40 | Ryuhei Mori         | Quantum nonlocality and quantum computation |
| 13:40 -- 14:40 | Seiichiro Tani      | Quantum Algorithm for Finding the Optimal Variable Ordering for Binary Decision Diagrams |
| 14:50 -- 15:50 | Jevgēnijs Vihrovs   | On Quantum Speedups for Dynamic Programming |
| 16:00 -- 17:00 | François Le Gall    | Quantum Distributed Computing |

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
The subject of this talk will be quantum distributed computing, i.e., distributed computing when the processors of the network can exchange quantum information. After describing the basics of distributed computing, I will explain a result obtained with Frédéric Magniez ([arXiv:1804.02917](https://arxiv.org/abs/1804.02917)) on quantum algorithms computing the diameter of the network. I will then present others results ([arXiv:1810.10838](https://arxiv.org/abs/1810.10838) and [arXiv:1908.11488](https://arxiv.org/abs/1908.11488)) that show separations between the computational powers of quantum and classical distributed algorithms in several fundamental models of distributed computing. I will conclude my talk by mentioning interesting and important open questions in quantum distributed computing.

### Ryuhei Mori (Tokyo Institute of Technology)

Title: Quantum nonlocality and quantum computation

Abstract:
Quantum nonlocality is one of the most important feature of quantum physics.
From the discovery of the violation of Bell (CHSH) inequality, many types of Bell inequalities have been found and considered.
In this talk, we consider how the quantum nonlocality can be regarded as resource of computation,
and show relationship with recent developments on separations of complexity classes defined by quantum shallow circuits and classical shallow circuits.


### Tomoyuki Morimae (Kyoto University)

Title: Fine-grained quantum supremacy

Abstract: It is known that several sub-universal quantum computing models, such as the Boson sampling model, IQP model,
and the one-clean qubit model, are hard to classically sample unless the polynomial hierarchy collapses.
All these results, however, prohibit only polynomial-time classical simulations. In this talk, we show impossibilities of
classically simulating quantum computing even in some exponential time assuming several fine-grained complexity conjectures
such as SETH.

### Ansis Rosmanis (Nagoya University)

Title: Adversary Method Beyond Function Evaluation

Abstract: The adversary method for lower bounding quantum query
complexity was introduced some 20 years ago. It was subsequently
strengthened, allowing negative weights in the adversary matrix. Then,
some 10 years ago, it was shown that this negative-weights adversary
method can prove optimal bounds for any function-evaluation problem.
However, the scope of the adversary method goes beyond function
evaluation. In this talk, I will present some of my recent work in
this area.

### Seiichiro Tani (NTT Corporation)

Title: Quantum Algorithm for Finding the Optimal Variable Ordering for Binary Decision Diagrams

Abstract:
The ordered binary decision diagram (OBDD) is one of the data structures that have been most often used for decades to represent Boolean functions in practical situations. Since the early stages of OBDD research, one of the most central problems has been how to find an optimal variable ordering, i.e., one that minimizes OBDDs. In this talk, based on [arXiv:1909.12658](https://arxiv.org/abs/1909.12658), we review OBDDs and present an exponential-time quantum algorithm that is asymptotically better than the best known classical algorithm.


### Jevgēnijs Vihrovs (University of Latvia)

Title: On Quantum Speedups for Dynamic Programming

Abstract:
In this talk, we examine quantum algorithms for NP-complete problems whose best classical algorithm is an exponential time application of dynamic programming. We introduce the path in the hypercube problem that models many of these dynamic programming algorithms.
In this problem we are asked whether there is a path from $$0^n$$ to $$1^n$$ in a given subgraph of the Boolean hypercube, where the edges are all directed from smaller to larger Hamming weight. We give a quantum algorithm that solves path in the hypercube in time $$O^*(1.817^n)$$.
The technique combines Grover's search with computing a partial dynamic programming table. We use this approach to solve a variety of vertex ordering problems on graphs in the same time $$O^*(1.817^n)$$, and graph bandwidth in time $$O^*(4.383^n)$$.
Then we use similar ideas to solve the travelling salesman problem and minimum set cover in time $$O^*(1.728^n)$$. Finally, we will look at some open questions and directions for research.
