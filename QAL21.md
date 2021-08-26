---
layout: qal
title: Quantum Algorithms and Lower Bounds 2021
---

Workshop on Quantum Algorithms and Lower Bounds 2021
================

Date and venue
----------------
21--22 Sept. 2021, Online


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


Abstracts
----------------

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

### Jevgēnijs Vihrovs (University of Latvia)

Title: Quantum Speedups for Dynamic Programming on $$n$$-Dimensional Lattice Graphs

Abstract:
Motivated by the quantum speedup for dynamic programming on the Boolean hypercube by Ambainis et al. (2019), we investigate which graphs admit a similar quantum advantage.
In this paper, we examine a generalization of the Boolean hypercube graph, the $$n$$-dimensional lattice graph $$Q(D,n)$$ with vertices in $$\{0,1,…,D\}^n$$.
We study the complexity of the following problem: given a subgraph $$G$$ of $$Q(D,n)$$ via query access to the edges, determine whether there is a path from $$0^n$$ to $$D^n$$.
While the classical query complexity is $$\Theta((D+1)^n)$$, we show a quantum algorithm with complexity $$\tilde{O}(T_D^n)$$, where $$T_D < D+1$$.
The first few values of $$T_D$$ are $$T_1 \approx 1.817$$, $$T_2 \approx 2.660$$, $$T_3 \approx 3.529$$, $$T_4 \approx 4.421$$, $$T_5 \approx 5.332$$.
We also prove that $$T_D \ge (D+1)/e$$ (here, $$e \approx 2.718$$ is the Euler’s number), thus for general $$D$$, this algorithm does not provide, for example, a speedup, polynomial in the size of the lattice.
While the presented quantum algorithm is a natural generalization of the known quantum algorithm for $$D = 1$$ by Ambainis et al., the analysis of complexity is rather complicated.
For the precise analysis, we use the saddle-point method, which is a common tool in analytic combinatorics, but has not been widely used in this field.
We then show an implementation of this algorithm with time and space complexity $$\mathsf{poly}(n)^{\log n} T_D^n$$ in the QRAM model, and apply it to the Set Multicover problem.
In this problem, $$m$$ subsets of $$[n]$$ are given, and the task is to find the smallest number of these subsets that cover each element of $$[n]$$ at least $$D$$ times.
While the time complexity of the best known classical algorithm is $$O(m(D+1)^n)$$, the time complexity of our quantum algorithm is $$\mathsf{poly}(m,n)^{\log n} T_D^n$$.
This is joint work with Adam Glos, Martins Kokainis, and Ryuhei Mori.
