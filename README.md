# ⚡ 2PC vs 3PC Visualizer

An interactive simulation of the **Two-Phase Commit (2PC)** and **Three-Phase Commit (3PC)** protocols used in distributed systems.

🔗 Repo: https://github.com/mafrinwritescode/2pc_3pc

---

## 🎯 What This Project Does

This visualizer demonstrates how distributed nodes coordinate to reach agreement, and what happens when things go wrong.

It focuses on:
- Normal commit/abort flows
- Timeout handling
- Failure recovery
- The **blocking deadlock problem in 2PC**
- How **3PC solves it**

---

## 💀 Key Highlight

> When all participants are in READY and the coordinator crashes,  
> the system **cannot commit or abort** → leading to **blocking deadlock**.

This project visually explains *why that happens*.

---

## 🧠 Features

- 🎮 Scenario-based simulation
- 📊 Real-time protocol logs
- 🎬 Smooth animations for message passing
- ⚠️ Failure + recovery visualization
- 🔍 Deep insight into distributed consensus

---

## 🧩 Concepts Covered

- Two-Phase Commit (2PC)
- Three-Phase Commit (3PC)
- Coordinator & Participants
- READY state and locking
- Blocking vs Non-blocking systems

---

## 🛠️ Tech Stack

- HTML
- CSS
- JavaScript (Vanilla)

---

## 🚀 Live Demo

👉 (Add your Netlify / GitHub Pages link here)

---

## ▶️ How to Run

1. Clone the repo:
```bash
git clone https://github.com/mafrinwritescode/2pc_3pc.git
