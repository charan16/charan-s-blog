---
layout:     page
title:      Quantum Computing--An introduction
date:       2020-07-4
summary:    This is an introduction to the Quantum Computing
categories: Quantum Computing
---
Quantum Supremacy is quite a buzz term in the world of computer science. If a quantum computer solves a problem in a better way than a traditional computer this is termed as achieving quantum supremacy. Quantum Computing is the science that powers quantum computers. It is the use of quantum mechanic phenomenon to perform computation. Quantum computation is like performing computations probabilistically i.e on probabilities. This article is focused on introducing the readers to the world of Quantum Computing.

## Quantum Computing


   >Quantum computing is the use of quantum-mechanical principles such as Superposition and Entanglement to perform computation.




To understand this in much depth Let us recap how our conventional computers work. The classical computers process information in bits 1 and 0. A bit can have a value of either 0-state or 1-state.

Quantum computers process information in quantum bits or “qubits” which can take form of either 0 or 1 or both. Yes, a quantum bit can be present in multiple states at the same time until it is measured. This principle is known as Superposition. Actually, a qubit is always in a superposition state only measuring it actually forces it to come to a single state.This is explained in detail later below.
Entanglement states that two qubits are related to each other i.e

_"measuring one qubit will force the other qubit to be in same state”_.

It is confusing and spooky right. Yes infact, Einstein also felt the same. He called quantum entanglement a Spooky action. In order to understand entanglement principle and how applied in quantum computation is little tough and is out of scope of this introductory article.
There are several models for quantum computations. One of such model is quantum circuit . It is analogous to a logical circuit in the classical computers. It is build up of quantum gates. These are like classical logic gates like and, or and not gate. We can come to an understanding that a quantum computer is a network of quantum logic gates and measurements.

## When to use Quantum Computers?

Let us first answer the question why do we need quantum computers , can classical computers do not solve a problem that quantum computers do?quantum computers obey the Church–Turing thesis, that is, any computation problem that can be solved by a quantum computer can also be solved by a classical computer. These are useful because some problem require very less time when solved on a quantum computer than on a traditional computer. These gives us the question what are problems that are faster to solve using quantum computation.
Any problem that has an enormous state space or huge choices whose answers can only get by actually performing computations like in case of cryptography, optimisation etc. There are lot of resources that will point to the individual applications in the respective field.

## Quantum Superposition

After knowing about what and when details of Quantum computing. Let us deeply understand its fundamental principals. One of such principle is Superposition. We have already established that it is in a superposition state of both 0 and 1. Let us understand this deeply with an example. Let us take the example of Schrodinger cat.It is a taught experiment which was designed by Erwin Schrodinger.
In this experiment he takes a cat and puts it in a box with a danger and closes it. The probability of cat live or dead is 0.5.

![cat_image](assets/image1.png)
*Image from https://youtu.be/UjaAxUO6-Uw*

After some time he opens the box. Let us think we all know the output right?

![cat_image](assets/image3.png)

Image from https://youtu.be/UjaAxUO6-Uw

Cat is either dead or alive. What happens when the box is not opened ?


Now think in a probabilistic way Cat is 50 % dead and 50 % alive at the same time.


![cat_image](assets/image2.png)


Weird right! yes the principles that define the inner particles are more weird. Quantum mechanics defines the principle that govern the sub atomic particles. General Relativity defines the principles that govern the large bodies. These two don’t go hand in hand and which is much more weird. Ok ! let us come back to cat, when the box is not opened Quantum mechanics defines that Cat is in a superposition state of live and end. We only know its definite state(alive or dead) only when measured (i.e box is open).

The cat sate can be defined like this

      Cat = 0.5 alive + 0.5 dead

Now let’s use the analogy to dead — 0 and alive — 1.

      Cat = 0.5 |0> + 0.5 |1>

Now remove cat and use quantum bit

      q = 0.5 |0> + 0.5 |1>

Now let us replace 0.5 with probability of 0 state ‘a’ and another probability 0.5 with 1 state ‘b’

      q = a |0> + b |1>

which is how Quantum bits are represented. The super position of state that is present a chance in 0 and b chance in 1 and we can only know its definite state of 0 and 1 only when we measured it. Thus quantum Computation is a game of probabilities :).

In the conclusion we have understood the quantum computation and it’s building blocks and where to use them and how qubits are represented.I am excited to start this journey of Quantum computing and will keep post the articles as I advance in the journey.
Sources:-
1. <https://en.wikipedia.org/wiki/Quantum_computing>
2. <http://tph.tuwien.ac.at/~oemer/>
3. <https://phys.org/news/2016-09-quantum-advances-entanglement.html>
