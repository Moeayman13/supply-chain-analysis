

# Supply Chain Performance Analysis

This project analyzes supplier performance, manufacturing insights, inventory management, customer demographics, and shipping operations using real-world data. The goal is to identify performance bottlenecks, optimize supply chain operations, and provide data-driven recommendations.
> Graduation project for DEPI - Power BI Engineer Track.   This repository contains datasets, Power BI reports, and analysis related to our project Supply Chain analysis.

---

## Table of Contents

- [Project Overview](#project-overview)  
- [Key Insights](#key-insights)  
- [Data Summary](#data-summary)  
- [Technologies Used](#technologies-used)  
- [Getting Started](#getting-started)  
- [Contributing](#contributing)  
- [License](#license)

---

## Project Overview

This analysis evaluates the efficiency of five suppliers and their impact on manufacturing and logistics. It highlights performance variability, manufacturing lead times, product defect rates, and customer behavior segmented by gender. The project aims to improve supply chain decisions and identify high-impact areas.

---

## Key Insights

- **Supplier 4** has the lowest reliability and the highest variability.
- **Skincare products** generate the highest revenue but face significant inspection failure rates.
- **Bangalore** has the fastest average shipping times.
- **Road transport** is the most used but also the most expensive.
- Customers who **prefer not to disclose gender** generate the highest revenue.

---

## Data Summary

### Supplier Metrics

| Supplier | Revenue (k) | Products Sold | Avg MFG LT | Reliability Score | Performance Variability |
|----------|-------------|----------------|-------------|--------------------|--------------------------|
| Supplier 1 | 157.5 | 11k | 12.59 | 48.1% | 8.39 |
| Supplier 2 | 125.5 | 11k | 15.59 | 22.7% | 9.59 |
| Supplier 3 | 97.8 | 8k | 14.93 | 13.3% | 8.00 |
| Supplier 4 | 86.5 | 7k | 15.33 | 0% | 7.7 |
| Supplier 5 | 110.3 | 9k | 16.33 | 16.7% | 8.78 |

### Product Manufacturing

| Category  | Avg MFG Cost | Avg LT | Avg Defect Rate | Inspection Failure Rate |
|-----------|--------------|--------|------------------|-------------------------|
| Skincare  | 0.08         | 13.78  | 2.33             | 32.5% (197.5% by suppliers) |
| Haircare  | 0.08         | 17.07  | 2.48             | 38.24% (150% by suppliers) |
| Cosmetics | 0.09         | 13.31  | 1.92             | 38.46% (165% by suppliers) |

### Inventory Summary

- Total Stock: 5,000 units

| Product Type | Avg Stock Level | Stock Turnover | Order Quantity |
|--------------|------------------|----------------|----------------|
| Cosmetics    | 58.65            | 200.45         | 1,343          |
| Haircare     | 48.35            | 281.49         | 1,480          |
| Skincare     | 40.20            | 515.70         | 2,099          |

### Customer Demographics

| Gender           | Revenue (k) | Products Sold | Most Purchased Product |
|------------------|-------------|----------------|-------------------------|
| Female           | 161.51      | 12,801         | Skincare                |
| Male             | 126.63      | 7,507          | Skincare                |
| Non-binary       | 116.37      | 10,580         | Skincare                |
| Prefer not to say| 173.09      | 15,211         | Haircare                |

### Shipping & Transportation

- **Total Transportation Costs:** 52.92k  
- **Total Shipping Costs:** 554.82k  
- **Avg Shipping Time:** 5.75 days  
- **Most Used Mode:** Road

| Mode | Cost (k) |
|------|----------|
| Air  | 14.6     |
| Road | 16.05    |
| Rail | 15.17    |
| Sea  | 7.1      |

| City      | Avg Time | Avg Cost |
|-----------|----------|----------|
| Delhi     | 5.93     | 5.07     |
| Kolkata   | 5.96     | 5.76     |
| Mumbai    | 5.55     | 6.25     |
| Bangalore | 5.28     | 5.75     |
| Chennai   | 6.00     | 4.69     |

---

## Technologies Used

- Microsoft Excel  
- Power BI  
- Microsoft Word  
- Git / GitHub  

---

## Getting Started

Clone the repository and open the `.docx` file for detailed analysis:

```bash
git clone https://github.com/Moeayman13/supply-chain-analysis.git
Getting Started
Clone the repository and open the .docx file for full analysis:
git clone https://github.com/Moeayman13/supply-chain-analysis.git

Contributing
Feel free to fork this project, open issues, and submit pull requests if you have improvements or new insights to add.
License
This project is open-source and available under the MIT 
