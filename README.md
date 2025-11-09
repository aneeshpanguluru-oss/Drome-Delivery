# 🚁 Drone Delivery Route Optimizer

A Python + MySQL project that finds the **shortest delivery route** for a drone using the **BFS algorithm**, supporting **8-directional movement** (horizontal, vertical, diagonal) and **dynamic cost calculation**.

---

## ✨ Features
- Finds the **shortest route** between two coordinates using **Breadth-First Search (BFS)**
- Supports **diagonal movement** (distance √2 ≈ 1.414)
- Calculates **total delivery cost** based on user-defined cost per unit distance
- Stores all results automatically in **MySQL**
- Separates **successful** and **failed** deliveries
- Uses **NumPy** for efficient grid handling

---

## 🧱 Tech Stack
| Component | Technology |
|------------|-------------|
| **Programming Language** | Python 3.x |
| **Database** | MySQL 8.x |
| **Libraries** | NumPy, mysql-connector-python |
| **Algorithm** | Breadth-First Search (BFS) |

---

## ⚙️ Setup Instructions

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/aneeshpanguluru-oss/Drone-Delivery.git
cd Drone-Delivery
