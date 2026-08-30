# Mobile-Phone-Pricing-Update

## Objective:
To update and analyse promotional pricing for 30 mobile phone products across multiple e-commerce platforms and evaluate profitability, pricing competitiveness, and potential pricing risks using Microsoft Excel.

## Overview:
- This project focuses on analysing promotional prices for iPhone and Samsung products across Shopee, Lazada, TikTok Shop, and the Company Website.
- The analysis evaluates the impact of platform fees on profitability and identifies products with low margins, negative profit, and potential pricing inconsistencies.

## Project Workflow

1. Data Preparation & Calculations:
   
- Created a structured workbook containing a Cleaned Data sheet and Working Sheet
- Used VLOOKUP to automatically retrieve product cost prices from the master data
- Calculated Revenue After Platform Fee
- Calculated Profit and Profit Margin (%)
- Created a Status field to identify profitable and loss-making products
- Applied Conditional Formatting to automatically highlight high-risk products

2. Pricing Analysis & Dashboard:

- Compared promotional prices against competitor prices
- Analysed the effect of platform fees on product profitability
- Compared average profit margins across Shopee, Lazada, TikTok Shop, and Website
- Identified products with negative and low profit margins
- Created an interactive Excel Dashboard containing:
  1. KPI Summary
  2. Products at Risk
  3. Platform Performance

## Analysis & Report 

## 1. Summary of Updates
Promotional prices for 30 mobile phones were updated across Shopee, Lazada, TikTok Shop, and the Company Website. 
All calculations, including revenue after platform fees, profit, profit margin, status, and risk level, were automated 
using Excel formulas and VLOOKUP in the "Working Sheet". A clean Dashboard was also created to provide a quick overview 
of pricing performance and potential risks.

## 2. Pricing Inconsistencies Identified
1. Aggressive Shopee Pricing: Several high-value iPhones, particularly the iPhone 16 series and iPhone 15 Pro models, are priced 
below or close to competitor prices. After the 8% platform fee, some generate very low or negative profit margins.
2. Loss-Making Products: 2 products are currently identified as Loss Risk, with negative profit margins.
3. Uncompetitive TikTok Shop Pricing: Some products are priced higher than competitors while still generating low profit margins.
4. Platform Margin Gap: The Company Website generates the highest average margin at approximately 12.7%, benefiting from zero platform fees. However, the most aggressive pricing is concentrated on higher-fee platforms such as Shopee and Lazada.

Main Issue: The current promotional strategy prioritises competitive pricing but does not sufficiently protect profit margins after platform fees.

## 3. Products Flagged for Risk (Losses / Tight Margin)
Critical Issues (Loss Risk - Negative Profit):
•	iPhone 16 128GB (Shopee) → Margin: -1.26%
•	iPhone 15 Pro 512GB (Shopee) → Margin: -1.40%
High Risk Products (Very Tight Margin < 2%):
•	iPhone 16 Pro 256GB (TikTok Shop) 
•	iPhone 15 256GB (Shopee) 
•	iPhone 16 Pro 512GB (TikTok Shop) 
•	iPhone 15 512GB (Shopee) 
•	iPhone 16 Pro 256GB (TikTok Shop)

Total: 12 products (40% of all promoted items) have margins below 5%. Most of them are on Shopee. 
Recommendation: Immediately review and adjust prices for the 2 Loss Risk products before the weekend promotion goes live.


## Key Question 

## 1. Which products are at risk of making a loss?
- Two products were identified as having negative profit margins:

iPhone 16 128GB (Shopee): -1.26% margin
iPhone 15 Pro 512GB (Shopee): -1.40% margin

- These products should be reviewed before the promotional campaign goes live.

## 2. How many products have low profit margins?
A total of 12 out of 30 products (40%) have profit margins below 5%.
Most of these products are concentrated on Shopee, indicating that platform fees combined with aggressive promotional pricing are putting pressure on profitability.

## 3. Which platform provides the highest profitability?
The Company Website provides the highest average margin at approximately 12.7%.
This is largely because the Website does not incur the same platform fees as Shopee, Lazada, and TikTok Shop.

## 4. How do platform fees affect profitability?
Platform fees significantly reduce the revenue retained from each sale.
Some products that appear competitive based on their promotional price become low-margin or loss-making after platform fees are deducted.
This shows that competitor pricing should not be evaluated without considering the platform's associated costs.

## 5. Are there pricing inconsistencies across platforms?
Yes. Several pricing inconsistencies were identified.
Some Shopee products were priced aggressively below or close to competitor prices despite having very low margins.
Some TikTok Shop products were priced higher than competitors while still generating relatively low margins.
The most aggressive pricing was concentrated on platforms with higher fees.

## 6. What is the main pricing issue identified?
The main issue is that the promotional strategy appears to prioritise beating competitor prices over protecting profit margins.
A product may appear competitively priced but become unprofitable after platform fees are taken into account.

## Key Finding 
- 12 out of 30 products (40%) have profit margins below 5%.
- 2 Shopee products are currently loss-making, with margins of -1.26% and -1.40%.
- Shopee has the highest concentration of low-margin products due to aggressive pricing combined with platform fees.
- The Company Website has the highest average margin at approximately 12.7%.
- Some TikTok Shop products are priced above competitors while still generating low margins.
- The current pricing strategy prioritises competitor pricing but does not consistently protect profitability after platform fees.

## Recommendations
1. Review and adjust the 2 loss-making Shopee products before the promotion goes live.
2. Establish a minimum 5% margin threshold and automatically flag products below it.
4. Use platform-specific pricing that accounts for different platform fees.
4. Review TikTok Shop products that are both relatively expensive and low-margin.
5. Implement a centralised master pricing system with automated validation.
6. Add an approval step before promotional prices are published.
7. Create standardised export templates to make future pricing updates faster and more consistent.

## Tools Used:
- Microsoft Excel (Pivot Tables, charts, basic formulas)

## Files Included:
- Bike Raw Dataset.xlsx
- Bike Cleaned Data & Dashboard.xlsx
