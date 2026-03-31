# Data Analysis Dashboard Project

## Project Title
**Jumia Product Performance Dashboard: Analyzing Pricing, Discounts, and Customer Reviews**

---

## Project Objective
The objective of this project is to design and build an interactive Excel dashboard that analyzes the performance of products listed on Jumia. Students will explore how pricing, discounts, reviews, and ratings influence product performance and customer engagement. The final dashboard should support data-driven decision-making in an e-commerce context.

---

## Dataset Overview
The dataset contains product-level data with the following columns:

- **Product** – Name of the product  
- **Current Price** – Current selling price in Kenyan Shillings (KSh)  
- **Old Price** – Original price before discount in Kenyan Shillings (KSh)  
- **Discount** – Discount percentage applied to the product  
- **Reviews** – Number of customer reviews  
- **Rating** – Average customer rating out of 5  

---

## Data Cleaning and Preparation

- Check for and handle missing values, especially in the **Reviews** and **Rating** columns  
- Identify and remove duplicate product entries  
- Convert price columns into numeric format by removing “KSh”, commas, and text  
  - Use:
    - **Split Text to Columns (Data tab)**  
    - OR **Find and Replace (Ctrl + H)**  
- Ensure the **Discount** column is numeric and properly formatted as a percentage  
  - Methods:
    - Find and Replace (Ctrl + H)  
    - Extract using LEFT/RIGHT  
    - Text Split  
- Convert the **Rating** column from text format (e.g., “4.5 out of 5”) into numeric values  
- Convert negative reviews to positive  

---

## Data Enrichment

Create the following additional columns:

### 1. Discount Amount (KSh)
- Formula:  
  `Old Price - Current Price`

### 2. Rating Category
- **Poor** → ratings below 3  
- **Average** → ratings between 3 and 4.4  
- **Excellent** → ratings of 4.5 and above  

### 3. Discount Category
- **Low Discount** → below 20%  
- **Medium Discount** → between 20% and 40%  
- **High Discount** → above 40%  

---

## Data Analysis

### Descriptive Analysis

- What is the average:
  - Current price  
  - Old price  
  - Discount percentage  
  - Rating  
- Which product is:
  - Most expensive  
  - Least expensive  
- What is the average rating and discount by discount category?  
- How are products distributed across rating categories?  

---

### Trend and Relationship Analysis

Analyze and interpret:

- Relationship between **discount percentage and number of reviews**  
- Relationship between **rating and number of reviews**  
- Whether **higher discounts lead to increased customer engagement**  
- Whether **higher-rated products tend to have more reviews**  

---

### Product Performance Analysis

Identify:

- Top 10 products with the **highest discounts**  
- Top 10 products with the **most reviews**  
- Top 5 **highest-rated** and bottom 5 **lowest-rated** products  
- Comparison between **high-discount and low-discount products** based on:
  - Average rating  
  - Number of reviews  

---

## Dashboard Design

### Dashboard Requirements

Create a single interactive Excel dashboard containing:

#### Overview
- Total number of products  
- Average rating  
- Average discount percentage  
- Total number of reviews  

#### Product Performance
- Top products by rating  
- Top products by number of reviews  
- Top products by discount percentage  

#### Trend Analysis
- Visualizations showing:
  - Discount percentage vs reviews  
  - Rating vs reviews  

#### Product Categories
- Breakdown of products by **rating category**  
- Breakdown of products by **discount category**  

---

## Visualization Guidelines

- Use **Pivot Tables** as the primary data source  
- Use appropriate charts:
  - Bar charts  
  - Column charts  
  - Pie/Donut charts  
  - Scatter plots  
- Apply **conditional formatting**:
  - Highlight high discounts  
  - Highlight low ratings  
- Include **slicers** for:
  - Rating category  
  - Discount category  
  - Price range  

---

## Presentation

### Group Presentation

Each group will:

- Present their dashboard to the class  
- Explain key insights derived from the analysis  
- Demonstrate dashboard interactivity using filters and slicers


### Discussion Points

- Which products are performing best and why  
- Whether discounts are effective in driving engagement  
- Identify products with **high discounts but low ratings**  
- Provide recommendations to improve product performance

 --  
 
- ##**Solution**
- **Question 1**[Discount amount]
-<img width="1920" height="1080" alt="Screenshot 2026-03-30 161319" src="https://github.com/user-attachments/assets/57c9232a-6ec3-45dd-9b5a-cde31fb9f70d" />

-**Question 2**[Ratings category]
  <img width="1920" height="1080" alt="Screenshot 2026-03-31 154115" src="https://github.com/user-attachments/assets/ba3712dd-5801-46cb-b9a5-27d7e5751427" />

-**Question 3**[Discount category] 
<img width="1920" height="1080" alt="Screenshot 2026-03-31 154905" src="https://github.com/user-attachments/assets/4315c766-f529-4266-9c9a-bf5295a22abc" />

--

## Data Analysis

### Descriptive Analysis Solutions 

- **What is the average:**
-[Current price]
<img width="1920" height="1080" alt="Screenshot 2026-03-31 162019" src="https://github.com/user-attachments/assets/bc515cc1-b591-4fd7-a08e-3c90c421dafc" />
-[Old price]
<img width="1920" height="1080" alt="Screenshot 2026-03-31 162301" src="https://github.com/user-attachments/assets/2cf251ea-8d85-427d-85bd-bc1ee7da8f0e" />
-[Discount percentage]
<img width="1920" height="708" alt="Screenshot 2026-03-31 162601" src="https://github.com/user-attachments/assets/d3944f70-90e7-4152-980d-75e4198bba97" />
-[Ratings]
<img width="1920" height="886" alt="Screenshot 2026-03-31 162809" src="https://github.com/user-attachments/assets/0c0619a0-173c-4d8c-b1e3-e9e0ad478e56" />




