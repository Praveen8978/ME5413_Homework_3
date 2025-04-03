# ME5413 - Homework 3: Planning

## 📌 Overview

This repository contains my implementation of **global planning algorithms** for ME5413: Autonomous Mobile Robotics, specifically focused on:

- **Task 1**: A* Path Planning with obstacle inflation
- **Task 2 (Bonus)**: Optimal route to visit all four locations and return to the start

---

## 📁 Contents

- `/src/Task_1/homework3.ipynb`: Main notebook containing all tasks and results
- `map/`: Folder for input map or relevant images (if any)
- `README.md`: This file

---

## ✅ Implemented Features

- 8-connected **A*** path planner
- **Obstacle inflation** based on robot radius (0.3m)
- **Heuristic switching** (Manhattan & Euclidean)
- Pairwise shortest paths between:
  - `start`, `snacks`, `store`, `movie`, `food`
- **Brute-force** for optimal visiting order
- **Nearest Neighbor** for optimal visiting order
- **Path visualization** with matplotlib
- Runtime tracking of the algorithm

---

## 🧪 Usage

Open the notebook and run all cells:

```bash
jupyter notebook homework3.ipynb
