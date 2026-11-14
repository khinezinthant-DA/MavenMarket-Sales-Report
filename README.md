# MavenMarket Sales Report | SQL and Power BI

An interactive Power BI dashboard analysing 1997-1998 sales data for MavenMarket,
a grocery chain with 24 stores across the USA, Mexico and Canada.

**Tools:** SQL, Power Query, Power BI, DAX, Data Modelling

## Problem Statement
MavenMarket had no single view of its sales performance. Management needed to
understand revenue and profit trends, which stores, regions and product tiers
drove growth, and which customer segments were most valuable, in order to make
better decisions on stores, pricing and loyalty.

## Approach
- Used SQL to query and prepare transaction, product, store, customer and
  calendar data.
- Cleaned and transformed the data in Power Query and built a star-schema
  data model.
- Created DAX measures for Total Revenue, Total Profit, Profit Margin,
  Quantity Sold and Total Transactions, plus a Price Tier field (Low / Mid / High).
- Built a 3-page interactive report with country and year slicers and page navigation.

## Dashboards Pages
**General Report** 
- KPIs, revenue trend with trendline, revenue by country, store opening and remodelling years
  <img width="1125" height="634" alt="Dashboard1" src="https://github.com/user-attachments/assets/56f6949b-233b-4b9c-8549-0bf2114d93f6" />
  
**Store and Product Analysis**
- Decomposition tree (country, city, store, store type), revenue by price tier and store type
  <img width="1127" height="632" alt="Dashboard2" src="https://github.com/user-attachments/assets/e819f2c4-58ec-4a6a-80da-963a90cbc37e" />
  
**Customer Analysis**
- Revenue by income level, member card, gender and country, plus top 10 customers
  <img width="1129" height="636" alt="Dashboard3" src="https://github.com/user-attachments/assets/e433d5fb-935d-4354-beb4-2d8cb4679d34" />

## Key Findings
- **$1.76M revenue, $1.05M profit (59.67% margin)** from 270K transactions
  and 833K units sold.
- Monthly revenue grew about **2.6x** ($46K to $120K) over 1997-1998, with a
  sharp jump in January 1998.
- The **USA generated about 67% of revenue**; Canada contributed only $0.11M,
  showing an expansion gap.
- **Mid-tier products drove about 66% of revenue**, and Supermarket formats
  about 83%.
- **Average-income customers contributed about 50% of revenue**, and Bronze
  members were the largest segment, pointing to where loyalty campaigns should focus.

## Dataset
MavenMarket retail dataset (1997-1998).
