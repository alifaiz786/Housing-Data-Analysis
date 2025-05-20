# Housing-Data-Analysis
# 🏡 Housing Market Dashboard (Power BI Project)

This Power BI project provides a comprehensive analysis of housing market trends in Denmark. Using a dataset of 100,000 real estate transactions, the report delivers actionable insights into regional pricing trends, sales performance, and house-type metrics — supporting smarter property decisions and policy evaluation.

---

## 📂 Project Structure


---

## 📊 Report Pages & Visualizations

### 1. **House Market Overview**
- 📌 **Median Sales Price Change by Region** – Bar chart showing price trends by region (e.g., Jutland, Zealand)
- 🏠 **Units Sold & 12-Month Sales** – KPIs to summarize market volume
- 📈 **Offer Price vs Purchase Price** – Scatter plot showing negotiation patterns
- 📉 **YoY Sales Growth by Sales Type** – Line & area chart capturing yearly change across sales channels

---

### 2. **Sales Performance**
- 📍 **Sales by Region** – Bar chart highlighting total volume in billions by region
- 📌 **Key Influencers** – AI visual showing what factors (like age) influence price drops
- 🧾 **Sales Table** – Detailed breakdown by Year, Quarter, and Purchase Price
- 📊 **Offer-to-SQM Ratio by Sales Type** – Measures value per square meter by sales channel
- 🔵 **Average Price per SQM by Region** – Donut chart for price efficiency analysis

---

### 3. **House Type Analysis**
- 🏘 **Avg Offer vs Purchase Price by House Type** – Side-by-side bar chart comparing prices
- 📉 **Avg Inflation / Interest / Yield Rates** – Economic context for each house type
- 📏 **Avg SQM / SQM Price by House Type** – Combined bar-line chart visualizing cost per unit area

---

## 🧠 Key Metrics Used

- `purchase_price`: Final price paid for the house
- `offer_price` (derived): Implied from % difference
- `sqm`: Size of the house in square meters
- `sqm_price`: Unit price per square meter
- `yield_on_mortgage_credit_bonds%`, `inflation`, `interest`: Market rates
- `region`, `sales_type`, `house_type`: Category filters used in slicing data

---

## 🛠 Tools & Skills Demonstrated

- **Power BI Desktop**: Data modeling, DAX measures, report layout
- **Data Cleaning**: Handling missing `city`, `yield`, and `inflation` values
- **KPI Visuals**: Sales totals, averages, and growth
- **Custom Filters**: Dynamic filtering by `area`, `city`, `region`, `sales_type`
- **Business Storytelling**: Visually communicating negotiation patterns, market shifts, and affordability

---

## 📝 How to Use

1. Clone/download this repo.
2. Open `Housing.pbix` in **Power BI Desktop**.
3. Use filters in the **"House Type Analysis"** tab to explore insights.
4. Cross-filter by region, sales type, or city for localized trends.

