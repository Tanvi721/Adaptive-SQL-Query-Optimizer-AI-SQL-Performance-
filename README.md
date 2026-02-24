# 🚀 Adaptive SQL Performance Optimizer  
### AI-Powered Real-Time SQL Execution, Analysis & Optimization System

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python)
![MySQL](https://img.shields.io/badge/MySQL-Database-orange?style=for-the-badge&logo=mysql)
![Streamlit](https://img.shields.io/badge/Streamlit-UI-red?style=for-the-badge&logo=streamlit)
![Scikit-Learn](https://img.shields.io/badge/ML-ScikitLearn-yellow?style=for-the-badge)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen?style=for-the-badge)
![License](https://img.shields.io/badge/License-Educational-blueviolet?style=for-the-badge)

---

## 🧠 Project Overview

The **Intelligent SQL Performance Optimizer** is an AI-powered database optimization system that executes, analyzes, and improves SQL queries in real-time.

This system combines:

- 🔍 Automatic Query Type Detection  
- ⚡ Real SQL Execution Engine  
- 📊 MySQL EXPLAIN Plan Analysis  
- 🧠 Machine Learning Execution Time Prediction  
- 📌 Index Recommendation Engine  
- ✍ Query Rewrite Engine  
- 🤖 Reinforcement Learning Adaptation  
- 🗄 MySQL Real-Time Query Logging  
- 📈 Query History Dashboard  

It simulates a **Mini SQL Workbench + AI Optimizer + Enterprise Monitoring Tool**.

---

# 🖥 Project Screenshot

## 📊 SQL Optimizer Interface

> 📸 Replace the image below with your actual project screenshot if needed.

<img width="952" height="504" alt="image" src="https://github.com/user-attachments/assets/d1b9c432-9d41-4f84-91d0-96a31e5f8e3d" />
<img width="951" height="473" alt="image" src="https://github.com/user-attachments/assets/9ccd2531-d537-4804-8833-5e5439d06ace" />
<img width="960" height="434" alt="image" src="https://github.com/user-attachments/assets/e59caf5e-67e2-4aac-8c21-20a7aa1a7cf9" />
<img width="960" height="506" alt="image" src="https://github.com/user-attachments/assets/3989302e-0456-4e25-bbac-b476230da6df" />





---

# 🎥 Demo Recording

## 🚀 Real-Time SQL Optimization Demo

## 🎥 Demo Recording

▶️ Watch Demo Video:

[▶️ Watch Demo Video](Adaptive-SQL-Optimizer/demo.mp4)



---

# 🏗 System Architecture

## 📊 Architecture Diagram

> Add this image inside an `assets` folder: `assets/architecture.png`

```markdown
![Architecture Diagram](assets/architecture.png)
```

### 🔁 System Flow

```
User Query (Streamlit UI)
        │
        ▼
Automatic Query Type Detection
        │
        ├── SQL Execution Engine
        │
        ├── SELECT → MySQL EXPLAIN Plan
        │
        ├── ML Execution Time Prediction
        │
        ├── Index Recommendation Engine
        │
        ├── Query Rewrite Engine
        │
        ├── Reinforcement Learning Update
        │
        └── MySQL Real-Time Logging
                 │
                 ▼
        Query History Dashboard
```

---

# 🗄 MySQL Real-Time Data Storage

All executed queries and optimization results are stored in MySQL.

---

## 📊 Database Tables

### 1️⃣ Query Logs Table

```sql
CREATE TABLE query_logs (
    id INT PRIMARY KEY AUTO_INCREMENT,
    query_text TEXT,
    predicted_time FLOAT,
    created_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP
);
```

### 2️⃣ Optimization Results Table

```sql
CREATE TABLE optimization_results (
    id INT PRIMARY KEY AUTO_INCREMENT,
    original_query TEXT,
    optimized_query TEXT,
    index_suggestions TEXT,
    issues_detected TEXT,
    created_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP
);
```

---

## 🐍 MySQL Logging Code

```python
cursor.execute("""
INSERT INTO query_logs (query_text, predicted_time)
VALUES (%s, %s)
""", (query, predicted_time))

cursor.execute("""
INSERT INTO optimization_results
(original_query, optimized_query, index_suggestions, issues_detected)
VALUES (%s, %s, %s, %s)
""", (
    query,
    rewritten,
    str(index_rec),
    str(issues)
))

conn.commit()
```

---

# 🧠 Intelligent Query Handling

| Query Type | System Behavior |
|------------|-----------------|
| SELECT | Execute + EXPLAIN + Analyze |
| INSERT | Execute + Show rows affected |
| UPDATE | Execute + Show rows affected |
| DELETE | Execute + Show rows affected |
| CREATE | Execute + Confirm |
| ALTER | Execute + Confirm |
| DROP | Execute (with safety validation) |

---

# 🛠 Technology Stack

| Layer | Technology |
|-------|------------|
| Programming Language | Python |
| Database | MySQL |
| UI | Streamlit |
| Machine Learning | Scikit-learn |
| Query Analysis | MySQL EXPLAIN |
| Adaptive Learning | Q-Learning |

---

# 🚀 Installation & Setup

## 1️⃣ Clone Repository

```bash
git clone https://github.com/your-username/intelligent-sql-optimizer.git
cd intelligent-sql-optimizer
```

## 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

## 3️⃣ Configure Database

Update `db_connection.py`:

```python
host="127.0.0.1"
user="root"
password="your_password"
database="optimizer"
port=3306
```

## 4️⃣ Train ML Model

```bash
python model/train_model.py
```

## 5️⃣ Run Application

```bash
streamlit run app.py
```

---

# 🎯 Key Features

+ ✅ Automatic SQL Query Type Detection  
+ ✅ Real-Time Query Execution  
+ ✅ AI Execution Time Prediction  
+ ✅ MySQL EXPLAIN Plan Analysis  
+ ✅ Index Recommendation System  
+ ✅ Query Rewrite Engine  
+ ✅ Reinforcement Learning Adaptation  
+ ✅ Query History Dashboard  
+ ✅ MySQL Real-Time Data Logging  

---

# 📈 Enterprise Impact

✔ Improves database performance  
✔ Reduces full table scans  
✔ Detects missing indexes  
✔ Enables intelligent optimization  
✔ Provides real-time performance monitoring  

---

# 🔮 Future Enhancements

- PostgreSQL & Multi-DB Support  
- Cloud Deployment (AWS RDS)  
- Slow Query Alert System  
- Cost-Based Optimization Engine  
- NLP-Based SQL Rewriting  
- Role-Based Authentication  

---

# 🏢 Real-World Applications

- Enterprise Database Monitoring  
- Backend Performance Optimization  
- DevOps Query Analysis  
- AI-Driven SQL Tuning Systems  

---

# 👩‍💻 Author

**Tanvi Barve**  
Future-Ready Software & AI Engineer 🚀  
Building Intelligent Real-World AI Solutions  

---

# ⭐ If you found this project useful, consider giving it a star!
