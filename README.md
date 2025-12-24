# Top-Instagram-Influencers-Data-
Interactive dashboard analyzing cleaned data of top Instagram influencers to uncover insights on followers, engagement, categories, and country-wise performance.
# 📊 Top Instagram Influencers Data (Cleaned) – Tableau Dashboard

## 📌 Project Overview
This project analyzes **Top Instagram Influencers** using cleaned data to understand influencer performance based on followers, engagement rate, influence score, and geographic distribution. The analysis is visualized through **interactive Tableau dashboards and a Tableau Story**, providing actionable insights for marketing and business decisions.

The project focuses on identifying high-engagement influencers, comparing performance across countries, and understanding relationships between followers, likes, and engagement.

---

## 🎯 Objectives
- Analyze top Instagram influencers based on followers and influence score
- Identify influencers with high engagement rates
- Compare influencer performance across countries
- Study relationships between followers, likes, and engagement
- Present insights using interactive dashboards and Tableau storytelling

---

## 🧰 Tools & Technologies
- **Tableau Desktop** – Dashboard creation & storytelling  
- **Microsoft Excel** – Data cleaning and preprocessing  
- **SQL (Optional)** – Data validation  

---

## 📁 Project Files
├── Top Instagram Influencer data(code).twb
├── Tableau Project Report – Top Instagram Influencers Dashboard.pdf
├── README.md


---

## 📊 Dataset Description
The dataset contains information about top Instagram influencers worldwide, including:

- Rank  
- Channel Info (Username)  
- Influence Score  
- Number of Posts  
- Followers  
- Average Likes  
- Engagement Rate (Last 60 Days)  
- New Post Average Likes  
- Total Likes  
- Country  

The data was cleaned and standardized before importing into Tableau.

---

## 🧹 Data Cleaning & Preparation
- Removed null and inconsistent values  
- Converted numeric fields (followers, likes, influence score)  
- Standardized engagement rate as a percentage  
- Renamed columns for clarity  
- Verified country names for accurate geographic mapping  

---

## 📌 Key Performance Indicators (KPIs)
- Total Influencers  
- Total Followers  
- Average Influence Score  
- Average Engagement Rate  
- Average Likes per Post  
- Total Likes  
- Top Influencer by Influence Score  
- Country with Highest Number of Influencers  

---

## 🧮 Calculated Fields Used
- **Engagement Rate**  
  `(avg_likes / followers) * 100`

- **Growth in New Post Likes**  
  `(new_post_avg_like - avg_likes) / avg_likes * 100`

- **Like-to-Follower Ratio**  
  `total_likes / followers`

---

## 📈 Dashboards Included
### 1️⃣ Influencer Overview
- KPI tiles
- Top 10 influencers by influence score
- Country-wise influencer count

### 2️⃣ Engagement Analysis
- Followers vs Average Likes (Scatter Plot)
- Engagement rate comparison
- Country and influencer filters

### 3️⃣ Country-wise Performance
- Map visualization
- Average engagement rate by country
- Like-to-follower ratio analysis

### 4️⃣ Rank & Trend Insights
- Heatmap of engagement by rank and country
- Comparison of new vs average likes
- Engagement trends for the last 60 days

### 5️⃣ Engagement & Influence Analysis
- Histogram of average likes
- Box plot of influence score distribution

---

## 📖 Tableau Story
A Tableau Story combines all dashboards into a logical flow:
- Influencer overview
- Engagement comparison
- Country-based insights
- Identification of high-growth influencers
- Engagement & influence analysis

This improves storytelling and presentation clarity.

---

## 📌 Key Insights
- High follower count does not always mean high engagement
- Some mid-ranked influencers show strong engagement growth
- USA and India have the highest number of top influencers
- Micro-influencers often provide better engagement ratios

---

## 💼 Business Use Cases
- Influencer marketing campaign selection
- Brand partnership decisions
- Regional marketing strategies
- Identifying rising and high-engagement influencers

---

## 🚀 Conclusion
This project demonstrates how **Tableau dashboards and storytelling** can transform cleaned social media data into meaningful insights. It highlights strong skills in **data cleaning, KPI creation, dashboard design, and business analysis**, making it suitable for Business Analyst and Data Analyst portfolios.

---

## 🔮 Future Enhancements
- Add time-series analysis for follower growth
- Perform sentiment analysis on comments
- Integrate real-time Instagram API data
- Apply clustering techniques to group influencers

---


