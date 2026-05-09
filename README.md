# E-Commerce Behaviour Analysis
**Analyst:** Ibtisam Ahmed Khan  
**Dataset:** eCommerce Behavior Data — Multi Category Store (Oct 2019, REES46)  
**Tools:** Python, pandas, matplotlib, seaborn, scipy  

## Business Question
Where is this ecommerce platform losing customers, and what should the business do about it?

## Dataset
- 5 million user events from a real multi-category ecommerce store
- Three event types: view, add to cart, purchase
- Columns: event_time, event_type, product_id, category_code, brand, price, user_id, user_session

## Analysis Structure
| Section | What it covers |
|---|---|
| 1. Data Loading | Shape, columns, date range, missing values |
| 2. Data Cleaning | Time features, category extraction, brand cleaning |
| 3. Traffic Overview | Hourly and daily activity patterns |
| 4. Conversion Funnel | View → Cart → Purchase drop-off analysis |
| 5. Category Performance | Revenue, CVR, and cart abandonment by category |
| 6. Brand Performance | Top brands by revenue and conversion rate |
| 7. User Behaviour | Session depth, one-time vs returning users |
| 8. Price Sensitivity | Average price at each funnel stage, CVR by price bracket |
| 9. Findings and Recommendations | Three business recommendations + A/B test proposal |

## Key Findings
- **Cart abandonment is the #1 problem** — only ~40-50% of cart additions result in a purchase
- **Most users are one-time visitors** — a major retention opportunity
- **Electronics dominates revenue but underconverts** — comparison shopping behaviour detected
- **Price is not the barrier** — users purchase at higher prices than they browse, meaning checkout friction drives abandonment, not price resistance

## Recommendations
1. Simplify checkout and add progress indicators to reduce cart abandonment
2. Introduce personalised remarketing for users who viewed 3+ products without purchasing
3. Add a price-match guarantee badge on electronics product pages to reduce comparison shopping drop-off

## Proposed A/B Test
Testing a checkout progress bar to reduce cart-to-purchase drop-off — hypothesis, metrics, and expected lift defined in Section 9.

## Files
- `ecommerce-behaviour-analysis.ipynb` — full analysis notebook
- `findings_brief.txt` — plain-language findings summary

## How to Run
1. Download the dataset from [Kaggle](https://www.kaggle.com/datasets/mkechinov/ecommerce-behavior-data-from-multi-category-store)
2. Place `2019-Oct.csv` in the same folder
3. Run the notebook top to bottom
