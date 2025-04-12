---
layout: ../layouts/QAL.astro
title: Quantum Algorithms and Lower Bounds 2021
---

Workshop on Quantum Algorithms and Lower Bounds 2021
================

Date and venue
----------------
21--22 Sept. 2021, Online

[Registration Day 1 (21 Sept.)](https://us06web.zoom.us/meeting/register/tZ0qdeuhpz4tGdzz39ax364IZehznHXtGe3F)

[Registration Day 2 (22 Sept.)](https://us06web.zoom.us/meeting/register/tZYlf-mvqzMsEtQovC49pEIy0X8eRq4mgex-)


Speakers
----------------
* Sergey Bravyi (IBM)
* François Le Gall (Nagoya University)
* Ryuhei Mori (Tokyo Institute of Technology), Organizer
* Tomoyuki Morimae (Kyoto University)
* Ramis Movassagh (IBM Quantum, MIT-IBM AI Research lab)
* Seiichiro Tani (NTT Corporation)
* Jevgēnijs Vihrovs (University of Latvia)

Program
----------------

The timezone is JST (UTC+9).

### 21 Sept.

| Time           | Speaker             | Title |
|---------------:|:--------------------|-------|
| 10:00 -- 11:00 | Ramis Movassagh     | Improved robustness of quantum supremacy for random circuit sampling |
| 11:10 -- 12:10 | Tomoyuki Morimae    | Quantum Encryption with Certified Deletion, Revisited: Public Key, Attribute-Based, and Classical Communication |
| 14:00 -- 15:00 | Seiichiro Tani      | On the average-case quantum hardness of collision problems |

### 22 Sept.

| Time           | Speaker             | Title |
|---------------:|:--------------------|-------|
| 10:00 -- 11:00 | Sergey Bravyi       | Quantum advantage for computations with limited space |
| 11:10 -- 12:10 | Ryuhei Mori         | Lower bounds on error probability of quantum channel discrimination by the Bures angle and the trace distance |
| 14:00 -- 15:00 | François Le Gall    | Test of Quantumness with Small-Depth Quantum Circuits |
| 15:10 -- 16:10 | Jevgēnijs Vihrovs   | Quantum speedups for dynamic programming on $$n$$-dimensional lattice graphs |



Abstracts
----------------

### Sergey Bravyi (IBM)

Title: Quantum advantage for computations with limited space

Abstract:
Quantum computers promise the ability to solve problems that are intractable in the classical setting, but in many cases this is not rigorously proven.
It is often possible to establish a provable theoretical advantage for quantum computations by restricting the computational power.
In multiple cases, quantum advantage over these restricted models was demonstrated experimentally.
Here we consider space-restricted computations that use only one computational classical or quantum bit with a read-only memory as input.
We show that $$n$$-bit symmetric Boolean functions can be implemented exactly in this framework through the use of quantum signal processing and $$O(n^2)$$ gates,
but in the analogous classical computations some of the functions may only be evaluated with probability $$1/2+O(n/\sqrt{2}^n)$$.
We experimentally demonstrate computations of three-bit to six-bit symmetric Boolean functions by quantum circuits with an algorithmic success probability that exceeds the classical limit.
This shows that in computations, quantum scrap space offers an advantage over analogous classical space, and calls for an in-depth exploration of space–time trade-offs in quantum circuits.
This is join work with Dmitri Maslov, Jin-Sung Kim, Theodore J. Yoder and Sarah Sheldon  [Nature Physics](https://www.nature.com/articles/s41567-021-01271-7).

### François Le Gall (Nagoya University)

Title: Test of Quantumness with Small-Depth Quantum Circuits

Abstract:
Recently Brakerski, Christiano, Mahadev, Vazirani and Vidick (FOCS 2018) have shown how to construct a test of quantumness based on the learning with errors (LWE) assumption: a test that can be solved efficiently by a quantum computer but cannot be solved by a classical polynomial-time computer under the LWE assumption. This test has lead to several cryptographic applications. In particular, it has been applied to producing certifiable randomness from a single untrusted quantum device, self-testing a single quantum device and device-independent quantum key distribution.
In this paper, we show that this test of quantumness, and essentially all the above applications, can actually be implemented by a very weak class of quantum circuits: constant-depth quantum circuits combined with logarithmic-depth classical computation. This reveals novel complexity-theoretic properties of this fundamental test of quantumness and gives new concrete evidence of the superiority of small-depth quantum circuits over classical computation.

### Ryuhei Mori (Tokyo Institute of Technology)

Title: Lower bounds on error probability of quantum channel discrimination by the Bures angle and the trace distance

Abstract:
Quantum channel discrimination is a fundamental problem in quantum information science.
In this study, we consider general quantum channel discrimination problems,
and derive the lower bounds of the error probability.
Our lower bounds are based on the triangle inequalities of the Bures angle
and the trace distance.
As a consequence of the lower bound based on the Bures angle, we prove the
optimality of Grover's search if the number of marked elements is fixed to some integer $$k$$.
This result generalizes Zalka's result for $$k=1$$.
We also present several numerical results in which our lower bounds based
on the trace distance outperform recently obtained lower bounds.
This is join work with Ryo Ito [arXiv:2107.03948](https://arxiv.org/abs/2107.03948).

### Tomoyuki Morimae (Kyoto University)

Title: Quantum Encryption with Certified Deletion, Revisited: Public Key, Attribute-Based, and Classical Communication

Abstract:
Broadbent and Islam (TCC '20) proposed a quantum cryptographic primitive called quantum encryption with certified deletion.
In this primitive, a receiver in possession of a quantum ciphertext can generate a classical certificate that the encrypted message is deleted. 
Although their construction is information-theoretically secure, there are two disadvantages:

1. The sender has to generate a quantum state and send it to the receiver over a quantum channel.
1. The verification of the deletion certificate is private.

In this talk, we solve these two problems.

1. We construct a scheme with classical communication based on the LWE assumption.
1. We construct a publicly verifiable one by using the one-shot signatures and extractable witness encryption for NP.

This is the joint work with Taiga Hiroka, Ryo Nishimaki, and Takashi Yamakawa [arXiv:2105.05393](https://arxiv.org/abs/2105.05393) (Accepted in ASIACRYPT2021).

### Ramis Movassagh (IBM Quantum, MIT-IBM AI Research lab)

Title: Improved robustness of quantum supremacy for random circuit sampling

Abstract:
Motivated by the recent experimental demonstrations of quantum supremacy, proving the hardness of the output of random quantum circuits is an imperative near term goal.
We prove under the complexity theoretical assumption of the non-collapse of the polynomial hierarchy that approximating the output probabilities of random quantum circuits
to within $$\exp(-\Omega(m\log m))$$ additive error is hard for any classical computer, where $$m$$ is the number of gates in the quantum computation.
More precisely, we show that the above problem is $$\#\mathsf{P}$$-hard under $$\mathsf{BPP}^{\mathsf{NP}}$$ reduction.
In the recent experiments, the quantum circuit has $$n$$-qubits and the architecture is a two-dimensional grid of size $$\sqrt{n}\times\sqrt{n}$$.
Indeed for constant depth circuits approximating the output probabilities to within $$2^{-\Omega(n\log{n})}$$ is hard. For circuits of depth $$\log{n}$$ or $$\sqrt{n}$$ for which the anti-concentration property holds,
approximating the output probabilities to within $$2^{-\Omega(n\log^2{n})}$$ and $$2^{-\Omega(n^{3/2}\log n)}$$ is hard respectively.
We made an effort to find the best proofs and proved these results from first principles, which do not use the standard techniques such as the Berlekamp--Welch algorithm, the usual Paturi's lemma, and Rakhmanov's result. 
This is joint work with Yasuhiro Kondo and Ryuhei Mori [arXiv:2102.01960](https://arxiv.org/abs/2102.01960) (Accepted in FOCS2021).


### Seiichiro Tani (NTT Corporation)

Title: On the average-case quantum hardness of collision problems

Abstract：
Finding collisions or multicollisions is a fundamental problem in theoretical computer science and one of the most central problems in cryptography. For given finite sets $$X$$ and $$Y$$ with $$|Y| = N$$,
and a function $$F \colon X \to Y$$, the l-collision finding problem is to find a set of l distinct inputs $$x_1,\dotsc,x_l$$ such that $$F(x_1)=\dotsb=F(x_l)$$.
Bounding query and time complexities of the $$l$$-collision finding problem is fundamental and has several applications.
In this talk, we first briefly review the current status of collision problems in various settings, and then present a quantum algorithm that finds an $$l$$-collision for a given random function.
This algorithm has an optimal time/query complexity, up to a logarithmic factor, in the setting where the size of the function domain is sufficiently large.
We then discuss the limit of this algorithm, open problems, and the relationship between the average-case and worst-case settings.
This talk is partly based on [arXiv:1911.02822](https://arxiv.org/abs/1911.02822) (A draft version of Theoretical Computer Science, 842:100-117, (2020)).

### Jevgēnijs Vihrovs (University of Latvia)

Title: Quantum speedups for dynamic programming on $$n$$-dimensional lattice graphs

Abstract:
Motivated by the quantum speedup for dynamic programming on the Boolean hypercube by Ambainis et al. (2019), we investigate which graphs admit a similar quantum advantage.
In this paper, we examine a generalization of the Boolean hypercube graph, the $$n$$-dimensional lattice graph $$Q(D,n)$$ with vertices in $$\{0,1,…,D\}^n$$.
We study the complexity of the following problem: given a subgraph $$G$$ of $$Q(D,n)$$ via query access to the edges, determine whether there is a path from $$0^n$$ to $$D^n$$.
While the classical query complexity is $$\Theta((D+1)^n)$$, we show a quantum algorithm with complexity $$\tilde{O}(T_D^n)$$, where $$T_D < D+1$$.
The first few values of $$T_D$$ are $$T_1 \approx 1.817$$, $$T_2 \approx 2.660$$, $$T_3 \approx 3.529$$, $$T_4 \approx 4.421$$, $$T_5 \approx 5.332$$.
We also prove that $$T_D \ge (D+1)/e$$ (here, $$e \approx 2.718$$ is the Euler’s number), thus for general $$D$$, this algorithm does not provide, for example, a speedup, polynomial in the size of the lattice.
While the presented quantum algorithm is a natural generalization of the known quantum algorithm for $$D = 1$$ by Ambainis et al., the analysis of complexity is rather complicated.
For the precise analysis, we use the saddle-point method, which is a common tool in analytic combinatorics, but has not been widely used in this field.
We then show an implementation of this algorithm with time and space complexity $$\mathrm{poly}(n)^{\log n} T_D^n$$ in the QRAM model, and apply it to the Set Multicover problem.
In this problem, $$m$$ subsets of $$[n]$$ are given, and the task is to find the smallest number of these subsets that cover each element of $$[n]$$ at least $$D$$ times.
While the time complexity of the best known classical algorithm is $$O(m(D+1)^n)$$, the time complexity of our quantum algorithm is $$\mathrm{poly}(m,n)^{\log n} T_D^n$$.
This is joint work with Adam Glos, Martins Kokainis, and Ryuhei Mori [MFCS 2021](https://doi.org/10.4230/LIPIcs.MFCS.2021.50).


Link
----------------
[QAL20](./QAL20)

