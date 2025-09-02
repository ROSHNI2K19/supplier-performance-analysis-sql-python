# 📊 Supplier Performance Analysis  

## 📌 Project Overview  
This project focuses on optimizing supplier performance for a Liquor Store, using purchase, sales, and inventory data.  

Through data integration and exploratory analysis, it identifies key cost drivers, profitability patterns, and supplier efficiency metrics to support procurement and supply chain decision-making.  

## 🎯 Objectives  
- Analyze the impact of purchase price, volume, and sales on profitability  
- Identify vendors with low inventory turnover and potential overstock risk  
- Explore cost efficiency from bulk purchasing and optimal purchase volumes  
- Highlight top-performing vendors for negotiation and strategy

## 🗂️ Dataset  
The project consolidates multiple tables from the database:  
- **BeginInventory / EndInventory** → Opening and closing stock levels  
- **Purchases / InvoicePurchases** → Vendor transactions & freight costs  
- **PurchasePricesDec** → Details such as description,size, volume etc.
- **Sales** → Revenue, quantity sold 

## 🔧 Tools & Technologies  
- **Python (Pandas, NumPy, Matplotlib, Seaborn)** – Data cleaning, transformation, EDA, and visualization  
- **SQLite** – Database integration and SQL queries

## 📈 Key Insights from Analysis  
1. **Price vs Sales Revenue** → Purchase price has almost no influence on sales dollars; however, higher purchase costs slightly reduce gross profit.  
2. **Volume vs Sales** → Buying more doesn’t directly scale sales in the same proportion; moderate correlation observed.  
3. **Profitability** → Profit margin is independent of sales dollars, meaning high revenue vendors are not always the most profitable.  
4. **Inventory Turnover** → No significant impact on gross profit, but low turnover vendors increase holding risks.  
5. **Bulk Purchasing Advantage** →  
   - Small purchases → avg. unit price **$27.1**  
   - Medium purchases → avg. unit price **$15.4** (~43% savings)  
   - Large purchases → avg. unit price **$10.6** (~60% savings vs. small purchases)
  
## 📢 Business Impact  
This analysis enables the business to:  
- Negotiate better vendor contracts by leveraging volume-based discounts  
- Reduce inventory costs by identifying low-turnover vendors  
- Focus on profitability rather than sales volume alone  
- Optimize procurement strategy to balance cost, revenue, and margin  

