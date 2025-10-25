# 🏠 Airbnb Data Pipeline Project

## 📄 Overview
The **Airbnb Data Pipeline Project** is a data engineering and analytics workflow designed to extract, clean, transform, and visualize Airbnb listing data. The project demonstrates the complete process of handling real-world data — from ingestion and transformation to visualization and analysis — using lightweight, open-source tools suited for small-scale or educational use.

While large-scale Airbnb analyses often rely on frameworks like Spark, BigQuery, or Hadoop, this project focuses on **simplicity, efficiency, and reproducibility** using Python and SQLite, making it accessible for classroom demonstrations and individual learners.

---

## 🎯 Objectives
- Design a small-scale **data pipeline** for Airbnb listing data.  
- Perform **data cleaning and transformation** using `pandas`.  
- Create **visualizations** to understand price, neighborhood, and room type patterns.  
- Build **interactive maps** to display geographical trends.  
- Store and query structured data efficiently using **SQLite**.  

---

## ⚙️ System Architecture & Workflow
The project follows a simple yet robust data pipeline structure:

1. **Data Ingestion:**  
   Raw Airbnb data is loaded using Python.

2. **Data Cleaning & Transformation:**  
   Performed using `pandas` — removing duplicates, handling null values, and converting data types.

3. **Data Storage:**  
   Cleaned data is stored in an **SQLite** database for efficient querying.

4. **Exploratory Data Analysis (EDA):**  
   Conducted using `matplotlib` and `seaborn` to visualize price, availability, and room type distributions.

5. **Geospatial Visualization:**  
   Implemented using `folium` to generate interactive maps showing spatial listing patterns.

6. **Insights & Reporting:**  
   The analysis highlights trends and correlations in Airbnb pricing, neighborhood popularity, and seasonal availability.

## 🖼️ System Architecture Diagram  
![System Architecture](https://github.com/Rushita-Yandapalli/team-10-FDE/blob/main/System%20architecture.jpg)

---

## ✨ Key Features
- 🧹 **Automated Data Cleaning** with `pandas`  
- 📊 **Exploratory Visualizations** using `matplotlib` and `seaborn`  
- 🗺️ **Interactive Mapping** with `folium`  
- 🧩 **Lightweight Database Integration** using `sqlite3`  
- 🔁 **Reproducible Workflow** for easy re-runs and analysis  

---

## 🧰 Technologies Used

### 💻 Programming Language
- **Python**

### 🧪 Python Libraries
- `pandas` → Data cleaning, transformation, and manipulation  
- `matplotlib` → Data visualization  
- `seaborn` → Statistical data visualization  
- `folium` → Interactive map visualization  
- `sqlite3` → Database connectivity and querying  

### 🛠️ Tools
- **Matplotlib**, **Seaborn**, and **Folium** for visualization  
- **SQLite** for structured data storage and efficient querying  

---

## 🗂️ Dataset Information
The dataset contains Airbnb listing information including:
- Listing ID, Name, Host, and Neighborhood  
- Room Type and Price  
- Number of Reviews  
- Availability and Minimum Nights  

📚 *Dataset Source:*  
[Inside Airbnb Dataset](http://insideairbnb.com/get-the-data.html)

---

## 📊 Exploratory Visualizations
Visualizations created during EDA include:
- **Price Distribution:** Histogram showing the spread of listing prices.  
- **Room Type Distribution:** Bar chart comparing proportions of room types.  
- **Top 10 Neighborhoods by Average Price:** Horizontal bar chart of the most expensive areas.  
- **Availability Trend:** Line plot showing seasonal availability.
  
---

## 🧩 Installation & Usage

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/Rushita-Yandapalli/team-10-FDE.git
cd team-10-FDE
```

---

## 🏁 Conclusion
The **Airbnb Data Pipeline Project** showcases how data engineering, analytics, and visualization can be combined to gain actionable insights from real-world data. Using Python and SQLite, the project highlights a structured yet simple approach to end-to-end data processing for educational and analytical purposes.

---

## 👩‍💻 Team Members
**Team 10 — FDE Project**

- **Mrinalini B**  
- **Rushita Yandapalli**  
- **A Bala Aditya**

---

---
