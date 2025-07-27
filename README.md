# A* Pathfinding Visualizer 🔍🧭

This repository contains an implementation of the A* (A-Star) pathfinding algorithm in Python, using a visual maze environment. It simulates node expansion and optimal path search using both Manhattan and Euclidean heuristics.

---

## 🚀 Features

- A* algorithm implementation from scratch  
- Maze generation and visualization  
- Option to toggle between Manhattan and Euclidean distances  
- Visualization of search process and final path  

---

## 🧠 Algorithms

- **A* Search**: Uses cost function `f(n) = g(n) + h(n)` to explore the shortest path.  
- **Heuristics**:
  - Manhattan Distance  
  - Euclidean Distance  

---

## 📁 Files

- `astar.py` – Main script with the search algorithm.  
- `maze_2.py` – Maze environment for testing the algorithm.  
- `README.md` – Documentation and guide.  

---

## 📸 Demo

_A GIF or image of your maze and path would be perfect here once available._

---

## ⚙️ Requirements

- Python 3.x  
- `matplotlib` and `numpy`

Install dependencies:

```bash
pip install numpy matplotlib
````

---

## 🧪 How to Run

Clone the repository:

```bash
git clone https://github.com/yourusername/AStar-Pathfinding-Visualizer.git
cd AStar-Pathfinding-Visualizer
```

Make sure `maze_2.py` is in the same directory.

Run the script:

```bash
python astar.py
```

To toggle between different maps:

```python
m = Maze(map_num=1)  # Change 1 to 2 to use a different map
```

---

## ✍️ Author

**Ashok Kumar Meena**
BTech, Electrical Engineering
IIT Madras | Firmware Developer @ Ather Energy
GitHub: [github.com/yourusername](https://github.com/yourusername)

---

## 📜 License

MIT License.

