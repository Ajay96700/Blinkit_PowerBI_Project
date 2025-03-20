## Overview

Blinkit is India's leading quick-commerce platform, specializing in last-minute grocery and essentials delivery. The company caters to customers across different tier cities, offering a variety of grocery items, household goods, and beverages. The data provides insights into sales performance, customer preferences, and outlet efficiency across different outlet types, locations, and item categories.

## Objective
The primary objective of analyzing Blinkit's grocery data is to:
1.	Understand Sales Performance – Evaluate total and average sales across different outlet types and locations.
2.	Identify Consumer Preferences – Analyze item categories that contribute the most to revenue.
3.	Assess Outlet Performance – Compare sales across small, medium, and large-sized outlets.
4.	Optimize Inventory & Pricing – Improve stock management and pricing strategies based on sales patterns.
5.	Enhance Customer Experience – Leverage customer ratings and item visibility to improve service quality.

## Dax Formulas

### Total Sales
```Dax
Total sales = CALCULATE(SUM('BlinkIT Grocery Data'[Sales]))
```
### Average sales
```Dax
Average sales = CALCULATE(AVERAGE('BlinkIT Grocery Data'[Sales]))
```
### Average Rating
```Dax
Rating = CALCULATE(AVERAGE('BlinkIT Grocery Data'[Rating]))
```
### Number of Item
```Dax
No. of Item = CALCULATE(COUNT('BlinkIT Grocery Data'[Item Identifier]))
```

