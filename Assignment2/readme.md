# Best-First Search vs A* Search

## 🔹 Best-First Search (Greedy Best-First)
- Expands the node that appears closest to the goal using **heuristic `h(n)`**.
- Ignores the actual path cost `g(n)`.
- Faster but may follow a wrong/longer path.
- **Not optimal** (may not give shortest path).
- **Not complete** (can miss solutions).

---

## 🔹 A* Search
- Expands the node with the lowest **`f(n) = g(n) + h(n)`**.
- Considers both path cost (`g(n)`) and heuristic (`h(n)`).
- **Always finds the optimal path** if the heuristic is admissible.
- **Complete** (finds solution if one exists).
- Slower compared to Best-First due to more exploration.

---

