# **Dynamic Network Routing Simulation Using Dijkstra's Algorithm**

## **Overview**

This project simulates dynamic network routing using **Dijkstra's Algorithm**. The system efficiently computes the shortest path between nodes in a weighted graph, which can represent a network of interconnected devices or routers. The simulation adapts dynamically to changes in network conditions, such as the addition or removal of nodes and edges, or weight adjustments.

---

## **Features**

- Implementation of **Dijkstra's Algorithm** for shortest-path computation.
- Dynamic updates to the graph (add/remove nodes and edges).
- Visualization of the network and routing paths.
- Performance metrics for pathfinding efficiency.
- Supports simulation of real-world scenarios such as network failures or congestion.

---

## **Technologies Used**

- **Programming Language:** Python
- **Libraries:** 
  - For Python: `networkx`, `matplotlib`, etc.
- **Development Tools:** Git, IDE (VS Code)

---

## **Getting Started**

### **Prerequisites**

Ensure you have the following installed:

- Python
- Git
- Required libraries or dependencies:
  - For Python: Install using `pip install networkx`.
  - For Puthon: Install using `pip install matplotlib`.



## **Usage**

1. Run the main script:
   ```bash
   python main.py  # For Python
   ```
   
2. Follow the on-screen instructions to:
   - Visualize the network graph.
   - Update nodes and edges dynamically.
   - Compute and display the shortest paths.

3. Explore scenarios like:
   - Adding new routes (edges).
   - Simulating link failures.
   - Measuring rerouting times.

---


## **Example**

Input Graph:
```
A --2--> B --3--> C
|         |         |
5         4         6
|         |         |
D --1--> E --2--> F
```

Shortest Path from A to F:
```
Initial optimal route: A → B → C → F
Route Cost: 11

```

## **Acknowledgment**
This project was developed as part of the Dynamic Algorithms and Applications course.

---
