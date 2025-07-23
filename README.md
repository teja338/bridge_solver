# Bridge and Torch Problem (BFS Solution)

This project implements a Breadth-First Search (BFS) solution to the classic **Bridge and Torch Puzzle**, where a group of people must cross a bridge within a given time constraint.

---

## Problem Statement

Four individuals — **Amogh (A)**, **Ameya (M)**, **Grandmother (G)**, and **Grandfather (F)** — need to cross a bridge at night. They have **one torch** and only **two people can cross at a time**.

Each person takes a different amount of time to cross:
- `A`: 5 minutes
- `M`: 10 minutes
- `G`: 20 minutes
- `F`: 25 minutes

The torch is **required** for every crossing, and when two people cross together, they must go at the **slower person’s speed**.

### Goal:
Find a sequence of moves that gets everyone to the other side of the bridge in **60 minutes or less**.

---

## Movement Rules

- At most **2 people** can cross at a time.
- The torch must **always** be carried.
- One person must return with the torch if anyone is still on the original side.
- Total time must not exceed **60 minutes**.

---

##  Approach: Breadth-First Search (BFS)

The solution explores all possible valid moves using **BFS**, ensuring that the first found solution is optimal (if one exists within the time limit).



