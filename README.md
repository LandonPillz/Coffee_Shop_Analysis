# Coffee & Cream: Power BI Sales Dashboard (2023)

**Coffee & Cream** is a fictional local bakery and coffee shop analyzing its sales performance for the year 2023. Using a cleaned version of the “Dirty Cafe Sales” dataset from Kaggle, I developed a Power BI dashboard that provides actionable insights into revenue, costs, profit trends, and customer behavior.

> This project demonstrates data cleaning, DAX modeling, visual storytelling, and business scenario analysis.

<img width="1325" height="742" alt="Image" src="https://github.com/user-attachments/assets/a6dae278-b58d-4e28-99cd-65610984e72d" />

## Dataset Overview

- **Source**: [Dirty Cafe Sales Dataset (Kaggle)]([https://www.kaggle.com/datasets](https://www.kaggle.com/datasets/ahmedmohamed2003/cafe-sales-dirty-data-for-cleaning-training))
- **Rows**: 10,000
- **Columns**: 8
- **Timeframe**: January–December 2023
- **Type**: Synthetic transactional data with intentional errors and inconsistencies (cleaned during preprocessing)
- **Secondary Source**: I created a second excel file with costs of item so I could find gross profit and how much the fictional company spent

| Column             | Description                                 |
|--------------------|---------------------------------------------|
| Transaction ID     | Unique identifier per transaction           |
| Item               | Product name (e.g., Coffee, Sandwich)       |
| Quantity           | Number of items purchased                   |
| Price Per Unit     | Cost per item                               |
| Total Spent        | Quantity × Price                            |
| Payment Method     | Method used for payment (Cash, Credit, etc) |
| Location           | In-store or Takeaway                        |
| Transaction Date   | Date of sale                                |


| Column             | Description                                 |
|--------------------|---------------------------------------------|
| Cost               | Cost for Coffee & Cream                     |
| Item               | Product name (e.g., Coffee, Sandwich)       |

---

## Dashboard Features

The dashboard was built in **Power BI** and includes:

### Key Visualizations

| Visual                          | Purpose                                                    |
|----------------------------------|-------------------------------------------------------------|
|  **Transactions by Month**     | Understand sales volume trends across the year             |
| **Total Sales by Item**       | Identify best-selling products                             |
| **Payment Method Distribution** | Analyze customer payment preferences                       |
| **Cost, Sales & Profit Matrix**| Monthly financial breakdown: cost, sales, and profit       |
| **Profit Over Time (Line Chart)**| Track profit trends by month                               |
|  **Slicers (Filters)**         | Drill into data by **Item**, **Month**, and **Location**    |
---
<img width="680" height="214" alt="Image" src="https://github.com/user-attachments/assets/3cabf5b3-41ba-498d-bce6-9775860314a7" />

---
<img width="350" height="304" alt="Image" src="https://github.com/user-attachments/assets/1040c4d4-3216-4ae9-a607-81f815a66b4a" />

---
<img width="404" height="307" alt="Image" src="https://github.com/user-attachments/assets/98d0ec69-99a0-484d-b813-23b59d05e74b" />

---
<img width="320" height="299" alt="Image" src="https://github.com/user-attachments/assets/12420e75-b8b1-45e3-a6a1-9d0622961719" />

---
<img width="611" height="209" alt="Image" src="https://github.com/user-attachments/assets/69d89ebd-3f1b-432c-94a5-b63c0d6bed85" />

---
<img width="215" height="329" alt="Image" src="https://github.com/user-attachments/assets/592634b5-2b45-42bb-ba15-ab25179c2210" />

---


## Business Scenario

Coffee & Cream is reviewing its 2023 performance to make data-driven decisions on product strategy, pricing, operations, and customer preferences. As the data analyst, I was tasked with identifying patterns and presenting insights to various stakeholders.

---

##  Stakeholder Questions

- Which items brought in the most revenue?
  (Salads)
- Were there months with unusually high or low profits?
  (January - High, May - Low)
- How has profit trended throughout the year?
  (Profit Averaged Monthly Around $1400)
- Which month had the highest operational costs?
  (January)
- Are there seasonal trends in product sales?
  (Coffee had increased sales in cold months such as October-December)
- Which products are best to promote based on profitability?
  (Salads, Sandwiches, and Smoothies)
- When should we run loyalty campaigns or promotions?
  (Holiday Season - December through January)
- What were total sales, costs, and profit in 2023?
  (Total Cost = 9.85k, Total Sales = 27.61k, Gross Profit = 17.76k)


---

## Key Insights

- **Top Sellers**: Items like *Salads* and *Sandwiches* generated the most revenue, a rebranding to have more emphasis on those items is recommended.
- **Profit Fluctuation**: High profits observed in winter and fall, with a notable summer dip.
- **Balanced Payment Use**: No dominant payment method; customers used both cash and card consistently.
- **Takeouts**: Takeouts had a prominant number of sales, marketing towards take out deals may be beneficial.
- **Seasonality**: Clear spikes during holidays and early Q4 suggest timing for future promotions.

---

## Tools Used

- **Power BI** – data cleaning, dashboard creation, data modeling, visual analytics  
- **Microsoft Excel** – initial data cleaning and validation  
- **DAX** – calculated fields and measures  
- **Kaggle** – data source  

---


## Contact

**Created by:** [Landon Pillar]  
Email: [landonpillar4@gmail.com]  
Portfolio: [https://landonpillz.github.io/Portfolio/]  
LinkedIn: [https://www.linkedin.com/in/landon-pillar-95657829b/]

---
## Link to Kaggle 
https://www.kaggle.com/datasets/ahmedmohamed2003/cafe-sales-dirty-data-for-cleaning-training


