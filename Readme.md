# Vrinda Store Sales Python Dashboard
Python | Pandas | Plotly | Dash | Data Analysis | Data Visualization | Dashboard

## Project Overview
Welcome to my data analysis project focused on exploring and understanding sales performance for **Vrinda Store**. This project was created to analyze sales data, uncover customer trends, and generate business insights using Python.

The goal of this project is to follow a real-world data analyst workflow — from cleaning raw data to generating insights that can help support business decision-making.

This project demonstrates practical skills in:
- Data Cleaning
- Feature Engineering
- Exploratory Data Analysis (EDA)
- Data Visualization
- Static Dashboard
- Interactive Dashboard
- Business Insight Generation

Using Python-based analysis, I explored:

🔍 Sales trends across different months  
👥 Customer demographics and behavior  
📦 Order and quantity patterns  
📊 Revenue distribution  
📈 Monthly performance trends  

The analysis was performed using real-world style sales data to better understand how data can be used to support business decisions.

You can explore the full analysis, code, and visualizations inside the notebook included in this repository.

---

## Why This Project Matters

Understanding sales patterns helps businesses:
- Improve marketing
- Target customers
- Increase revenue
- Reduce returns
- Optimize operations

---

## Business Questions
Below are the key questions this project aims to answer:

- How do sales vary across different months?
- Which months generate the highest revenue?
- What is the distribution of customers by gender?
- Which age groups contribute the most sales?
- How does order quantity vary?
- What patterns exist in customer purchases?
- Are there any visible sales trends?

---

## Tools I Used
For this analysis, I used the following tools:

**Python**  
The main tool used for data analysis and data processing.

**Libraries**
- NumPy → Data processing
- Pandas → Data cleaning and analysis
- Matplotlib → Basic visualizations
- Seaborn → Statistical visualizations
- Plotly → Interactive charts
- Dash → Interactive Dashboard 

**Environment**
- Jupyter Notebook
- Kaggle

**Version Control**
- Git
- GitHub

---

## 📊 Static Dashboard

To better understand the sales performance of Vrinda Store, I created a **static dashboard** that summarizes key metrics and insights from the dataset.

The dashboard highlights:
- Monthly sales trends
- Customer distribution
- Order patterns
- Revenue analysis
- Sales performance overview

This dashboard was created using Python visualization libraries and provides a quick overview of the business performance.

### Dashboard Preview
![Static Dashboard](/Images/Vrinda%20Store%20Static%20Dashboard.png)

### Key Highlights
- Shows overall sales performance
- Displays monthly trends
- Summarizes customer behavior
- Helps identify high-performing periods

---

## 📈 Interactive Dashboard

In addition to the static dashboard, I created an **interactive dashboard** to allow dynamic exploration of the data.

The interactive dashboard allows users to:
- Filter data quarterly
- Explore trends
- Analyze customer segments
- View sales patterns
- Interact with charts

This dashboard was built to simulate a real-world business dashboard where users can explore the data interactively.

### Dashboard Preview
![Interactive Dashboard](/Images/Vrinda%20Store%20Interactive%20Dashboard.png)

### Dashboard Link
You can explore the interactive dashboard here:

🔗 **Dashboard Link:**
Run locally using `app.py` or paste the link at the web browser after run the notebook locally `http://127.0.0.1:8075`.

### Features
- Interactive charts
- Dynamic filtering
- Real-time updates
- User-friendly layout

---

## 🔍 Key Insights

- **Women contribute ~64% of total revenue**, making them the dominant customer segment.
- **Maharashtra, Karnataka, and Uttar Pradesh contribute ~36.6% of total revenue**.
- The **Adult age group (30–49 years) contributes ~50.6% of total orders**.
- **Amazon, Myntra, and Flipkart together contribute ~80.4% of total revenue**.

#### 1. Sales Momentum Weakens in Q4
- **March is the strongest month** in both revenue (**₹1.93M**) and order volume (**2,819** orders).
- **November is the weakest month** with revenue at **₹1.62M** and **2,383** orders.
- From peak (March) to low (November), revenue drops by roughly **16%**, indicating end-of-year slowdown.

#### 2. Fulfillment Performance Is Strong, but Return Leakage Exists
- **Delivered orders: ~92.3%** (28,641 out of 31,047), showing strong operational execution.
- Combined non-success outcomes (**Returned + Cancelled + Refunded**) are about **7.7%**, which is a clear optimization opportunity.

#### 3. Revenue Is Concentrated Geographically
- Top 5 states (Maharashtra, Karnataka, Uttar Pradesh, Telangana, Tamil Nadu) contribute roughly **52.6%** of total revenue.
- This indicates high regional concentration and scope to scale in underperforming states.

#### 4. Female Dominance Is Consistent Across All Age Groups
- Women contribute close to **70% of orders** in **Young**, **Adult**, and **Senior** segments.
- This consistency suggests campaigns tailored for women can be generalized across age bands with segment-specific creatives.

#### 5. Adult Segment Is the Core Growth Lever
- **Adult customers (30–49)** account for around **50.6%** of total orders.
- Protecting this segment while improving conversion in **Young (30.3%)** can create balanced growth.

---

## 🚀 Business Recommendations

---

### 🎯 Target Audience
- **Primary:** Women aged **30–49 years** (Adult segment) — highest order share (~50.6%)
- **Secondary:** Young women aged **18–29 years** — growing segment with untapped potential
- **Retention Focus:** Senior women (50+) — loyal buyers with consistent purchasing behavior

---

### 📍 Target Locations

#### 🔝 High-Priority States (Maintain & Scale)
| State | Contribution |
|-------|-------------|
| Maharashtra | Highest revenue contributor |
| Karnataka | 2nd highest revenue contributor |
| Uttar Pradesh | 3rd highest revenue contributor |

#### 📈 Growth Opportunity States (Expand & Invest)
- **Telangana** and **Tamil Nadu** — top 5 states with room to scale
- Underperforming states — launch **geo-targeted campaigns** to expand reach

---

### 🛒 Target Channels

#### 💎 Top Performing (Invest More)
- **Amazon** — Highest order share
- **Myntra** — Fashion-focused, ideal for women's category
- **Flipkart** — Broad reach across demographics

---

### 📣 Marketing Strategy

#### 🗓️ Seasonal Campaigns
- Launch **festive sales** during Q1 (Jan–Mar) to capitalize on peak revenue season
- Run **re-engagement campaigns** in Q4 (Oct–Dec) to counter the ~16% revenue dip
- Use **flash sales** and **limited-time offers** during off-peak months (Sep–Nov)

#### 💰 Promotions & Offers
- Offer **personalized coupons** for repeat customers (loyalty rewards)
- Provide **bundle discounts** on best-selling categories

#### 📱 Digital Advertising
- Run **Instagram & Facebook ads** targeting women aged 30–49 in top states
- Use **regional language creatives** for Maharashtra, Karnataka, and UP to improve CTR

#### 🔄 Reduce Return & Cancellation Rate (7.7%)
- Improve **product descriptions and sizing guides** to reduce mismatch returns
- Offer **easy exchange** instead of returns to retain revenue
- Send **order confirmation + delivery tracking** notifications to reduce cancellations

---

### 📊 Summary Action Plan

| Priority | Action | Impact |
|----------|--------|--------|
| 🔴 High | Target women 30–49 in MH, KA, UP via Amazon/Myntra/Flipkart | Revenue growth |
| 🔴 High | Launch Q4 re-engagement campaigns to reduce seasonal dip | Stabilize revenue |
| 🟡 Medium | Expand geo-targeting to Telangana & Tamil Nadu | New market growth |
| 🟡 Medium | Reduce return/cancellation rate below 5% | Revenue retention |
| 🟢 Low | Test underperforming channels with targeted offers | Channel diversification |

---

## Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Data Visualization
- Dashboard Development
- Business Analysis
- Python
- NumPy & Pandas
- Matplotlib & Seaborn
- Plotly & Dash
- Git & GitHub

--- 

## Future Improvements

- Add KPIs
- Add more filters
- Deploy Dash dashboard online

---

## What I Learned

Throughout this project, I strengthened my understanding of the data analysis workflow and improved my practical skills in Python, especially in data cleaning, analysis, and visualization. This project helped me understand how raw data can be transformed into meaningful insights.

### Data Analysis with Python
**Data Manipulation:**  
Using Pandas helped me efficiently clean and organize the dataset for analysis.

**Data Visualization:**  
Libraries like Matplotlib, Seaborn, and Plotly helped me visualize patterns and trends in the sales data.

**Feature Engineering:**  
Creating new columns such as Month and Age Group made the analysis more meaningful and easier to interpret.

### Data Cleaning and Preparation
**Data Quality:**  
I learned that cleaning data is one of the most important steps in analysis, as incorrect or messy data can lead to wrong insights.

**Data Transformation:**  
Converting data types, standardizing values, and preparing columns for analysis improved the reliability of the results.

### Business-Oriented Analysis
**Trend Analysis:**  
I learned how to analyze sales trends over time to understand business performance.

**Customer Insights:**  
Analyzing customer demographics helped me understand purchasing patterns.

**Dashboard Creation:**  
Building static and interactive dashboards helped me present insights in a clear and visual way.

Overall, this project improved my understanding of how data analysis can support business decisions and strengthened my foundation in Python-based data analysis.

---

## Challenges I Faced

This project presented several challenges that helped me learn and improve my problem-solving skills:

### Data Cleaning Issues
Some columns contained inconsistent values that needed to be standardized before analysis. Cleaning and transforming the data required careful attention to avoid errors.

### Data Type Conversion
Converting columns such as dates and quantities into the correct format was necessary for proper analysis and visualization.

### Creating Meaningful Visualizations
Choosing the right charts to represent the data clearly was challenging, but it helped me understand how visualization improves data storytelling.

### Dashboard Design
Designing dashboards that clearly present insights while keeping them simple and readable required multiple adjustments and improvements.

---

## Conclusion

This project demonstrates a complete data analysis workflow, from raw data cleaning to visualization and dashboard creation. By analyzing Vrinda Store sales data, I was able to identify patterns in sales performance and customer behavior.

The project helped me strengthen my skills in Python, data analysis, and visualization while also improving my ability to generate business insights from data.

Overall, this project serves as a strong foundation for future data analytics projects and reflects my ability to work with real-world datasets and analytical tools.
