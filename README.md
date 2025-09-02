# Mevgal Greek Yogurt Sales Performance Analysis
#### Unlocking sales insights for a global dairy leader through data-driven analytics

![](https://github.com/SnehaEkka/BA780-Greek-Yogurt-Sales-Analysis/blob/main/Mevgal-banner.jpg)

## About Mevgal
MEVGAL is a Greek dairy product manufacturer. It manufactures and sells a wide variety of pasteurized dairy products, including milk, yogurt (both traditional Greek and European), cheeses, desserts, and rice puddings. MEVGAL now produces one in every five yogurts exported by Greece. The company owns a significant share in the Greek Yogurt category in markets ranging from Europe to America and Asia.

## Data Source

- **Primary Dataset:** [Zenodo Sales Data (2020–2022)](https://zenodo.org/record/7853252)
- **Data Description:** Sales records for 7 core yogurt products, including time, region, and product metadata.
- **Published by:** the University of Western Macedonia researchers on the ITHACA Lab platform https://ithaca.ece.uowm.gr/

## Purpose & Business Context

The Greek yogurt market is crowded and rapidly evolving. Companies like MEVGAL must routinely adapt to shifting consumer trends—but fragmented, manual sales tracking limited their ability to spot high-potential products or capitalize on seasonality. This project addresses those pain points with end-to-end analytics and rich visualization.

**Our objective:** Unlock actionable sales trends, elevate business intelligence, and empower strategic planning through robust data analysis. This project explores and analyzes three years (2020-2022) of dairy supply chain sales data for MEVGAL. 

## Solution Overview

Leveraging Python, Pandas, and Matplotlib/Seaborn, this project automates the discovery of sales trends, highlights star performers in the product lineup, and surfaces actionable recommendations for marketing and operations teams.

## Tech Stack & Tools

| Tool/Tech          | Role in Project                | Why Chosen            |
|--------------------|-------------------------------|-----------------------|
| Python             | Data processing, scripting     | Flexibility, speed    |
| Pandas             | Data wrangling & aggregation   | Industry standard     |
| Matplotlib/Seaborn | Visualization                  | Insightful, flexible  |
| Jupyter Notebook   | Interactive analysis           | Transparency, clarity |
| Excel              | Initial review/checks          | Familiar, agile       |

## Data Pipeline & Workflow

- Import and clean raw Zenodo sales data
- Aggregate across years, regions, and products
- Exploratory analysis: Uncover patterns, seasonality, and anomalies
- Visualization: Temporal trends, distribution insights, product comparisons
- Key findings and business-ready recommendations  

## Business Impact & Key Results

- **Identified Top Performing SKUs:**  
  - E.g., “Fruit Yogurt 150g” consistently outperformed other products, accounting for nearly 40% of all sales across the period.
- **Clarified Seasonality:**  
  - Clear summer sales peaks: MEVGAL sees up to 2.3x higher sales in June–August vs. winter low points.
- **Optimized Inventory & Promotions:**  
  - Recommendations to align promotions with high-sales months, reducing stock-outs and boosting market penetration.
- **Portfolio Insights:**  
  - Underperforming SKUs flagged—potential to cut costs or reallocate marketing resources.
- **Time Savings & Repeatability:**  
  - Project transforms a previously manual, ad hoc reporting process into a repeatable analytics workflow, enabling stakeholders to generate new insights with minimal effort.

## Key Code Highlights & How to Use

- **Notebook Logic:**  
  - Data cleaning: Smart handling of missing dates/values with clear EDA steps.
  - Aggregation & segmentation: Custom functions to break down sales by product and time.
  - Visual summaries: Plots and charts spotlighting both successes and pain points.
- **How to Run:**  
  1. Download data from [Zenodo](https://zenodo.org/record/7853252)
  2. Open `Mevgal_Sales_Analysis.ipynb` in Jupyter
  3. `pip install pandas matplotlib seaborn jupyter`, if needed
  4. Run notebook cells sequentially, updating file paths as necessary

## Future Improvements

- Layer on predictive sales forecasting using regression or machine learning
- Expand data sources: Integrate weather or economic trends for deeper context
- Automate dashboard/reporting for non-technical stakeholders

## Coursework & Contributors
- Built as part of the BA780 - Intro to Data Analytics, with a focus on real-world business analytics and transforming raw data into actionable strategies.
- Team Members: Dian Jin, Kunjingyi Chen, Min Xu, Mitchell Wu, Sneha Ekka, Tanvi Sheth

## Presentation Deck

Refer to the [MEVGAL Presentation Deck](https://www.canva.com/design/DAFxrObRam8/Zp9cwPbMrqd1GxI1oGxcuA/view) for additional business context, visual takeaways, and next-step recommendations.
