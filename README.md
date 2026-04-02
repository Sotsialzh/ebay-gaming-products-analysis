eBay Market Analysis: Gaming Peripherals & External Storage (March 2026)
📌 Project Overview
This project provides a deep dive into the e-commerce market for popular gaming peripherals and storage devices. Using a dataset of over 35,000 real eBay listings from March 2026, the analysis focuses on pricing strategies, item conditions, and the correlation between seller reputation and consumer trust.

The goal is to extract actionable insights for price prediction, market trend forecasting, and consumer behavior studies in the gaming industry.

📊 Dataset Breakdown
The dataset includes four major product categories:

💾 External Hard Drives & SSDs: 16,549 listings (external_hd)

🖱️ Gaming Mice: 11,280 listings (gaming_mouse)

⌨️ Gaming Keyboards: 7,321 listings (gaming_keyboard)

🎧 Gaming Headsets: 279 listings (gaming_headset)

🔍 Key Features & Attributes
Each listing in the dataset contains rich metadata for granular analysis:

Product Info: Title, Category, and Direct URL.

Pricing & Logistics: Sale price (USD), separate shipping costs, and cleaned sale dates.

Condition: Categorized as Brand New, Pre-Owned, or Open Box.

Social Proof: Product ratings and review counts.

Seller Metrics: Feedback percentage, rating, and total feedback count (crucial for trust analysis).

🎯 Potential Applications
Price Optimization: Developing models to predict the final sale price based on condition and seller rating.

Competitive Analysis: Comparing top gaming brands vs. generic products.

Trust Analysis: Investigating how seller feedback scores impact sales volume and pricing.

Market Trends: Identifying the most "liquid" categories (e.g., SSDs vs. Peripherals).

🛠️ Data Quality & Preprocessing
To ensure the data is "analysis-ready," the following steps were taken:

Date Cleaning: Removed "Sold" prefixes and standardized date formats.

Parsing: Seller feedback metrics were split into separate columns for easier calculation.

Handling Nulls: Identified that "New" products often have N/A ratings due to a lack of initial reviews.

Currency Standardization: All pricing is normalized to USD.
