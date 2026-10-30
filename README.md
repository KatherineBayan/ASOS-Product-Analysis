# ASOS-Product-Analysis

<img width="1182" height="784" alt="image" src="https://github.com/user-attachments/assets/44e2432e-e1b0-471b-9f59-a06f82b364db" />

### Description

Conducted a product availability and inventory analysis using ASOS product listing data to identify size-level stockouts, evaluate brand performance, and determine which products require inventory attention. The project involved data cleaning, product-level consolidation, stockout analysis, brand comparisons, and product prioritization. The findings were used to develop data-driven recommendations for inventory monitoring and stock management.

### Goals

- Measure the extent of size-level stockouts across ASOS product listings.
- Identify sizes and products experiencing the greatest availability pressure.
- Compare brands based on average product prices and stockout rates.
- Prioritize products for inventory investigation using stockout rates and estimated exposure.
- Develop recommendations to improve inventory monitoring and product availability.

### Skills Used

- **Python:** Data manipulation and analysis using Pandas.
- **Data Cleaning:** Handling missing values, filtering records, and consolidating product listings.
- **Exploratory Data Analysis (EDA):** Identifying patterns and trends in product availability.
- **Data Visualization:** Creating charts and comparisons to communicate stockout patterns and brand performance.
- **Business Analytics:** Interpreting inventory-related metrics and translating findings into business recommendations.
- **Analytical Reporting:** Presenting results and actionable insights based on the data.

### Results

- Analyzed **9,708 initial records**, retaining **8,438 records** after data cleaning.
- Found that **23.98% of recorded size options were sold out**, while **50.41% of products had at least one sold-out size**.
- Identified **2XL - UK 16** as the size with the highest observed stockout rate at **43.86%**.
- Consolidated the data into **525 unique products** and classified them into inventory priority groups:
    - 109 high-priority products (20.76%)
    - 50 medium-priority products (9.52%)
    - 366 routine-monitoring products (69.71%)
- Identified brands with relatively high average prices and elevated stockout rates, highlighting potential areas for inventory review.
- Estimated a total stockout exposure proxy of **727,029.22**, calculated using listed product prices and the number of sold-out sizes. This represents potential exposure, not confirmed lost revenue.

### Recommendations

- Prioritize inventory investigation for the 109 products classified as high priority, particularly those with high stockout rates and greater estimated exposure.
- Review stock allocation for sizes with elevated stockout rates, especially 2XL - UK 16, XL - UK 14, and UK 14.
- Improve brand-level analysis by standardizing brand names and correcting product-title fragments mistakenly included in extracted brand labels.
- Monitor products with recurring stockouts and regularly update inventory priority classifications.
- Compare stockout indicators with actual sales, demand, and on-hand inventory data to better estimate potential revenue impact.
- Establish a recurring inventory monitoring process to help identify availability issues and support more informed replenishment decisions.
