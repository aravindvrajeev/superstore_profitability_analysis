# Superstore Profitability Analysis

## Project Overview
At first glance, the Superstore's highest-revenue products might seem like its most valuable. This analysis tests that assumption — investigating where the store is generating revenue without generating profit, what is driving that disconnect, and whether the pattern holds across customer segments and shipping methods.

---

## Key Questions
- What trends do the top-revenue products in each category show with respect to profitability?
- How does the revenue-profitability relationship vary across customer segments?
- How has discounting affected the profitability of products?
- Does shipping method have an effect on the sales vs profitability relationship?

---

## Key Findings
- **High revenue does not equal high profitability.** Several top-selling sub-categories — Tables, Bookcases, and Machines — carry negative or thin profit margins. Tables generates $207K in revenue but loses $17.7K — a -8.6% margin.
- **The pattern is universal across customer segments.** Consumer, Corporate, and Home Office segments all show the same revenue-margin disconnect.
- **Discounting is the primary driver of margin erosion.** Sub-categories with the highest margins are overwhelmingly sold at zero discount, while loss-making sub-categories rely heavily on moderate and heavy discounts.
- **Discounting is not the sole explanation.** Supplies show negative margins despite minimal discounting, while Binders and Copiers maintain healthy margins despite significant discounts.
- **Shipping method does not drive the disconnect.** The same sub-categories underperform on margins regardless of shipping mode.
- **Recommendation:** The store should review its discounting policy on high-revenue, low-margin sub-categories — particularly Tables and Machines. The cases of Supplies, Binders, and Copiers suggest that a blanket strategy of reducing discounts is not sound and a targeted approach is needed.

---

## Limitations
1. Region-wise profitability analysis was not carried out in the Python section, though SQL queries indicate the same sub-categories underperform across regions with some region-specific variation.
2. The relationship between order volume and per-unit profitability was not explored.
3. The dataset does not include cost-of-goods data which could have provided indication for products producing low margins without high discounts.

---

## Tools Used
- Python (pandas, matplotlib, seaborn)
- SQL (SQLite — CTEs, window functions, CASE WHEN, LAG)
- Jupyter Notebook

---
## Screenshot
<img width="3856" height="2070" alt="discountvsprofit_margin" src="https://github.com/user-attachments/assets/f1dd243f-21cf-4e25-aa16-76aa6c0aafb2" />

## Project
[View Notebook](https://github.com/aravindvrajeev/superstore_profitability_analysis/blob/main/superstore_analysis.ipynb)
