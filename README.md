## 📦 Food Delivery Data Analysis

### 🔍 Project Overview

This project demonstrates a real-world **data engineering and analytics workflow** by integrating multiple data sources in different formats (CSV, JSON, and SQL). The goal is to create a unified dataset for analyzing customer behavior, restaurant performance, and order trends in a food delivery platform.

---

### 📁 Datasets Used

* **orders.csv** – Transactional order-level data
* **users.json** – User master data
* **restaurants.sql** – Restaurant master data (SQL schema + records)

---

### 🛠️ Tech Stack

* **Python**
* **Pandas**
* **SQLite**
* **Jupyter Notebook**

---

### 🔄 Data Processing Steps

1. Load transactional data from CSV
2. Load user data from JSON
3. Execute SQL script and extract restaurant data
4. Perform **LEFT JOINs** to retain all orders:

   * `orders.user_id → users.user_id`
   * `orders.restaurant_id → restaurants.restaurant_id`
5. Generate a final consolidated dataset

📁 **Output:** `final_food_delivery_dataset.csv`

---

### 📊 Key Analysis Use Cases

* Order trends over time
* User behavior patterns
* City-wise and cuisine-wise performance
* Gold vs Regular membership impact
* Revenue distribution and seasonality

---

### 🚀 Project Highlights

✔ Handles multi-format data ingestion
✔ Real-world join logic and data modeling
✔ Clean, modular, interview-ready code
✔ Scalable foundation for EDA & dashboards

---

### 📌 How to Run

```bash
pip install pandas
```

Open the Jupyter Notebook and run cells sequentially to generate the final dataset.

---

### 🧠 Skills Demonstrated

* Data Engineering (ETL pipeline)
* SQL + Python integration
* Data merging and validation
* Analytical thinking & problem solving

---

### 📎 Author

**Vidya Gadhave**

---
