# Myntra-Fashion-Clothing-Analysis-Sales-Discounts-and-Customer-Behavior
This Excel mini project analyzes the Myntra Fashion Clothing Database, covering purchase patterns by gender, pricing and discounts, brand performance, product sizes, and customer ratings. Using PivotTables, charts, and statistics, it transforms raw retail data into clear business insights.
# Introduction:
This report presents a comprehensive analysis of fashion retail data, highlighting purchase behavior, pricing trends, and brand performance.It explores customer preferences across gender, category, size ranges, and evaluates sales value, discounts, and ratings.Together, these insights provide a clear overview of consumer trends and business performance for strategic decision making.
# Objective:
•	The objective of this project is to analyze fashion retail data using PivotTables to generate actionable business insights.
•	It focuses on evaluating sales performance across categories and brands, understanding customer behavior by gender and loyalty, and assessing discount strategies to measure their impact on pricing and profitability.
•	By identifying key accounts, tracking growth trends, and highlighting customer preferences, the analysis supports informed decision-making to optimize sales channels, strengthen customer engagement, and drive sustainable business growth.
# Data description:
•	This dataset contains product-level details from a fashion retail store.
•	Each row represents one product, showing its ID, brand, category, gender target, price, discount, final price, size options, and customer feedback (ratings and reviews).
•	It helps analyze sales performance, discount impact, and customer preferences across different brands, categories, and sizes
# Data Cleaning in Power Query
•	Removed duplicates to ensure each product ID is unique.
•	Handled missing values by replacing nulls with defaults or removing incomplete rows.
•	Standardized text fields (brand names, categories, discount labels) using Transform → Format tools.
•	Split & merged columns where needed (e.g., separating discount % from text, merging category fields).
•	Ensured numeric consistency by converting prices, ratings, and reviews into proper number formats.
•	Verified calculations so that Final Price = Original Price – Discount Price.
# Data Cleaning in Excel
•	Used filters & conditional formatting to spot duplicates and errors.
•	Applied formulas (e.g., TRIM, PROPER, VALUE) to clean text and numeric fields.
•	Checked relationships between discount %, discount price, and final price for accuracy.
•	Standardized size options by aligning formats (e.g., “S, M, L” vs “Small, Medium, Large”).
•	Validated data ranges to ensure ratings (1–5) and reviews are logical.
•	Created a clean master table ready for PivotTable analysis.
# Final Price statistics:
•	Average (Mean): ₹1572.54
•	Median: ₹1439 (slightly lower than mean, showing right-skewed distribution)
•	Mode: ₹1424 (most frequent price point)
•	Variation: Standard Deviation ₹876.92, showing wide spread in prices
•	Range: ₹9 to ₹9499 (very large spread, with extreme values)
•	Skewness: 1.96 → positively skewed (lower-priced items, few very high-priced outliers)
•	Kurtosis: 7.88 → heavy-tailed distribution, meaning extreme values are more common than in a normal curve
•	Total Sales Value (Sum): ₹7,861,123 across 4999 purchases
# Discount Price statistics:
•	Average (Mean): ₹105.69
•	Median & Mode: ₹80 (most common and middle value)
•	Variation: Standard Deviation ₹166.53 → discounts vary widely
•	Range: ₹3 to ₹4225 → extreme spread, with very high outliers
•	Skewness: 13.18 → highly positively skewed (most discounts are small, few very large ones)
•	Kurtosis: 243.73 → extremely heavy-tailed distribution, meaning rare but extreme discount values occur often enough to distort the curve
•	Total Discount Value (Sum): ₹528,360 across 4999 purchases
# Pivot table:
1.	Purchase Count by Gender and Category
•	Out of 4,999 total purchases, women account for 3,062 (61%) and men for 1,937 (39%).
•	Men: Most purchases are in Topwear (882) and Bottom Wear (612).
•	Women: Strong preference for Western Wear (1,713), followed by Indian Wear (659) and Plus Size (315).
•	Shared categories: Sports Wear shows participation from both genders (192 total).
2.	Gender-Based Purchase Price Analysis:
•	Out of the dataset, women’s purchases show a higher average final price (₹1639.24) compared to men’s (₹1467.09). Similarly, the average discount price is higher for women (₹114.91) than for men (₹91.12).
•	Overall: The grand average final price is ₹1572.54, with an average discount of ₹105.69. This indicates that women’s purchases tend to be slightly more expensive and attract higher discounts compared to men’s.
3.	Top 10 Brand-Wise Product Count:
•	ROADSTER clearly dominates, while the rest of the brands contribute smaller portions.
4.	Average Ratings by Brand:
•	The overall average rating is 4.53 across all brands.
•	Most brands cluster around 4.5, showing consistent customer satisfaction.
•	A few brands stand slightly higher at 4.6 (VEIRDO, River of Design Jeans, Espresso, Cultsport).
•	Amydus has a mid point rating of 4.55, just above the overall average.
5.	Brand-Wise Sales Value:
•	Total sales value: ₹4,072,557 across all brands.
•	Top contributor: ROADSTER with ₹1,382,889 (the largest share).
•	Strong performers: MAST & HARBOUR (₹382,795), HERE&NOW (₹372,896), Sangria (₹310,908), HRX by Hrithik Roshan (₹328,064).
•	Mid-range brands: Highlander (₹264,710), Tokyo Talkies (₹241,857), Anouk (₹212,847), WROGN (₹386,585).
•	Smaller contributor: Vishudh (₹189,006).
6.	Top 10 Product Count by Size Range:
•	Total products: 3,710
•	Most common sizes: XS–XL (737), S–XXL (734), and S–XL (646)
•	Other ranges: XS–XXXL (422), numeric sizes (224 & 237), larger sizes (169 & 108), and Onesize (167)
7.	Category-Wise Average Price & Discount:
•	Overall average: Original Price ₹1678, Final Price ₹1573, Discount ₹106
•	Highest: Indian Wear – Final ₹2459, Discount ₹182
•	Lowest: Inner Wear & Sleep Wear – Final ₹744, Discount ₹64
•	Most other categories: Final prices between ₹1300–₹1800 with moderate discounts.
8.	Product Count by Gender:
•	Total products: 4,999
•	Women’s products: 3,062 (majority share)
•	Men’s products: 1,937
•	Women’s category has more products compared to Men’s, making up the larger portion of the total.
# Key Insights:
1.	Women drive sales – They account for the majority of purchases (61%) and spend more per item, making them the most valuable customer segment.
2.	Category preferences differ – Women lean toward Western & Indian Wear, while men focus on Topwear & Bottom Wear. Sports Wear is the only balanced category.
3.	Pricing shows a gap – Women’s purchases are costlier and attract bigger discounts, suggesting stronger promotional targeting in women’s categories.
4.	ROADSTER dominates – It leads both in product count and sales value, far ahead of other brands.
5.	Customer satisfaction is strong – Average ratings are consistently high (4.5+), showing reliable product quality across brands.
6.	Size ranges are diverse – XS–XL and S–XXL are most common, but plus-size and numeric ranges show inclusivity.
7.	Category pricing varies – Indian Wear is premium (₹2459 avg.), while Inner Wear & Sleep Wear is budget-friendly (₹744 avg.).
8.	Women’s product variety is larger – More products are offered for women, aligning with their higher purchase share.
# Conclusion:
Women are the primary drivers of sales, contributing the majority of purchases and higher spending, supported by wider product variety and stronger discounts. ROADSTER dominates brand performance, while mid‑range brands show steady contributions with consistently high customer satisfaction. Overall, the market is women‑centric, with opportunities to expand unisex categories, balance reliance on ROADSTER, and leverage growth potential in Sports Wear.
