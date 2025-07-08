# OPTIMIZATION-MODEL
# 🧮 Business Optimization Model: Furniture Production (Using Linear Programming)

"COMPANY" : CODTECH IT SOLUTIONS

"NAME" : Vuppala Manoviraj

"INTERN ID" : CT04DG410

"DOMAIN" : DATA SCIENCE

"DURATION" : 4 WEEKS

"MENTOR" : NEELA SANTOSH

## 📌 Overview

This project solves a business problem for a fictional company, **ABC Furniture Co.**, which manufactures **chairs** and **tables**. The goal is to **maximize profit** using **Linear Programming (LP)**, subject to **limited resources** (wood and labor).

The optimization is implemented using Python and the **PuLP** library, along with a **visualization of constraints and the feasible region** using **Matplotlib**.

---

## 🚀 Problem Statement

ABC Furniture Co. manufactures:
- **Chairs** (₹45 profit per unit)
- **Tables** (₹80 profit per unit)

Subject to:
- **Wood Constraint:** 400 units/week
- **Labor Constraint:** 450 hours/week

Each product consumes:
| Product | Wood (units) | Labor (hours) |
|---------|---------------|----------------|
| Chair   | 5             | 10             |
| Table   | 20            | 15             |

### Objective:
Maximize profit:
\[
Z = 45x + 80y
\]

---

## ✅ Solution Summary

| Output                     | Value         |
|---------------------------|---------------|
| Optimal Chairs to Produce | 24 units      |
| Optimal Tables to Produce | 14 units      |
| Maximum Profit            | ₹2200         |
| Wood Used                 | 400 units     |
| Labor Used                | 450 hours     |

All constraints are satisfied, and resources are fully utilized.

---

## 📦 Tools & Libraries

- **Python 3.x**
- [PuLP](https://pypi.org/project/PuLP/) — LP modeling and solver
- **Matplotlib** — Plotting constraints and feasible region
- **NumPy** — Numerical calculations for plotting

---

## 🔧 Installation

Clone this repo or download the `.ipynb` notebook. Then install dependencies using:

```bash
pip install pulp matplotlib numpy
```

## 📊 Visualization

The notebook includes:

- Constraint plots (wood, labor)

- Feasible region

- Optimal solution marked on the graph

- Optional iso-profit line

## 🔍 Insights & Recommendations

- Produce 24 chairs and 14 tables weekly for maximum profit of ₹2200.

- Both wood and labor are fully utilized.

- To further scale, consider:

  - Hiring more labor or sourcing more wood.

  - Introducing new products to use idle capacity if it arises.

## 📈 Future Scope

- Add demand limits per product

- Include storage or transportation costs

- Handle multiple factories (multi-constraint LP)

- Perform sensitivity analysis or dual LP
