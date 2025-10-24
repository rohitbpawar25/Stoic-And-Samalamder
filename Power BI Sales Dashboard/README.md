# Task 1: Sales Performance Dashboard – Power BI

**Priority:** Medium  
**Task Category:** Dynamic Data & Visualisation  

---

## Objective
Students will create an interactive **Sales Performance Dashboard** using Power BI. The dashboard should include key metrics and visualizations that provide insights into sales trends, regional performance, and product categories.

---

## Scenario
You are a **Data Analyst** at a retail company. Your manager has asked you to create a dashboard to analyze sales performance over the last year. The company operates in multiple regions and sells products in various categories.

---

## Steps to Complete the Task

### 1. Data Import
- Download the dataset provided.  
- The dataset contains the following fields:
  - Order Date  
  - Region  
  - Product Category  
  - Product Name  
  - Sales  
  - Profit  
  - Quantity Sold  
  - Customer Name  
- Load this dataset into Power BI.

---

### 2. Data Transformation (Power Query)
Perform the following transformations in Power Query:
1. Format the **Order Date** column as a Date field.  
2. Create a new column for **Year** and **Month** from the Order Date column.  
3. Remove any duplicate rows.  
4. Filter out rows where **Sales** or **Profit** is zero or negative.  
5. Create a calculated column for **Profit Margin** using the formula:  

---

### 3. Visualizations

#### Page 1: Sales Overview
- **KPI Cards** for:
- Total Sales  
- Total Profit  
- Average Profit Margin  
- **Bar Chart:** Sales by Region  
- **Pie Chart:** Sales distribution by Product Category  
- **Line Chart:** Monthly sales trend for the last year  

#### Page 2: Regional Analysis
- **Stacked Column Chart:** Compare Sales and Profit by Region  
- **Map Visualization:** Show Total Sales by geographic Region  
- **Table:** Display Product Name, Sales, Profit, and Quantity Sold  

#### Page 3: Customer Insights
- **Donut Chart:** Top 5 Customers by Sales  
- **Clustered Bar Chart:** Sales by Product Category for each Region  

---

### 4. Interactivity
- Add **Slicers** for:
- Region  
- Year  
- Product Category  
- Enable **Cross-filtering** between visuals for better interactivity.

---

### 5. Formatting
- Add a **Title** and **Company Logo** to the dashboard.  
- Use professional **color schemes** and **data labels** for better readability.  
- Add **Tooltips** to visualizations to show additional details.

---

### 6. Insights & Conclusion
Add a text box in Power BI (150–200 words) highlighting insights and recommendations.

**Example:**

#### Key Insights
1. The **West Region** achieved the highest total sales, contributing over 35% of total revenue.  
2. **Electronics** is the top-performing product category with the highest profit margin.  
3. Sales show a steady increase from **Q2 to Q4**, indicating strong year-end performance.  

#### Recommendations
1. Increase inventory and marketing focus in high-performing regions and categories.  
2. Offer promotional discounts during low-sales months to maintain consistent revenue.

---

## Submission
- Save the Power BI file as `SalesDashboard.pbix`.  
- Export the dashboard as `SalesDashboard.pdf`.

---

## Evaluation Criteria
| Criteria | Weight |
|-----------|---------|
| Data Transformation Accuracy | 20% |
| Dashboard Design (Visuals, Formatting, Layout) | 30% |
| Interactivity and Filters | 20% |
| Insights and Recommendations | 20% |
| Timely Submission | 10% |
