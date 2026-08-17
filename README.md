# UK Used Car Market Analytics & Dashboard

This repository contains a comprehensive data analysis project focused on the UK used car market. The project involves exploratory data analysis (EDA), data cleaning, and the creation of an interactive Power BI dashboard to derive actionable insights regarding car pricing, performance, and trends.

## Project Overview
The objective of this project is to analyze the relationship between various vehicle features (such as Make, Model, Year, Mileage, and Engine Size) and their market price. 

## Key Technologies
* **Python (Pandas, NumPy)**: Used for data cleaning, preprocessing, and exploratory data analysis (EDA).
* **Excel**: Utilized for pivoting and preliminary statistical summarization of the dataset.
* **Power BI**: Built an interactive dashboard to visualize sales performance and pricing patterns.
* **DAX (Data Analysis Expressions)**: Developed custom measures to calculate average prices and performance metrics across different car makes (Audi, BMW, VW, etc.)

## Repository Contents
* **`car_price.csv`**: The raw dataset containing detailed records of used car sales in the UK (including model, year, price, mileage, and technical specs).
* **`EDA.xlsx`**: Excel file containing pivot tables summarizing the average price per car make and other exploratory statistical findings.
* **`Car Price Dashboard.pbix`**: The final Power BI report, featuring interactive visualizations and filtering capabilities.

## Key Insights
* **Market Trends**: Analyzed how factors like `mileage` and `engineSize` impact the final `price`.
* **Brand Comparison**: Pivoted data to compare average market prices across major manufacturers such as Audi, BMW, and VW.
* **Interactive Dashboarding**: Created a dynamic reporting interface in Power BI that allows users to explore price variations based on `fuelType`, `transmission`, and `year`.

## How to View
1. **To explore the data**: Open the `car_price.csv` or `EDA.xlsx` files in Excel or any data analysis tool.
2. **To view the dashboard**: Download the `Car Price Dashboard.pbix` file and open it using **Power BI Desktop**.

---
*Created as part of a Data Analysis & Machine Learning portfolio.*
