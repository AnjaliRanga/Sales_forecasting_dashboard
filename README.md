#  Super Store Sales Forecasting Dashboard

An interactive Power BI report featuring sales analysis and 20-day sales forecasting for a retail super store with multi-regional operations.

##  Key Metrics

- **Total Sales**: $252K
- **Total Profit**: $27K
- **Order Count**: 931 orders
- **Average Shipping Time**: 4 days
- **Time Period**: 2019-2020 data with forecasting into 2021

##  Features

### Page 1: Sales Dashboard
- **Sales Overview**: Real-time KPIs for sales, profit, orders, and shipping
- **Regional Analysis**: Interactive US map showing sales distribution by state
- **Sales by Month**: Year-over-year comparison (2019 vs 2020) with trend lines
- **Profit Trends**: Monthly profit analysis with seasonal patterns
- **Category Breakdown**: Hierarchical view of sales by category and sub-category
- **Sales Channels**: Analysis by ship mode and payment methods
- **Segment Distribution**: Consumer (54%), Corporate (30%), Home Office (16%)

### Page 2: Sales Forecasting
- **20-Day Forecast**: Predictive analytics showing expected sales trends
- **Historical Pattern Analysis**: 2-year historical data (2019-2020)
- **State-wise Forecast**: Top performing states with projected sales
- **Confidence Intervals**: Visual representation of forecast accuracy range
- **Interactive Timeline**: Adjustable date range for custom forecasting

##  Key Insights

### Sales Performance
- California leads with $0.34M in sales
- Standard shipping dominates (0.13M orders)
- Consumer segment generates 54% of total sales
- COD payment method accounts for 44% of transactions

### Forecasting Highlights
- Peak sales periods identified in October-December
- Average daily sales forecast: ~5K
- Highest forecast peak: 10.6K (projected January 2021)
- Sales volatility patterns identified for inventory planning

### Category Analysis
- **Office Supplies**: $99,652.14
- **Technology**: $79,484.07
- **Furniture**: $72,984.87
- Top sub-categories: Storage, Binders, Paper, Appliances

##  Tools & Technologies

- **Microsoft Power BI Desktop** - Report creation
- **Power BI Forecasting** - Built-in time series forecasting
- **DAX** - Custom calculations and measures
- **Power Query** - Data transformation
- **Bing Maps** - Geographic visualization

##  Project Structure
```
Super-Store-Sales-Forecasting/
│
├── Super-Store-Dashboard.pbix    # Main Power BI file
├── data/                          # Source data files
│   └── sales_data.csv
├── screenshots/                   # Dashboard images
│   ├── page1_dashboard.png
│   └── page2_forecast.png
└── README.md
```

##  Forecasting Methodology

The forecast uses Power BI's built-in exponential smoothing algorithm:
- **Forecast Length**: 20 days
- **Confidence Interval**: 95%
- **Historical Data**: 2 years (2019-2020)
- **Seasonality**: Auto-detected patterns
- **Accuracy**: Visual confidence bands shown in forecast charts

##  Business Use Cases

- **Inventory Planning**: Predict stock requirements based on sales forecast
- **Resource Allocation**: Staff scheduling aligned with predicted busy periods
- **Budget Planning**: Revenue projections for financial planning
- **Marketing Strategy**: Timing promotions based on sales patterns
- **Supply Chain**: Optimize shipping and logistics based on regional demand

##  Dashboard Features

-  Multi-page report with drill-through capability
-  Interactive filters by region and year
-  Dynamic KPI cards with real-time updates
-  Geographic heat map visualization
-  Advanced forecasting with confidence intervals
-  Year-over-year comparison charts
-  Category hierarchy with drill-down
-  Professional color-coded design

##  Data Schema

- Order ID, Order Date, Ship Date
- Customer details (Name, Segment, Region, State)
- Product details (Category, Sub-Category)
- Sales, Profit, Quantity, Discount
- Ship Mode, Payment Mode

##  Future Enhancements

- [ ] Add customer segmentation analysis
- [ ] Include discount impact analysis
- [ ] Integrate real-time data refresh
- [ ] Add product-level forecasting
- [ ] Create mobile-optimized view
- [ ] Add what-if scenario analysis


