# 🚚 Supply Chain Optimization using Linear Programming

This project showcases how to optimize a dynamic supply chain network using **Linear Programming** with the help of the `PuLP` library. The goal is to **minimize total costs** while considering real-world constraints like traffic, inventory, reliability, and disruptions.

---

## 📂 Dataset

We use a logistics dataset (downloadable via Kaggle CLI):

- Dataset: [Logistics and Supply Chain Dataset](https://www.kaggle.com/datasets/datasetengineer/logistics-and-supply-chain-dataset)

---

## 📈 Problem Overview

- Multiple shipping routes, each with:
  - Cost
  - Traffic Congestion
  - Delay probability
  - Inventory levels
  - Disruption likelihood
- Objective: **Minimize total cost** under safe and efficient routing constraints

---

## 📦 Key Steps

1. Install libraries:
    ```bash
    pip install pulp kaggle
    ```
2. Load and filter dataset
3. Define decision variables
4. Set objective function (minimize cost)
5. Apply constraints:
   - Inventory availability
   - Traffic/disruption filtering
6. Solve using `PuLP`

---

## 💡 Optimization Output

After solving, the model provides the optimal set of routes to use, minimizing overall cost while maintaining reliability and efficiency.

---

## 📊 Tech Stack

- Python
- Pandas
- PuLP (Linear Programming)
