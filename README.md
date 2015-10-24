# Constraint-Satisfaction-Problem
This is a generalized library for solving problems that can be reduced to the Constraint Satisfaction Problem.

This project was inspired by a post on https://www.reddit.com/r/dailyprogrammer about the Tazuku Solver (https://www.reddit.com/r/dailyprogrammer/comments/3pwf17/20151023_challenge_237_hard_takuzu_solver/)

Problems like this (along with Sudoku, Class Scheduling, etc) can be reduced to the Constraint Satisfaction Problem (CSP).

The Constraint Satisfaction Problem is a mathematical problem where a set of variables must meet certain constraints or limitations with regards to their values.


----
Formal Definition:

Formally, a constraint satisfaction problem is defined as a triple \langle X,D,C \rangle, where

X = \{X_1, \ldots,X_n\} is a set of variables,
D = \{D_1, \ldots, D_n\} is a set of the respective domains of values, and
C = \{C_1, \ldots, C_m\} is a set of constraints.

----

The user may define the constaints in a property file.
