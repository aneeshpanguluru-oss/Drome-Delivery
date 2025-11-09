# 🚁 Drone Delivery Route Optimizer

A Python + MySQL project that finds the **shortest delivery route** for a drone using the **BFS algorithm**, supporting **8-directional movement** (horizontal, vertical, diagonal) and **dynamic cost calculation**.

---

## ✨ Features
- Finds the **shortest route** between two coordinates using **BFS (Breadth-First Search)**  
- Supports **diagonal movement** with **√2 ≈ 1.414** distance factor  
- Calculates **total delivery cost** based on distance  
- Automatically stores results in **MySQL** database  
- Separates **successful** and **failed** deliveries  
- Uses **NumPy** for grid creation and data handling  

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

### 1️⃣ Clone the repository
```bash
git clone https://github.com/aneeshpanguluru-oss/Drone-Delivery.git
cd Drone-Delivery

