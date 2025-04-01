# 🚚 Three-Echelon Supply Chain Optimization – Python Model

This project models and solves a **three-echelon transportation problem** for a book distribution network. The objective is to minimize the shipping cost from warehouses → distribution centers → stores, based on a custom cost matrix derived from a random generator tied to the engineer's ID.

---

## 🧠 Problem Overview

- **Warehouses:** Tonoz, White Kiosk, Quarterage, Middle Yard  
- **Distribution Centers:** Atlas, Nebulae, Azure  
- **Stores:** Venus, Minerva, Neptunus, Mars, Ceres

Books can be sent:
- Directly from warehouses to stores
- From warehouses → distribution centers → stores

---

## ⚙️ Tools & Libraries

- Python
- Jupyter Notebook
- PuLP (CBC solver)
- Numpy / Pandas
- LaTeX (for final report)

---

## 📊 Project Components

| Notebook | Description |
|----------|-------------|
| `RandomNumberGenerator.ipynb` | Generates cost values based on student ID |
| `Model_1.ipynb`               | Builds and solves the initial transportation model |
| `Model_2.ipynb`               | Performs scenario analysis by changing warehouse/store capacities and costs |

---

## 📁 File Structure

- `notebooks/`: Python notebooks for modeling and simulation
- `report/`: Problem definition and questions (`SecondPart_v2.pdf`)
- `README.md`: Project documentation

---

## 📈 Objective

Minimize the total shipping cost while:
- Meeting store demands
- Respecting warehouse capacities
- Allowing flow through intermediate distribution centers

---

## 🔄 Scenario Analysis

1. **Modified warehouse and store capacities**
2. **Changed shipment costs**
3. **Model feasibility under tighter constraints**

---

## 👨‍💻 Engineer ID

This solution is customized based on the student ID: `YOUR_ID_HERE`  
The cost matrix is generated accordingly using the provided random number generator.

---

## 🧾 Report

See `report/Report.pdf` for the full problem background and modeling requirements.

---

> This project demonstrates how mathematical modeling and optimization can be used to solve real-world supply chain problems with Python.
