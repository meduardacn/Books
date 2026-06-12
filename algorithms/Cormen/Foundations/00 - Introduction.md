# Part I — Foundations: Introduction

This part starts the reader thinking about designing and analyzing algorithms. It is meant as a gentle introduction to how algorithms are specified, to the design strategies used throughout the book, and to many of the fundamental ideas used in algorithm analysis. Later parts build on this base.

## What each chapter covers

- **Chapter 1 — The Role of Algorithms in Computing.** Provides an overview of algorithms and their place in modern computing systems. It defines what an algorithm is, lists examples, and makes the case that algorithms should be considered a *technology*, alongside fast hardware, graphical user interfaces, object-oriented systems, and networks.

- **Chapter 2 — Getting Started.** Presents the first algorithms, which solve the sorting problem for a sequence of n numbers. They are written in a pseudocode that, although not directly translatable to any conventional programming language, conveys the structure clearly enough to be implemented in the language of one's choice. The algorithms examined are *insertion sort* (an incremental approach) and *merge sort* (a recursive "divide-and-conquer" technique). Running times of both are determined, and a useful notation for expressing them is developed.

- **Chapter 3 — Growth of Functions.** Precisely defines the *asymptotic notation* used for bounding algorithm running times from above and/or below. The rest of the chapter is primarily a presentation of mathematical notation, intended to align the reader's usage with the book's rather than to teach new mathematical concepts.

- **Chapter 4 — Divide-and-Conquer.** Goes further into the divide-and-conquer method introduced in Chapter 2. Provides additional examples, including Strassen's surprising method for multiplying two square matrices, and methods for solving recurrences (which describe the running times of recursive algorithms). A powerful technique is the *master method*, used to solve recurrences arising from divide-and-conquer algorithms. The proof of the master method can be skipped while still applying it.

- **Chapter 5 — Probabilistic Analysis and Randomized Algorithms.** Introduces probabilistic analysis and randomized algorithms. *Probabilistic analysis* is typically used to determine running times when an inherent probability distribution causes running time to differ across inputs of the same size. A *randomized algorithm* is one whose behavior is determined not only by its input but by the values produced by a random-number generator. Randomized algorithms can enforce a probability distribution on the inputs — ensuring that no particular input always causes poor performance — or even bound the error rate of algorithms allowed to produce incorrect results on a limited basis.
