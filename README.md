# Aurora Threads Boutique: Sales Performance Dashboard

**Tools:** Power BI, DAX, Power Query (M language), Excel
**My role:** Data Analyst

**Data:** Excel workbook of boutique sales transactions (771 units sold across 3 stores and 31 customers).

## Business overview
Aurora Threads is a high-end fashion boutique specialising in designer clothing, shoes and accessories. It is known for a distinctive collection and a personalised shopping experience, and it operates several branches across different cities, serving fashion-conscious clients. To stay ahead in a competitive retail market, the boutique wants to use data-driven strategies.

## The business problem
Aurora Threads has a growing volume of data but struggles to turn it into actionable insight. It finds it hard to spot trends across product categories and to track performance efficiently. Without advanced analytics, the team cannot make timely, well-informed business decisions.

## Project aim
Use DAX and M language in Power BI to answer key business questions about sales performance, customer behaviour and product trends, using dynamic calculations that give the boutique clear, actionable insights.

## My role and approach
1. **Customer purchase categories (M language):** created a custom column that groups purchases into Low, Medium and High quantity categories, to show how many products fall into each band. [Add the thresholds you used.]
2. **Revenue after discount (DAX calculated column):** created a column that removes the discount from each transaction, giving the true revenue per transaction. [Paste your formula here.]
3. **Weekday (DAX calculated column):** created a column showing the weekday of each transaction, to support analysis of sales patterns by day. [Paste your formula here.]
4. **Total quantity sold (DAX measure):** created a measure that totals units sold and recalculates as the report is filtered by store. [Paste your formula here.]
5. **Dashboard:** built a one-page Power BI report with store slicers (Store A, B and C), KPI cards, charts and a customer table.



## Key findings
- **Headline numbers:** 771 units sold, about $288K in revenue, 3 stores and 31 customers.
- **Top categories:** Accessories lead with $148K (about 51% of revenue), well ahead of Clothing ($71K) and Footwear ($70K).
- **Top products:** Handbag ($24K), Necklace ($22K), Sunglasses and Wallet ($19K each). Accessories make up 6 of the top 10 products.
- **Sales trend:** daily revenue is highly variable. Peaks reach about $24K and $22K, while quieter days fall to around $2K to $3K.
- **Gender split:** Unisex items generate $121K (41.9%), Female $102K (35.4%) and Male $65K (22.7%).
- **Payment types:** Cash ($88K, 30.6%) and Online Payment ($87K, 30.1%) are the most popular, followed by Credit Card ($72K, 25.0%) and Debit Card ($41K, 14.3%).
- **Customers:** the top customer (CUST006) spent $24,000 on 30 units. The seven highest-spending customers, about 23% of all customers, account for roughly 46% of revenue.

## Recommendations
1. **Protect and grow the accessories range.** Accessories drive about half of revenue, so keep best sellers such as handbags, necklaces and sunglasses well stocked.
2. **Cross-sell across categories.** Clothing and Footwear each contribute around a quarter of revenue. Outfit bundles that pair them with accessories could lift their sales.
3. **Expand the unisex range and grow the male segment.** Unisex is the largest segment, and male customers contribute the least, which suggests room for targeted ranges or campaigns.
4. **Reward top customers.** A small group of customers generates nearly half of revenue, so a VIP or loyalty programme fits the boutique's personalised service and reduces the risk of relying on a few buyers.
5. **Investigate daily peaks and slumps.** Check what drove the high-revenue days (promotions, paydays, weekends) using the weekday column, then plan staffing, stock and promotions for the quiet days.
6. **Keep all payment options and keep online payment reliable.** Online payment is already almost as popular as cash.

## What I learned
This project strengthened my DAX and Power Query skills, especially the difference between calculated columns and measures, and showed me how to turn a set of visuals into clear recommendations for a retail business.

## Repository contents
- README.md: this write-up
- data/: the Excel dataset
- dashboard/: screenshot of the final dashboard
- powerbi/: the Power BI (.pbix) file
