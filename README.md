# 🧩 RFM Customer Segmentation — SQL Project
---

## 🧠 **Project Overview**

This project demonstrates how to perform **RFM (Recency, Frequency, Monetary)** analysis using SQL.  
It segments customers based on their purchase behavior, helping businesses understand **customer value**, **loyalty**, and **engagement patterns**.

The analysis follows three key principles:

| Metric | Meaning | SQL Logic |
|:--|:--|:--|
| **Recency (R)** | How recently a customer purchased | `DATEDIFF(MAX(OrderDate), NOW())` |
| **Frequency (F)** | How often a customer purchased | `COUNT(OrderID)` |
| **Monetary (M)** | How much a customer spent | `SUM(TotalAmount)` |

---

## 📁 **Project Structure**

| Folder | Description |
|:--|:--|
| 📂 **sql/** | Contains the main SQL script for RFM analysis (`RFM PROJECT.sql`) |
| 📂 **docs/** | Contains project documentation (`SQL Project.pdf`) |
| 📜 **README.md** | This file — contains project overview and usage instructions |
| ⚖️ **LICENSE** | MIT License for open usage |
| ⚙️ **.gitattributes** | Maintains consistent file formatting |

---

## ⚡ **How to Run the Project**

1. **Clone the repository**
   ```bash
   git clone https://github.com/<your-username>/rfm-customer-segmentation-sql.git
   cd rfm-customer-segmentation-sql
