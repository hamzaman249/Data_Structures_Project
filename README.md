# MayDay-404: Real-Time Console Aviation Simulator

**Course:** CL2001 Data Structures, BSCS 3 Fall 2026
**University:** FAST-NUCES, Faisalabad-Chiniot Campus
**Section** 3E_BSCS

---

## Team Members

| Name | Roll No. |
|---|---|
| Hamza Mansoor | 25F-0579 |
| Hamna Shehzadi | 25F-0536 |
| Syed Ashal Haider | 25F-0543 |

---

## About the Game

MayDay-404 is a single-player, menu-driven Air Traffic Control game. You are the **Chief Routing Officer (CRO)** managing BlackBox Airline during an island-wide air emergency.

- Each turn is **1 tick (30 simulated seconds)**.
- You get **2 actions per turn**.
- Survive **30 ticks** with no crash, hijack, cyber breach, or war failure to win.
- Credibility starts at 100. If it reaches 0, you lose.

All data structures are built from scratch. **No STL is used.**

---

## Data Structures Used

| Module | Class | Data Structure |
|---|---|---|
| 1 | Registration | Singly linked list, hash table (linear probing) |
| 2 | EmergencyLanding | Queue (normal arrivals), min-heap (emergencies) |
| 3 | CommandHistory | Doubly linked list, stack (undo) |
| 4 | BSTflight | Binary search tree |
| 5 | AVLflight | AVL tree |
| 6 | SpaceGraph | Adjacency list and adjacency matrix |
| 7 | RadarSweep | BFS (queue), DFS (stack) |
| 8 | RouteFinder | Dijkstra with min-heap |
| 9 | RadarMST | Kruskal (union-find) or Prim (min-heap) |
| 10 | GameEngine | Integration of all modules |
| 11 | LeaderBoard | File I/O |

---



## How to Play

1. Choose **New Game** and enter your name (use `_` or `.` instead of spaces).
2. Each turn, choose up to 2 actions from the game menu.
3. Viewing options (13, 14, 15, 16, 22) are free.
4. Option **23** ends the turn early.
5. Wrong commands cost credibility.
6. Survive 30 ticks to win. Your result is saved to the leaderboard.

---



