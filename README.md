
# 🏡 Airbnb EDA Project – [City/Region Name] (Python)

This project focuses on performing **Exploratory Data Analysis (EDA)** on Airbnb listings to understand the dynamics of the short-term rental market in New York City. Using Python and powerful data analysis libraries, we uncover insights about pricing, availability, location trends, and more.

---

## 📌 Project Overview

- Analyze Airbnb listing data to extract meaningful insights
- Understand key features affecting price and availability
- Identify patterns in location, reviews, and room types
- Visualize findings using interactive and static charts

---

## 🧰 Tools & Technologies

- **Pandas** – data manipulation  
- **NumPy** – numerical operations  
- **Matplotlib & Seaborn** – static data visualization  
- **Jupyter Notebook** – project development and documentation

---

## 🔄 Workflow Steps

### 1. **Data Cleaning**
- Handled missing values (`price`, `neighborhood`, `beds`)
- Converted `last_review` to datetime
- Removed outliers (capped prices > $1,000)

### 2. **Exploratory Data Analysis (EDA)**
- **Room Types**: Entire homes/apartments most common  
- **Neighborhoods**: Manhattan has highest average prices  
- **Availability**: High availability correlates with lower prices and more reviews  
- **Pricing**: Most listings fall between $50–$300  
- **Hosts**: Some manage multiple listings (professional hosts)  
- **Reviews**: Explored relationships with price and availability  

### 3. **Visualizations Used**
- Bar charts, histograms, boxplots, heatmaps, pairplots

---

## 📌 Key Insights

- **Manhattan** is the most expensive borough  
- **Entire homes/apartments** dominate listings and cost more  
- **Outliers** (e.g. $10,000+ listings) skew data and need filtering  
- **High availability** listings are often cheaper and better reviewed  
- **Multiple-listing hosts** show a shift toward commercial use
