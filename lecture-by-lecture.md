
# Course Materials

(adapted from last year ... subject to change ... times are estimates)

**Quick Links**: [Installing Haskell](https://hackmd.io/@alexhkurz/Hk86XnCzD) ... [BNFC](BNFC-installation.md) ... [Haskell projects](haskell-projects.md) ... [videos](videos.md)

## Summer Preparations

[First Haskell Steps](https://hackmd.io/@alexhkurz/SJgHGZ_nw)

## Lecture by Lecture 

#### Introduction: A Calculator in Haskell

In this part, we will learn about parsing and write our first interpreter for a programming language that only has arithmetic expressions.

- **A Calculator in Haskell (Abstract Syntax)** ... [notes](https://hackmd.io/@alexhkurz/SyxKCkR6U)
- **A Calculator in Haskell (Concrete Syntax)** ...  [notes](https://hackmd.io/@alexhkurz/HJVtVl068)
- Videos:
  - [gcd and Euclid's algorithm](https://youtu.be/ZcJMj0antos)
  - [Recursion over algebraic data types in Haskell](https://youtu.be/2YLfJvOtLwA)
  - [Precedence levels in CFGs](https://youtu.be/jf1xhZSpCvg)  
  - [Uniqueness of parse trees](https://youtu.be/3ZLkPwB_c9g) 

[Assignment 1](assignments.md): Haskell, recursion over abstract data types, a calculator.


#### Lambda Calculus

- **Syntax of Lambda Calculus** ... [video preview](https://youtu.be/D0kH1BpNr14) ... [notes](https://hackmd.io/@alexhkurz/S1D0yP8Bw) ... video reviews on parsing [1](https://youtu.be/eYstx7uuE6c) and [2](https://youtu.be/yls1NEUlzZA)
- **Semantics of Lambda Calculus** ...[video preview](https://youtu.be/h4aT42t7v9c) ... [notes](https://hackmd.io/@alexhkurz/H1e4Nv8Bv) ... [video review](https://youtu.be/for3Meg1Lbc)

- Videos:
  - [Syntax of Lambda Calculus](https://youtu.be/D0kH1BpNr14)
  - [Parsing Lambda Calculus Expressions 1](https://youtu.be/eYstx7uuE6c)
  - [Parsing Lambda Calculus Expressions 2](https://youtu.be/yls1NEUlzZA)
  - [Operational Semantics of Lambda Calculus](https://youtu.be/h4aT42t7v9c)
  - [Reducing Lambda Expressions](https://youtu.be/for3Meg1Lbc). While watching this video, do the reductions in your own text editor. Frequently stop the video and guess the next step. Work along, it is all just the beta rule.
  - [Fixed Point Combinator](https://youtu.be/XvDOwbSh3xE)

[Assignment 2, Part 1](assignments.md): An interpreter for lambda calculus.


#### Blog

Deadline (tba) for a first draft of the first parts of your [blog](blog.md) (5 weeks = 5 entries). You will receive up to 5 points "on completion" (no grading for content yet), so you will have more time to flesh this out and polish it.

#### Rewriting as a Model of Computation

Lectures:
- [Rewriting: Examples](https://hackmd.io/@alexhkurz/rkzITG4nD). Abstract Reduction Systems: [Definition and Examples](https://hackmd.io/@alexhkurz/BJfvFVK8v)
- [Confluence and Normal Forms](https://hackmd.io/@alexhkurz/r1hRZaG8v).
- [Termination](https://hackmd.io/@alexhkurz/BJoZF44Iw)
- [Invariants](https://hackmd.io/@alexhkurz/BkMoUhXvD).

Supplementary materials:
- [Discrete Mathematics: Relations](https://hackmd.io/@alexhkurz/SJ1cc-dDr)
- Video on [merge sort](https://youtu.be/W2CknJGgzr0)
- [Exercises](https://hackmd.io/@alexhkurz/BJ23jmpIw)

#### Midterm 

(Nov 3 in 2020)

#### Assignment 2

An interpreter for a functional programming language. Extending lambda calculus with numbers, conditionals, recursion and lists.

- [Extensions of lambda-calculus](https://hackmd.io/@alexhkurz/rJEeYqZtw) ... video review on the [fixed point combinator](https://youtu.be/XvDOwbSh3xE).
- The [Work Cycle](https://github.com/alexhkurz/programming-languages-2020/blob/master/Lab1-Lambda-Calculus/README.md). I use scripts like [lambdanat](lambdanat) to automate part of the work cycle. Feel free to adapt to your own needs.

#### Program Verification 

There are many approaches to software reliability. You will be familiar with testing, which is part of the wider area of program analysis. In this section of the course we will look at program verification.

- [Hoare Logic](https://hackmd.io/Df57tnuCSGaW8wqqsl57FQ) ... [Exercises](https://hackmd.io/@alexhkurz/rkhVZNzjH)


#### Assignment 3

An interpreter for an imperative programming language.

---

## Bonus Lectures

In previous years, this course was more theoretical and less focussed on Haskell. I put here some material I dropped for 2020. I hope to bring back some of it for 2021.

#### More on Syntax and Semantics

- [Syntax and Semantics](https://hackmd.io/r_6EY8pVR7OdijRAEFNKvg) and  [Meaning in Syntax](https://hackmd.io/khfFd9N2RRWau8o-1ACc_g) 

#### Logic and Reasoning 

- [Rules of logic](https://hackmd.io/xJ8NOiK4S5qnYvEI85bHig)
- [Normalisation by Evaluation](https://hackmd.io/w9RLzXmcS86U4HVAQi5Lqg)
- [Induction and Equational Reasoning](https://hackmd.io/02w2FuLsT_uKYQxkPSdvtw)
- [Theorem Proving](https://hackmd.io/JrBBURefROGD1xMN44Zivw)

#### Universal Algebra and Category Theory

 - Abstract Data Types
 - What is Structure?
 - Structure Preserving Maps
 - Universal Properties

