# Pricing-transaction-dashboard
Power BI Pricing Dashboard - This project analyzes 10,000+ customer-level transactions across regions, countries, and products to uncover pricing, discount, and margin trends.  The dashboard visualizes key business KPIs, while identifying high-risk customers with low margins and high discounts.

# Pricing Case Study — Power BI Dashboard

# Objective
As a Senior Pricing Reporting Analyst in the Global Pricing Insights & Analytics team, the goal was to analyze customer-level transactions and deliver actionable insights on revenue, discounting, and margin performance.

# Key Business Questions
- How are revenue, volume, and pricing trending across months?
- Which customers, products, and regions contribute most to growth?
- Where do discounts or margins pose financial risk?
- How can pricing strategy improve profitability?

# Dataset
10,000 transactional rows with the following columns:
- Region, Country, Product, Customer, Month  
- Volume, List Price, Discount %, Revenue, and COGS  

# Dashboard Features
- **Revenue, Volume & ASP Overview**  
  Tracks overall business performance (Jan–Dec).
- **Customer / Product / Region Breakdown**  
  Highlights top contributors and outliers.
- **Discount & Margin Risk Analysis**  
  Flags high-discount, low-margin customer–product cases.
- **Pricing Variance (ASP Bands)**  
  Groups customers by ASP range to highlight extreme pricing outliers.

# Key KPIs
| Metric | Value | Insight |
|--------|--------|----------|
| Total Revenue | **$5.03B** | Healthy top-line, driven by Product B |
| Total Volume | **25M units** | Consistent across regions |
| ASP (Net) | **$201** | Recovered after Feb dip |
| Avg Discount % | **14%** | high in certain customers |
| Gross Margin % | **36%** | Good, but risks observed below 10% |

# Tools & Techniques
- **Power BI:** Dashboard creation, interactivity, storytelling  
- **Power Query:** Data cleaning & transformation  
- **DAX:** Custom measures for margin, discount & risk flags  
- **Excel:** Initial data exploration  

# Key Insights
- 158 transactions with **ASP < $50** (very low) → possible underpricing risk  
- 84 customers with **ASP > $500** → overpricing or niche deals  
- High-risk customers (discount >25% & margin <10%) identified for review  
- EMEA region leads in revenue share, APAC shows steep discount trends  

# Recommendations
1. Enforce **approval workflow** for discounts above 25%.  
2. Re-evaluate **low ASP segments (<$50)** for pricing leaks.  
3. Launch **margin recovery initiatives** for top 10 high-risk customers.  

# Dashboard Previews

**Overview Page**
![Overview Dashboard](Dashboard_Screenshots/Overview_Dashboard.png)

**Risk Analysis**
![Risk Analysis Dashboard](Dashboard_Screenshots/Risk_Analysis.png)

<img width="2190" height="1170" alt="Risk_Analysis png  " src="https://github.com/user-attachments/assets/08f757e0-a91f-41c1-8323-fa3e61b27c7a" />
<img width="2166" height="1140" alt="Overview_Dashboard png " src="https://github.com/user-attachments/assets/fe62b454-5fd2-48ed-be6e-3cdc209cbd6d" />

![Risk Analysis](Dashboard_Screenshots/Risk_Analysis.png)

---
📧 *Created by Agnes O Dieyi*  
🔗 Connect on [LinkedIn]https://www.linkedin.com/in/agnes-dieyi-7272bb157/
