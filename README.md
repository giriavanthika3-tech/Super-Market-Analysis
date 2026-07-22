### **Supermarket Order Analysis: Regional Profitability, Sales Drivers, and Market Segmentation**

---

### **1. Project Overview**
**Project Title:** Supermarket Global Order Profitability & Sales Dashboard
**Description:** This Tableau dashboard delivers a deep analytical view of a global supermarket's order performance. Moving beyond simple revenue tracking, it focuses heavily on the intersection of profitability, sales volume, and shipping costs across various global markets (Africa, Central Asia, North America, etc.). It uses advanced visualizations like scatter plots, bubble charts, and correlation matrices to dissect which product categories and geographical regions drive the company's bottom line.

---

### **2. Objective**
The core objective of this project is to provide stakeholders with an actionable understanding of the supermarket's financial ecosystem. Specific goals include:
*   **Profitability Mapping:** To identify which global regions are highly profitable versus those that are operating at a loss.
*   **Category Performance Intersection:** To evaluate how different product categories (Technology, Office Supplies, Furniture) perform across global markets.
*   **Sales vs. Profit Dynamics:** To analyze the relationship between gross sales revenue and net profit margin to spot inefficiencies.
*   **Sub-Category Trend Analysis:** To track the performance of specific product niches over time (by quarter) to spot seasonal trends or declines.
*   **Operational Costs:** To monitor the impact of shipping costs on overall profitability.

---

### **3. Dashboard Features**
*   **Executive Summary KPIs (Top Right):** Three distinct KPI cards showing *Sum of Shipping Cost (1M)*, *Count of Market (51K)*, and *Count of Product (51,290)*.
*   **Category Profit & Sales Bars (Top Left):** A horizontal "lollipop" style bar chart illustrating *Sum of Profit & Sales by Category*. It clearly ranks Technology highest, followed by Office Supplies and Furniture.
*   **Heatmap Matrix (Top Center):** A highly detailed table displaying *Sum of Profit by Category & Region*. The cells are color-coded (darker purple = higher profit), allowing for quick identification of profitable and unprofitable intersections. Notably, *Southeast Asia* shows negative numbers in Furniture and Office Supplies.
*   **Market Bubble Chart (Top Right):** A *Packed Bubble Chart* representing market scale. The size of the bubble likely correlates to the volume of orders or market count, with the "Central" region having the largest footprint.
*   **Time-Based Sub-Category Grid (Bottom Left):** A dot-matrix visualization showing the *Average of Profit & sales by Sub-Category* over time (Quarter of Order Date). It allows tracking of individual products (e.g., Copiers, Chairs, Tables) across 2011-2014.
*   **Sales vs. Profit Scatter Plot (Bottom Center):** A scatter chart plotting *Sum of Sales & Profit by Region*. This is a very powerful visual to identify outliers (e.g., 'Central' has high sales and very high profit, while 'EMEA' has low sales and low profit).
*   **Product Ranking Chart (Bottom Right):** A mirrored bar chart (BC - Butterfly Chart) showing the performance of specific sub-categories. (Note: The data appears to show identical values on both left and right sides for this specific dataset, but it is formatted as a comparison tool).

---

### **4. Business Questions**
This dashboard is designed to answer these strategic questions:
1.  Which product category generates the highest absolute profit, and which generates the lowest?
2.  In which specific regional markets is the company losing money on core products?
3.  Is there a direct correlation between high sales volume and high profit, or are some high-sales regions actually low-margin?
4.  Are there specific sub-categories that consistently underperform across all quarters, signaling a need to discontinue them?
5.  How do shipping costs compare to the overall scale of operations?

---

### **5. Key Insights (Data-Driven)**
*   **Technology is the Ultimate Profit Engine:** The lollipop chart shows Technology generating **664K** in profit, far surpassing Office Supplies (518K) and Furniture (285K).
*   **The Central Region Dominates:** The packed bubble chart identifies "Central" as the largest market. The scatter plot confirms this dominance, showing Central with both the highest sales (near 3M) and the highest profit (over 300K), placing it far above all other clusters.
*   **Southeast Asia is a Critical Concern:** The heatmap clearly flags **Southeast Asia** with a **negative profit of -7,270** in the Furniture category, and -4,173 in Office Supplies. They are losing money in this region on two out of three categories.
*   **The 80/20 Rule in Action:** The scatter plot reveals a massive gap between the top-tier region (Central) and the rest. Many regions (like EMEA, Caribbean, Africa, and Oceania) are clustered in the bottom-left quadrant, struggling with low sales and profits below 100K.
*   **Sub-Category Pricing Stability:** The dot-matrix chart shows remarkable consistency in average pricing and profit for top items like Phones, Copiers, and Chairs across the 2011-2014 timeframe, indicating a stable pricing strategy for core goods.

---

### **6. Tools & Technologies**
*   **Primary Tool:** Tableau Desktop (evident from the purple color theme, the specific visualization styles, and the worksheet tabs visible at the bottom).
*   **Data Source:** Supermarket Order Dataset (likely an extended version of the standard Tableau Superstore dataset).
*   **Advanced Visualizations:** Packed Bubble Chart, Scatter Plot, Heatmap/Highlight Table, Lollipop Chart, Dot Matrix Chart, and Butterfly Chart (Split/Diverging Bar Chart).
*   **Calculated Fields (Implied):** DAX/Tableau calculations used to derive "Average of Profit & Sales" and to arrange the data fields correctly for the matrix and scatter plots.

---

### **7. Skills Demonstrated**
*   **Advanced Analytical Charting:** Proficiency in using scatter plots to explore relationships between two independent measures (Sales vs. Profit), and using heatmaps to display dense 2-dimensional data.
*   **Complex Data Relationships:** Ability to manage and visualize three-dimensional data (Product Category x Region x Profit) effectively.
*   **Visual Storytelling:** Using a scatter plot to instantly reveal a massive performance gap between the leader ("Central") and the rest of the pack.
*   **Trend & Outlier Identification:** Using grid-based dot charts to track longitudinal performance and spot anomalies like the negative profit in Southeast Asia.
*   **Alternative Chart Styles:** Implementation of the "BC" Butterfly chart and Packed Bubbles, showing a wide toolkit of visualization options beyond standard bar and line charts.

---

### **8. Business Value**
*   **Crisis Management in Southeast Asia:** The heatmap provides an immediate call to action. The leadership team can investigate the Southeast Asian logistics chain, local pricing, or supplier costs to stop the bleeding of over -7K in furniture and -4K in office supplies.
*   **Growth Strategy for Mid-Tier Markets:** The scatter plot shows that many regions (North, South, West) are trapped in the middle. The company can analyze what "Central" is doing differently (better supply chain, bulk discounts, local marketing) and try to replicate that playbook in "North" and "South" to push them toward the 300K profit mark.
*   **Focus on Core Competencies:** Since Technology is by far the highest profit generator, the dashboard validates the strategy of doubling down on tech products globally. If budget cuts are needed, the company knows to protect the Technology supply chain at all costs.
*   **Shipping Cost Awareness:** Seeing a total of 1M in shipping costs relative to the KPI metrics allows logistics managers to negotiate better rates with carriers. If shipping costs are eating into the profits of lower-margin regions like Africa or EMEA, management may explore localized warehousing to reduce freight charges.
