# Divisor-Game
Leetcode Problem #1025. Find winner of divisor game.

# Alice and Bob Game

## Problem Description

Alice and Bob take turns playing a game, with **Alice starting first**.

- Initially, there is a number `n` on the chalkboard.
- On each player's turn, they **must choose** an integer `x` such that:
  - `0 < x < n`, and
  - `n % x == 0` (i.e., `x` is a divisor of `n`).
- The player then **replaces** `n` on the chalkboard with `n - x`.

If a player **cannot make a move**, they **lose** the game.

Both players play optimally.

## Objective

Write a function that returns `true` **if and only if Alice wins the game**, assuming both players play optimally.
---
