# BFS vs DFS Search for Exploiting a Rock-Paper-Scissors Program

Intelligent Systems – Practical Assignment  
University of Pretoria  
Completed: May 2021

---

## Project Overview

This project investigates the use of search algorithms to exploit predictable behaviour in a Rock-Paper-Scissors program called **breakable**.

The program selects a hidden sequence of moves with a length between 2 and 5 characters. Once the correct sequence is identified, the program repeats its previous move multiple times, allowing it to be exploited.

Two classical search algorithms were implemented and evaluated:

- Breadth-First Search (BFS)
- Depth-First Search (DFS)

The goal was to determine which algorithm is able to discover the correct sequence **most consistently and in the shortest time**.

👉 **[View Full Project Report (PDF)](docs/EAI320_Practical_Assignment_1.pdf)**

---

## Objectives

- Model the problem as a **search tree**
- Implement **Breadth-First Search (BFS)** for sequence discovery
- Implement **Depth-First Search (DFS)** for sequence discovery
- Evaluate how efficiently each algorithm identifies the hidden sequence
- Compare algorithm performance across multiple sequence lengths

---

## Methodology

The possible Rock-Paper-Scissors moves:

- Rock (R)
- Paper (P)
- Scissors (S)

These moves form the branches of a **search tree**.  
Each algorithm traverses the tree differently:

**BFS**

- Explores all nodes level by level
- Guarantees the shortest solution path

**DFS**

- Explores one branch deeply before backtracking
- Uses less memory but may take longer to find optimal sequences

Both algorithms were used to generate candidate sequences and test them against the `breakable` program.

---

## Tools & Technologies

- Search algorithms (BFS, DFS)
- Graph / tree traversal
- Algorithm performance comparison
- Rock-Paper-Scissors game modelling

---

## Notes

This repository contains the original academic report submitted for the course.

The implementation code and execution logs used during testing are included in the **appendix of the report**.
