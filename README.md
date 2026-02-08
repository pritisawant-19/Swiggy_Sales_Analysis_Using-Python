
---

# Swiggy Sales Analysis 

## Project Overview

This project focuses on analyzing Swiggy food order data to gain insights into sales patterns, restaurant performance, pricing, and customer ratings. The analysis is performed using Python in a Jupyter Notebook, with data sourced from an Excel file.

---

## Files in This Repository

### 1. `Swiggy Sales Analysis.ipynb`

**Description:**
A Jupyter Notebook containing exploratory data analysis (EDA) and insights derived from Swiggy order data.

**Key Features:**

* Data loading and preprocessing
* Handling missing and inconsistent values
* Exploratory Data Analysis (EDA)
* Analysis of:

  * Orders by city and state
  * Restaurant and dish performance
  * Price distribution
  * Ratings and rating counts
* Visualizations using Python libraries

**Technologies Used:**

* Python
* Pandas
* NumPy
* Matplotlib / Seaborn
* Jupyter Notebook

---

### 2. `swiggy_data (1).xlsx`

**Description:**
The raw dataset containing Swiggy order details used for analysis.

**Columns Explanation:**

* **State** – State where the order was placed
* **City** – City of the restaurant
* **Order Date** – Date of the order
* **Restaurant Name** – Name of the restaurant
* **Location** – Area/locality of the restaurant
* **Category** – Food category (e.g., Recommended, Snack)
* **Dish Name** – Name of the ordered dish
* **Price (INR)** – Price of the dish in Indian Rupees
* **Rating** – Customer rating of the dish/restaurant
* **Rating Count** – Number of users who rated

---

## How to Run the Project

1. Install required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
2. Open Jupyter Notebook:

   ```bash
   jupyter notebook
   ```
3. Open `Swiggy Sales Analysis.ipynb`
4. Ensure `swiggy_data (1).xlsx` is in the same directory
5. Run all cells to view the analysis and visualizations

---

## Insights You Can Gain

* Top-performing restaurants and dishes
* Pricing trends across categories
* Relationship between price and ratings
* City-wise and location-wise sales patterns

---

## Use Cases

* Food delivery business analysis
* Pricing and menu optimization
* Customer preference analysis
* Data analytics portfolio project

---



