# Delivery Optimization using Graph Algorithms & TSP

This project demonstrates a simplified delivery optimization scenario that combines **parcel selection**, **route optimization**, **time window feasibility**, and **graph algorithms** like **Dijkstra**, **Prim MST**, and **TSP brute force**.

---

## 🚚 Problem Statement

A delivery vehicle starts from the **Warehouse** and must deliver parcels to customers while considering:

- **Distance between locations**
- **Parcel time window constraints** (delivery must happen within allowed time)
- **Vehicle weight capacity**
- **Best route to minimize travel cost**

---

## 📦 Input Modeling

### Locations and Distance Matrix
```python
locations = ['Warehouse', 'C1', 'C2', 'C3']
distance_matrix = [
    [0, 4, 8, 6],
    [4, 0, 5, 7],
    [8, 5, 0, 3],
    [6, 7, 3, 0]
]
