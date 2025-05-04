# 💄 Sephora Skincare Products & Reviews Analysis

This project analyzes a large-scale dataset of **Sephora skincare products and user reviews** to uncover insights into product performance, customer sentiment, brand popularity, and pricing trends. It combines **data cleaning**, **exploratory analysis**, **text mining**, and **visual storytelling** to help both consumers and businesses understand what makes a product successful.

---

## 📦 Dataset Overview

The dataset was collected in **March 2023** using a Python scraper and includes:

### 🛍️ Product Information
- 8,000+ beauty and skincare products from Sephora
- Fields include: product name, brand, price, ingredients, rating, product type

### 💬 User Reviews
- ~1 million reviews for 2,000+ skincare items
- Each review includes: user appearance (e.g. skin type), rating, title, text

---

## 🔍 Key Features

### 📊 Exploratory Data Analysis (EDA)
- Analyze product categories, brand popularity, and price trends
- Understand ingredient frequency and pricing correlations

### 😄 Sentiment Analysis
- Classify review sentiment (positive, neutral, negative)
- Identify brands and products with the strongest/weakest customer feedback

### ✍️ Text Mining
- Extract most common words and themes from user reviews
- Identify common complaints and compliments

### 🤖 Recommender System (Planned)
- Recommend skincare products based on user preferences and review history

### 📈 Data Visualization
- Bar charts, histograms, and word clouds for quick insights
- Interactive dashboards with Tableau / Looker Studio (coming soon)

---

## 🧪 Example Visualization

![Brand Popularity](assets/brand_popularity_barplot.png)

> 📊 Bar chart of the most-reviewed skincare brands on Sephora

---

## 💻 Technologies Used

- `pandas`, `numpy`, `matplotlib`, `seaborn` — data wrangling & plotting  
- `NLTK` / `TextBlob` — sentiment analysis  
- `scikit-learn` — future ML modeling  
- `Tableau` / `Looker Studio` — dashboard visualization  
- `Python scraper` (requests + BeautifulSoup) — data collection  

---

## 🚀 How to Run

1. Clone this repository  
2. Install requirements: `pip install -r requirements.txt`  
3. Run notebooks in `/notebooks/` for EDA and sentiment analysis  
4. Visualizations are saved in `/assets/`

---

## 🧠 Project Ideas

- Build a **product rating predictor** using review sentiment and ingredients
- Create a **customer profile clustering** based on preferences
- Deploy a **product recommender API** using Flask or Streamlit

---

## 👩‍💻 Author

Made with 💜 by [@danaabdi](https://github.com/danaabdi)  
tableau link (https://public.tableau.com/app/profile/dana.abdirakhym6361/viz/sephora_17462112384150/Sheet10)
Feel free to ⭐ the repo or open an issue for collaboration ideas!

