
# 🏠 New York Airbnb Listings EDA (2024)

This project performs an Exploratory Data Analysis (EDA) on Airbnb listings from New York City to uncover patterns in pricing, availability, room types, and host behavior.

---

## 📸 **Project Visual**

![New York Panorama](images/newyork_panorama.jpg)

---

## 📦 **Project Objectives**

- Explore price trends and availability across boroughs.
- Understand room type distribution.
- Identify outliers in pricing.
- Provide insights for both hosts and guests.

---

## 📊 **Dataset Overview**

The dataset contains **20,765 listings** with 22 features, including:

- `id`: Listing ID  
- `name`: Listing title  
- `host_name`: Host's name  
- `neighbourhood_group`: Borough (Manhattan, Brooklyn, etc.)  
- `latitude` / `longitude`: Geolocation  
- `price`: Nightly price (USD)  
- `room_type`: Type of stay (Entire home, Private room, etc.)  
- `availability_365`: Available days per year  
- `reviews_per_month`: Average monthly reviews  

---

## 🛠 **Steps & Workflow**

### 1. Data Cleaning

- Handled missing values (`price`, `beds`).
- Converted columns to proper data types.
- Removed extreme outliers (listings above $1500 excluded from visualizations).

### 2. Exploratory Data Analysis (EDA)

- **Room Type Distribution**  
  Bar plots show Entire homes/apartments dominate the market.

- **Neighbourhood Group Insights**  
  Manhattan listings have the highest average prices.

- **Price Distribution**  
  Majority of listings priced between **$50 - $300**.

- **Availability & Reviews**  
  Listings with higher availability and reviews tend to be more competitively priced.

- **Outlier Detection**  
  Boxplots reveal luxury listings exceeding $10,000 per night.

---

## 🖼 **Sample Data Visualizations**

*Add your plots here by saving them in `images/` and referencing them:*

![Price Distribution](images/price_distribution.png)  
![Availability vs Price](images/availability_price.png)  

---

## 📁 **How to Run the Project**

1. Clone the repo:
   ```bash
   git clone https://github.com/indrxjith/-Airbnb-EDA.git
   cd -Airbnb-EDA
   ```

2. Install required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```

3. Run the notebook:
   ```bash
   jupyter notebook airbnbeda.ipynb
   ```

---

## 💡 **Key Insights**

- Entire homes dominate listings, private rooms are budget-friendly.
- Manhattan remains the most expensive borough.
- Some hosts operate multiple listings — trend toward professional hosting.
- High availability correlates with better guest experience and more reviews.

---

## 🚀 **Future Enhancements**

- Predict pricing using machine learning.
- Sentiment analysis on reviews.
- Build an interactive dashboard with Plotly or Tableau.

---

## 👨‍💻 **Author & Contact**

- GitHub: [indrxjith](https://github.com/indrxjith)

---

## 📄 **License**

MIT License — free to use, modify, and share.

---
