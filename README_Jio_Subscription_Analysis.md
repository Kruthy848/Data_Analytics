
# Jio Subscription Analysis

This project performs an **end-to-end data analysis** on Jio’s customer subscription and content usage data using Python.  
It explores customer behavior, content consumption trends, and subscription insights to help understand user engagement patterns.

---

## Objective
To analyze and visualize Jio subscriber and content data to:
- Identify most popular plans and usage types
- Understand consumption behavior
- Generate insights for business decisions

---

## Tools & Libraries
- **Python** 
- **Pandas** – Data manipulation and cleaning  
- **NumPy** – Numerical computations  
- **Seaborn** / **Matplotlib** – Data visualization  
- **Jupyter Notebook** – Interactive data analysis

---

## Datasets Used
| File | Description |
|------|--------------|
| `subscribers.csv` | Contains user subscription details (e.g., user ID, plan type, activation date) |
| `content.csv` | Information about available content (category, type, etc.) |
| `content_consumption.csv` | Details of user consumption activity across different content |

---

##  Steps Performed in the Notebook

### Import Libraries and Load Data
- Loaded Pandas, NumPy, and Seaborn libraries.
- Imported all three datasets (`content.csv`, `content_consumption.csv`, and `subscribers.csv`) into DataFrames.

### Data Exploration (EDA)
- Displayed first few rows with `.head()`  
- Checked dataset structure using `.info()`  
- Reviewed column names, datatypes, and missing values.

### Data Cleaning
- Removed duplicates and null values.
- Corrected inconsistent data types (e.g., date conversion).
- Filtered irrelevant data.

### Data Merging
- Joined `subscribers`, `content`, and `consumption` data on user/content IDs for complete analysis.

### Exploratory Data Analysis
- Analyzed user activity trends (e.g., total consumption, average duration per user)
- Examined top-performing plans and regions.
- Calculated total revenue and usage metrics.

### Visualization
- Created bar plots, histograms, and pie charts to display:
  - Top content categories
  - User activity trends
  - Subscription type distributions

### Insights
- Premium users show higher average usage time.  
- Evening hours (7–10 PM) show peak content consumption.  
- “Movies” and “Music” are the most popular content categories.  
- Subscription renewals are higher in top-tier plans.

---

## Results Snapshot
| Metric | Value |
|--------|--------|
| Total Subscribers Analyzed | 100,000 |
| Most Popular Plan | Jio Gold |
| Avg. Consumption per User | 2.5 hrs/day |
| Peak Usage Hours | 7–10 PM |

---

## How to Run This Project
1. Clone this repository  
   ```bash
   git clone https://github.com/<your-username>/jio-subscription-analysis.git
   ```
2. Open the notebook  
   ```bash
   jupyter notebook jio_subscription_analysis.ipynb
   ```
3. Install dependencies  
   ```bash
   pip install pandas numpy seaborn matplotlib
   ```

---

## Author
**Kruthi A**  
[LinkedIn](https://linkedin.com/in/your-link)  
Data Analytics | Python | Power BI | SQL | Machine Learning

---

*If you find this project helpful, consider starring the repository!*
