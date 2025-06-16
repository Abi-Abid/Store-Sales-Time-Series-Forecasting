![Retail Grocery Store](https://images.unsplash.com/photo-1607083206173-3e9c5c5af8d2?auto=format&fit=crop&w=1470&q=80)
*Source: [Unsplash](https://unsplash.com/photos/goods-on-shelf-rWMIbqmOxrY)*

# Store Sales - Time Series Forecasting
### Which product family, and from which store, is projected to generate the highest sales over the next 30 days? Well, let’s predict!!! 

**This is a time series forecasting project focused on predicting the unit sales of products for Corporación Favorita, a large Ecuadorian-based grocery retailer.**

This repository provides a comprehensive understanding of the problem, a step-by-step explanation of the approach taken, and a detailed storytelling walkthrough — from data exploration to final modeling. It reflects not only the technical solution but also my personal learning journey and explanation style in solving the grocery store sales prediction challenge.

- **June 16, 2025**: Today Exploratory Data Analysis (EDA) have been analyzed, insights from this are drafted below, for full story telling for this EDA, please refer to `Store_Sales_EDA_Story_Telling.pdf`, uploaded in this repository

### Insights from EDA
1. **Company Overview:** Corporación Favorita is a major grocery retailer operating in Ecuador. It runs 54 stores spread across 22 cities in 16 states. These stores are categorized into five types (A, B, C, D, and E) and grouped into 17 clusters of similar store formats.
2. **Product Assortment Consistency:** Across all 54 stores, the company has maintained a consistent product assortment of 33 family types since January 1, 2013, to August 8, 2017 — a period of 4.5 years. This shows the company’s consistency in offerings, but it also reveals a lack of inventory refresh or adaptation to changing consumer preferences.
3. **Sales Concentration by Product Family:** Over this 4.5-year period, 13 out of the 33 product family types recorded zero sales, indicating a clear disconnect between inventory and customer demand. This suggests an opportunity for the company to phase out non-performing product lines and instead focus on high-performing categories such as ‘Grocery I’, ‘Beverages’, ‘Produce’, and ‘Cleaning’. This would lead to cost savings in inventory management and better alignment with customer needs.
4. **Sales Seasonality & Holiday Impact:** A consistent sales pattern is observed year after year, where sales peak in December (likely due to Christmas and holiday shopping) and decline in January. Additionally, sales tend to be higher during the mid-year (summer months) as well. This correlates strongly with the holiday and event calendar, suggesting that holidays significantly boost customer purchases. The company should capitalize on these periods by increasing stock, offering promotions, and improving customer service to maximize revenue and customer satisfaction.
5. **Macroeconomic Influence – Oil Dependency:** As Ecuador is an oil-dependent economy, national economic health is closely tied to global oil prices. It was found that sales performance is inversely proportional to oil prices: high oil prices coincided with reduced sales, while lower oil prices saw an increase in sales. This trend must be monitored continuously, as future increases in oil prices could negatively impact sales, prompting the need for contingency planning and strategic pricing.
6. **Store-Level Performance Patterns:** Among all stores, those located in **Quito city**, particularly of **type A**, exhibited consistently strong sales performance. On the contrary, two stores — located in different cities and store types — were identified as severe under performers. These do not follow any observed trend and might be suffering due to internal operational issues. These outlier stores warrant deeper investigation and potential corrective actions.
7. **Strategic Focus Recommendations:** Moving forward, the company should prioritize stores with high sales volumes, especially type A stores in Quito, as they likely reflect stronger customer loyalty and demand. Forecasting unit sales accurately in these stores is critical. At the same time, performance improvement strategies should be gradually rolled out to underperforming stores, while reevaluating or even closing those with persistently poor sales.





### Author

**Dudekula Abid Hussain**

Email - dudekula.abid.hussain@outlook.com
