# eniac-discount-analysis

Overview
This project analyzes sales, pricing, discount behavior, and seasonality within Eniac’s marketplace.
The goal is to provide data‑driven insights to help settle an ongoing strategic debate inside the company:

Marketing Team: believes discounts improve customer acquisition, satisfaction, and retention.

Board & Investors: worry that aggressive discounts reduce revenue and weaken Eniac’s premium positioning.

Using real marketplace data, this project evaluates how discounts are currently applied, how customers respond to them, and what discount strategy makes the most sense for Eniac moving forward.
 Repository Structure
Code
eniac-discount-analysis/
│
├── data/                # Raw CSV files
├── notebooks/           # Jupyter notebooks with full analysis
├── charts/              # Exported PNG charts
├── presentation/        # Final presentation (PPTX or PDF)
├── docs/                # Notes, summaries, explanations
└── README.md            # Project overview
 
 Business Questions
The analysis answers five key questions:

How many products are discounted?  
→ Identifies discount frequency and patterns.

How big are the offered discounts?  
→ Measures discount percentage relative to product price.

How do seasonality and special dates (Christmas, Black Friday) affect sales?  
→ Reveals demand peaks and timing for effective promotions.

How should products be classified into categories to simplify reporting?  
→ Creates a clean, usable category structure for analysis.

What is the distribution of product prices across categories?  
→ Shows price ranges and helps identify which categories tolerate discounts.

Key Insights
Discounts are present but generally moderate, often between 5–15%.

Seasonal spikes (especially Black Friday and Christmas) significantly increase sales volume.

Accessories and low‑priced items show high volume, making them ideal for targeted discounts.

Premium categories (laptops, tablets) have wide price ranges and should avoid aggressive discounting.

Monthly sales trends show strong Nov–Dec peaks and a January drop, supporting seasonal discount strategies.

Recommendation
Based on the data, Eniac should adopt a controlled, targeted discount strategy:

Apply small, selective discounts rather than aggressive ones.

Focus discounts on accessories and low‑margin items.

Use seasonal promotions during Black Friday and Christmas.

Introduce bundle discounts (case + screen protector, charger + cable).

Use threshold discounts (“Spend €80, get €10 off”) to increase basket size.

Avoid heavy discounts on premium products to protect brand positioning.

This approach balances customer growth (Marketing) with revenue protection (Investors).

 Tools & Technologies
Python (pandas, seaborn, matplotlib)

Tableau

Jupyter Notebook

GitHub for version control and project documentation

 Presentation
The final presentation summarizes the analysis, visual insights, and strategic recommendations.
It is available in the presentation/ folder.
