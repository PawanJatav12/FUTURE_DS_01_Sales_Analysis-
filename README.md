# Business Sales Performance Analytics
### Future Interns - Data Science & Analytics Internship

**Name:** Pawan Kumar Jatav  
**Organization:** Future Interns  
**Track:** Data Science & Analytics  
**Task:** Task 1 - Business Sales Performance Analytics  
**GitHub Repo:** FUTURE_DS_01  

---

## Objective

Analyze business sales data to identify revenue trends, top-selling products, high-value categories, and regional performance. The goal was to generate actionable business insights from the data.

---

## Dataset

Since no dataset was provided, I created a realistic sales dataset using Python (numpy and pandas).

- Total Records: 1000 transactions
- Time Period: January 2023 to December 2023
- Columns: Order ID, Date, Product, Category, Region, Quantity, Unit Price, Discount %, Gross Revenue, Discount Amount, Net Revenue, Month, Quarter

---

## Tools and Libraries Used

- Python 3
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Analysis Performed

1. **KPI Summary** - Total Revenue, Total Orders, Units Sold, Average Order Value
2. **Monthly Sales Trend** - Revenue and order volume across all 12 months
3. **Product-wise Analysis** - Revenue and units sold per product
4. **Category Performance** - Electronics, Accessories, Wearables, Office Equipment
5. **Regional Performance** - North, South, East, West, Central regions
6. **Quarterly Comparison** - Revenue comparison across Q1, Q2, Q3, Q4
7. **Discount Impact** - How different discount levels affect orders and revenue
8. **Region x Product Heatmap** - Which products sell best in which regions

---

## Key Findings

- Laptop and Mobile Phone are the top revenue-generating products due to high price points
- Electronics category dominates overall revenue share by a big margin
- Most purchases happen at 0% discount — heavy discounts reduce revenue without proportional increase in orders
- Accessories category has decent order volume but very low revenue per order
- Some regions show high order count but lower average order value, meaning customers there prefer cheaper products

---

## Recommendations

- Increase stock and marketing focus on Laptop and Mobile Phone as they drive maximum revenue
- Avoid giving 15% to 20% discounts as they hurt overall revenue more than they help
- Run targeted campaigns in low-performing regions to expand customer base
- Use product bundling strategy for Accessories to increase average order value
- Plan inventory in advance for the best performing quarter based on seasonal trend

---

## Files in this Repository

| File | Description |
|------|-------------|
| `FUTURE_DS_01_Sales_Analysis.ipynb` | Main Jupyter Notebook with full analysis |
| `sales_data.csv` | Self-generated sales dataset |
| `kpi_dashboard.png` | KPI summary visualization |
| `monthly_trend.png` | Monthly revenue and order trend chart |
| `product_analysis.png` | Product-wise revenue and units chart |
| `category_analysis.png` | Category performance pie and bar chart |
| `regional_analysis.png` | Region-wise performance charts |
| `quarterly_analysis.png` | Quarterly revenue comparison chart |
| `discount_analysis.png` | Discount impact on orders and revenue |
| `heatmap_region_product.png` | Region x Product revenue heatmap |

---

## How to Run

1. Clone or download this repository
2. Open `FUTURE_DS_01_Sales_Analysis.ipynb` in Jupyter Notebook
3. Run all cells using **Kernel → Restart & Run All**
4. All charts and the CSV file will be generated automatically in the same folder

---

