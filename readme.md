# 🏠 Dubai Real Estate Market Analysis Dashboard

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)
![Status](https://img.shields.io/badge/Status-Complete-success?style=for-the-badge)

A comprehensive 3-page interactive Power BI dashboard analysing 2,000+ properties across 26 Dubai locations worth **8.6 Billion AED**, enabling data-driven real estate investment decisions.

---

## 📊 Project Overview

This dashboard provides comprehensive market intelligence for Dubai's real estate sector, featuring:
- **Executive Overview** with market-level KPIs and trends
- **Location-Specific Analysis** with comparative insights
- **Detailed Property Listings** with advanced filtering and drill-through capabilities

### Key Business Questions Answered:
- Which Dubai locations offer the best investment opportunities?
- What is the price differential between premium and standard areas?
- How do property prices vary by type, size, and location?
- What are the market trends across different property categories?

---

## 🎯 Key Features

### Page 1: Overview Dashboard
- **Market KPIs**: Total properties, average price, total market value, average size
- **Geographic Distribution**: Tree Map showing property count across all 26 locations
- **Price Comparison**: Top locations by average price
- **Property Mix**: Distribution by type (Apartment, Villa, Townhouse, Penthouse, Studio)
- **Trend Analysis**: Price and volume trends over time
- **Category Analysis**: Bedroom distribution across properties

### Page 2: Location Deep Dive Analysis
- **Dynamic Location Selector**: Choose any of 26 Dubai locations
- **Context KPIs**: Properties count, average price, price per sqft, market ranking
- **Comparative Analysis**: Selected location vs all others with market average reference
- **Property Mix**: Type distribution within selected location
- **Price Distribution**: Histogram showing price ranges
- **Heatmap Matrix**: Conditional formatting showing prices across locations and types

### Page 3: Property Details & Listings
- **Comprehensive Table**: 2,000 property records with 11 key attributes
- **Advanced Filtering**: Multiple slicers for location, type, bedrooms, price, furnishing, year
- **Scatter Analysis**: Size vs Price correlation with trendline
- **View Analysis**: Distribution by view type (Sea, Golf, Garden, City, Marina)
- **Drill-Through Navigation**: Right-click any location to see detailed properties
- **Export Capability**: Download filtered data to Excel

---

## 📈 Key Insights

### Market Intelligence Discovered:
- **Market Size**: 2,000 properties valued at 8.6 Billion AED
- **Premium Locations**: Downtown Dubai (5.8M), Emirates Hills (5.5M), Palm Jumeirah (5.5M)
- **Price Gap**: **53% differential** between premium (#3 Palm Jumeirah: 5.5M) and standard locations (#24 Discovery Gardens: 3.6M)
- **Luxury Market**: 39% of properties are 4+ bedrooms, indicating luxury market dominance
- **Property Distribution**: Balanced mix across types (20% each)
- **View Preferences**: Equal distribution across all view types (~400 properties each)

### Investment Insights:
- Premium locations (Palm Jumeirah, Emirates Hills, Downtown) show consistent high pricing
- Villas command highest prices in premium locations (9.3M AED in Palm Jumeirah)
- Standard locations like Discovery Gardens offer 35% lower pricing for similar property types
- 5M+ price range dominates the market (36 properties in premium locations)

---

## 🛠️ Technical Implementation

### Data Transformation
- **Power Query M Code**: 15+ calculated columns for enriched analysis
- **Data Cleaning**: Duplicate removal, null handling, type conversion
- **Feature Engineering**: Price ranges, property categories, location tiers, size categories

### DAX Measures (30+)
- **KPIs**: Total Properties, Average Price, Total Value, Price per SqFt
- **Comparative**: Above/Below Average, Premium vs Standard differential
- **Rankings**: Location Price Rank, Property Count Rank
- **Time Intelligence**: Year, Quarter, Month calculations
- **Percentages**: % of Total, % Furnished, % Above Average
- **Conditional**: Price Colour coding for formatting

### Advanced Features
- **Drill-Through Navigation**: Cross-page interaction from overview to details
- **Conditional Formatting**: Colour gradients in matrix (blue=low, red=high)
- **Interactive Filtering**: Dynamic slicers affecting all visuals
- **Reference Lines**: Market average comparison
- **Scatter Analysis**: Size-price correlation with trendline
- **Export Functionality**: Table data export to Excel

### Visualizations Used
- KPI Cards, Tree Map, Bar Charts, Donut Chart, Line & Column Chart
- 100% Stacked Bar, Histogram, Matrix with Heatmap, Scatter Plot, Table

---

## 💻 Technologies Used

- **Power BI Desktop**: Dashboard development and visualization
- **DAX (Data Analysis Expressions)**: 30+ measures for calculations
- **Power Query M**: Data transformation and modelling
- **Data Modelling**: Relationships and calculated columns

---

## 📸 Screenshots

### Page 1: Overview Dashboard
<img width="1276" height="736" alt="page1-overview" src="https://github.com/user-attachments/assets/e7bb80e9-dcea-4b45-9690-ae0c582c281a" />
*Market-level insights with KPIs, geographic distribution, and trend analysis*

### Page 2: Location Analysis
<img width="1277" height="732" alt="page2-location-analysis" src="https://github.com/user-attachments/assets/fa43aab3-f204-4089-b016-4133db6a2e57" />
*Deep dive into Palm Jumeirah showing premium location characteristics*

### Page 3: Property Details
<img width="1285" height="738" alt="page3-property-details" src="https://github.com/user-attachments/assets/a9f3b44b-8c77-4b36-877b-7dd1feef8196" />
*Comprehensive property listings with advanced filtering and scatter analysis*

---

## 📁 Project Structure

```
dubai-real-estate-Power BI/
├── Dubai_Real_Estate_Dashboard.pbix    # Power BI dashboard file
├── Dubai_Real_Estate_Dataset.csv       # Sample dataset
├── README.md                            # Project documentation
└── screenshots/                         # Dashboard screenshots
    ├── page1-overview.png
    ├── page2-location-analysis.png
    └── page3-property-details.png
```

---

## 🚀 How to Use

### Requirements
- Power BI Desktop (latest version)
- Windows 10 or later

### Steps
1. Download `Dubai_Real_Estate_Dashboard.pbix`
2. Open with Power BI Desktop
3. Navigate through 3 pages:
   - **Overview**: Market intelligence
   - **Location Analysis**: Select location from dropdown
   - **Property Details**: View all properties, apply filters
4. **Drill-Through**: Right-click any location → Drill through → Property Details
5. **Export**: Click "..." on table → Export data → Excel

---

## 📊 Dataset Information

### Data Source
- Synthetically generated realistic Dubai real estate data
- 2,000 property records across 26 Dubai locations
- Property types: Apartment, Villa, Townhouse, Penthouse, Studio
- Date range: 2020-2025

### Key Columns
- Property_ID, Property_Type, Location, Bedrooms, Bathrooms
- Size_sqft, Price_AED, Price_per_sqft, Furnishing
- Year_Built, Listing_Date, Amenities, View_Type, Parking_Spaces

---

## 🎓 Learning Outcomes

This project demonstrates proficiency in:
- ✅ End-to-end Power BI dashboard development
- ✅ Advanced DAX measure creation and optimization
- ✅ Data modelling and transformation with Power Query
- ✅ Interactive visualization design and UX principles
- ✅ Business intelligence and analytical thinking
- ✅ Real estate market analysis and insights generation

---

## 🎯 Business Impact

### For Real Estate Firms:
- **Investment Decision Support**: Identify high-ROI locations
- **Market Intelligence**: Understand pricing dynamics across Dubai
- **Portfolio Analysis**: Compare properties across multiple dimensions
- **Competitive Analysis**: Benchmark against market averages

### For Investors:
- **Location Comparison**: Instantly compare 26 Dubai areas
- **Price Optimization**: Find best value properties
- **Trend Analysis**: Understand market movements
- **Property Search**: Advanced filtering for specific requirements

---

## 👨‍💻 About the Author

**Sukesh Singla**
- Data Analyst | Business Intelligence Specialist
- 13+ years experience in data analytics and operations
- Certified in Data Science, Machine Learning, Power BI

### Connect With Me
- 📧 Email: ssingla25@gmail.com
- 💼 LinkedIn: [linkedin.com/in/sukesh-singla-667701a5](https://linkedin.com/in/sukesh-singla-667701a5)
- 🌐 Location: Delhi, India | Open to Dubai opportunities

---

## 🏆 Project Highlights

- **Complete Dashboard Lifecycle**: From data collection to deployment
- **Professional Design**: Clean, intuitive, and user-friendly interface
- **Advanced Features**: Drill-through, conditional formatting, dynamic filtering
- **Business-Focused**: Delivers actionable insights, not just visualizations
- **Portfolio-Ready**: Demonstrates job-ready Power BI skills

---

## 📝 Future Enhancements

- [ ] Integrate Python visuals for advanced analytics
- [ ] Add predictive modelling for price forecasting
- [ ] Create mobile-optimized layout
- [ ] Publish to Power BI Service with scheduled refresh
- [ ] Add bookmarks for guided storytelling
- [ ] Integrate with real-time Dubai property APIs

---

## 📄 License

This project is available for educational and portfolio purposes.

---

## 🙏 Acknowledgments

- Dubai real estate market research for insights
- Power BI community for best practices
- Data visualization principles from industry standards

---

## ⭐ Star This Repository

If you found this project helpful or interesting, please give it a star! ⭐

---

**Last Updated**: January 2025

**Status**: ✅ Complete and Production-Ready
