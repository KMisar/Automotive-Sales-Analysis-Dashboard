

# 🚗 Automotive Sales Dashboard

This Power BI project presents an interactive dashboard that offers comprehensive insights into automotive sales data. It enables data-driven decision-making by analyzing sales trends, profit margins, dealership performance, top-performing brands and models, and high-value sales across multiple dimensions.

---

## 📊 Project Overview

The **Automotive Sales Dashboard** was built using Power BI to help understand the key performance metrics of vehicle sales across brands, dealerships, and time periods. It provides dynamic visualizations to explore:

* Total Sales, Profit, and Cost
* Yearly and Weekly Sales Trends
* Top Brands and Models by Sales and Profit
* Dealership-wise Performance
* Profit Margins and High-Value Transactions

---

## 🧾 Dataset Description

The dataset includes detailed transactional data such as:

| Column Name     | Description                                  |
| --------------- | -------------------------------------------- |
| `Brand`         | Vehicle manufacturer (e.g., Honda, Nissan)   |
| `Model`         | Vehicle model (e.g., Civic, Rogue)           |
| `Year`          | Year of manufacture                          |
| `Price`         | Selling price of the vehicle                 |
| `Mileage`       | Vehicle mileage (km)                         |
| `Transmission`  | Transmission type (Automatic, Manual, etc.)  |
| `Fuel_Type`     | Fuel used (Petrol, Diesel, Electric, Hybrid) |
| `Date_Sold`     | Date the car was sold                        |
| `Dealership_ID` | Unique dealership identifier                 |
| `Cost`          | Cost incurred by the dealership              |
| `Profit`        | Profit from the transaction                  |
| `Customer_*`    | Customer details (Name, Email, Phone)        |

> 🧹 **Note:** The data was already clean and well-structured. No extensive preprocessing or data modeling was required.

---

## 📈 Key Measures Created

| Measure Name              | Description                                             |
| ------------------------- | ------------------------------------------------------- |
| `Total Sales`             | Sum of all vehicle prices sold                          |
| `Total Cost`              | Total cost incurred on all sold vehicles                |
| `Total Profit`            | Profit = Total Sales - Total Cost                       |
| `Profit Margin`           | Profit divided by Sales                                 |
| `Average Profit per Unit` | Average profit per vehicle                              |
| `Average Selling Price`   | Average of all vehicle prices                           |
| `Top 5 Models by Sales`   | Highest-selling models                                  |
| `Top 5 Brands by Sales`   | Brands with highest total sales                         |
| `Monthly Units Sold`      | Units sold per month (used for trend analysis)          |
| `High Value Sales`        | Sales with high prices and profits across brands/models |

---

## 📊 Dashboard Features

* **Dynamic Filters**: Quarter, Brand, Dealership Name
* **KPIs**: Sales, Profit, Cost, Profit Margin, etc.
* **Line Charts**: Yearly and weekly trends
* **Bar Charts**: Top models, brands, dealerships
* **Donut Chart**: Profit distribution by brand
* **Scatter Plot**: High-value sales by brand and model
* **Dual-Axis Visuals**: Profit margin vs sales by dealership

---

## 📷 Dashboard Preview

![Automotive Sales Dashboard](./AutomotiveSales%20Dashboard.png)

---

## 📌 Key Insights

* Volkswagen, Mercedes, and Toyota are the top-selling brands.
* The **Tiguan** model leads in total units sold.
* Most profits come from electric and hybrid fuel types.
* Dealership D0039 stands out in terms of high profit margins.
* Sales are consistent across the week with a slight dip mid-week.

---

## 💡 Conclusion

This project demonstrates how Power BI can turn raw automotive data into actionable insights through intuitive visualizations and DAX measures. It is especially useful for sales managers, dealership analysts, and automotive business planners.

---

## 🛠 Tools Used

* **Power BI**
* **DAX (Data Analysis Expressions)**
* **Microsoft Excel** (for data review)

---

## 📁 File Structure

```
Automotive-Sales-Dashboard/
│
├── AutomotiveSales Dashboard.pbix   # Power BI file
├── AutomotiveSales Dashboard.png    # Dashboard image preview
├── README.md                        # Project documentation
└── sample_data.csv                  # Sample dataset
```

---

