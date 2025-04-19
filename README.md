# ⚡ Peak Energy Demand Simulation & Distribution System Upgrade Proposal

This repository contains the simulation scenario, analysis, and proposed upgrade solutions for a distribution network under **peak energy demand** conditions. The analysis is conducted for both **Day Peak** and **Night Peak** scenarios.

---

## 📊 Load Scenario

- **🔌 Single-phase loads:** Each draws **0.5 kW**
- **⚙️ Three-phase loads:** Each draws **2 kW**

Simulations were conducted to observe voltage drops, loading levels, and transformer capacity under **maximum load conditions**.

---

## 📍 Network Segment Under Study

- Critical section: Between poles **PRA77 ➝ PRA70**
- Primary transformer involved: **BZ5933**

<p align="center">
  <img src="images/network_diagram.png" alt="Network Diagram" width="600"/>
</p>

---

## 🔧 Proposed System Enhancements

### 1️⃣ Upgrade of Conductor Between PRA77 and PRA70

| Parameter | Existing | Proposed |
|----------|----------|----------|
| Conductor Size | [current size] | 70 mm² ABC (additional) |
| Objective | Handle increased current, reduce losses |

- 📈 **Benefit:** Improved voltage profile and reliability

---

### 2️⃣ Addition of a New Feeder from BZ5933 Transformer

- 🧯 **Problem:** Existing feeder nearing overload during peak demand
- 💡 **Solution:** Install an additional feeder from **BZ5933**
- 🎯 **Purpose:** Load segregation, reduced feeder stress

<p align="center">
  <img src="images/feeder_addition_diagram.png" alt="New Feeder Layout" width="500"/>
</p>

---

### 3️⃣ Transformer Capacity Upgrade

| Parameter | Existing | Proposed |
|----------|----------|----------|
| Transformer Capacity | [Current rating] | **250 kVA** |

- ⚡ **Why?** Current capacity is insufficient under peak load
- 🛠️ **Upgrade Goal:** Ensure system stability and future scalability

---

## 🧠 Objective of the Project

- ✅ Minimize voltage drops under high demand
- ✅ Reduce technical losses
- ✅ Enhance load-handling capacity
- ✅ Improve long-term reliability

---

## 📁 Repository Structure

