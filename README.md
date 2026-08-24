# 🍴 Zomato Data Analysis

## 📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on the Zomato restaurant dataset to uncover patterns in restaurant ratings, pricing, cuisines, online delivery, table booking, customer engagement, and geographical distribution.

The analysis focuses on understanding restaurant performance and deriving actionable business insights from the data.

## 🎯 Objectives

- Analyze restaurant ratings and customer engagement
- Understand pricing patterns and their relationship with ratings
- Analyze online delivery and table booking availability
- Identify top-performing cuisines
- Understand restaurant distribution across cities
- Identify data quality issues and opportunities for improvement
- Generate actionable business insights

## 📁 Project Structure

```text
zomato-data-analysis/
│
├── Zomato_EDA.ipynb       # Exploratory Data Analysis notebook
├── zomato.csv             # Original/raw dataset
├── zomato_clean.csv       # Cleaned dataset
└── README.md              # Project documentation
```


## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

## 📂 Dataset

The dataset contains information about restaurants, including:

- Restaurant name
- Location and city
- Cuisine
- Price range
- Aggregate rating
- Votes
- Online delivery availability
- Table booking availability
- Currency

The dataset contains restaurants from multiple countries.

## 🧹 Data Cleaning

The data cleaning process included:

- Handling missing values
- Removing unnecessary columns
- Checking duplicate records
- Converting data types where required
- Cleaning and standardizing categorical values
- Creating a cleaned dataset for further analysis

## 🔍 Exploratory Data Analysis

The analysis explored:

### Restaurant Ratings
Analyzed rating distributions and identified restaurants with missing/not-rated values.

### Online Delivery
Compared restaurant ratings based on online delivery availability.

### Table Booking
Analyzed the relationship between table booking availability and restaurant ratings.

### Price Range
Compared ratings across different price ranges and examined the relationship between cost and ratings.

### Customer Engagement
Analyzed the relationship between votes and restaurant ratings.

### Cuisines
Identified the highest-rated cuisines while considering restaurants with sufficient representation.

### City Distribution
Analyzed the geographical concentration of restaurants.

## 💡 Key Insights

### 1. Ratings Gap

**22.49%** of restaurants are "Not Rated", highlighting an opportunity to encourage customers to submit ratings and reviews.

### 2. Online Delivery

Only **25.66%** of restaurants offer online delivery. Restaurants with online delivery have an average rating of **3.25**, compared with **2.47** for restaurants without it.

### 3. Table Booking

Only **12.12%** of restaurants offer table booking. Restaurants offering table booking have an average rating of **3.44**, compared with **2.56** for those without it.

### 4. Price and Ratings

The most expensive price range has an average rating of **3.89**, compared with **3.24** for the cheapest range.

However, the correlation between price and rating is only **0.08**, indicating that higher prices alone do not guarantee better ratings.

### 5. Votes and Ratings

Votes have a correlation of **0.41** with ratings, suggesting that customer engagement is associated with restaurant rating performance.

### 6. Top Cuisines

Among cuisines with at least 20 restaurants:

- Italian — **3.95**
- American — **3.92**
- Mexican — **3.85**

North Indian cuisine is the most common, with **936 restaurants**, indicating a highly competitive segment.

### 7. Market Concentration

**New Delhi, Gurgaon, and Noida** account for more than **77%** of restaurants in the dataset, indicating strong geographical concentration.

## 📈 Business Recommendations

- Encourage customers to leave ratings and reviews.
- Promote online delivery adoption among restaurants.
- Increase awareness and adoption of table booking.
- Focus on service and quality rather than relying only on premium pricing.
- Help new restaurants build early customer engagement and reviews.
- Identify opportunities in underrepresented cuisines and markets.
- Explore tier-2 cities as potential expansion markets where competition may be lower.

## 🚀 Future Scope

- Build an interactive **Power BI dashboard**
- Add business KPIs and interactive visualizations
- Perform SQL-based analysis
- Create deeper customer and restaurant segmentation
- Develop predictive models for restaurant ratings or performance
- Extend the analysis with more recent Zomato data

## 📌 Data Quality Note

The dataset contains restaurants from multiple countries and currencies. For India-specific cost and rating comparisons, filtering the dataset using:

`Currency = "Indian Rupees(Rs.)"`

can provide more consistent comparisons.

## 👩‍💻 Author

**Vaishnavi Dethe**
