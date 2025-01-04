# Airbnb Analysis: Insights into Vancouver Listings

## About
This project leverages Tableau dashboards to analyze Airbnb data, focusing on review scores, price dynamics, and neighborhood-level insights in Vancouver. The analysis provides actionable recommendations for Airbnb hosts to improve their offerings and remain competitive in the market.

---

## How to View the Dashboards
1. Access the dashboards on Tableau Public:
   - [Review Analysis](https://public.tableau.com/app/profile/brian.zhang1004/viz/2_1-2_4AirbnbAnalysis/2_4-ReviewAnalysis)
   - [Listing Growth](https://public.tableau.com/app/profile/brian.zhang1004/viz/1_1-1_5AirbnbAnalysis/1_2-ListingGrowth)
2. Interact with the filters to explore neighborhood-specific insights.

---

## Dashboards
### **1. Average Rating Across Vancouver Neighborhoods**
- **Description**:
  - A heatmap visualization of average review scores across Vancouver neighborhoods.
  - Highlights areas like Shaughnessy with the lowest average score and Kitsilano with the highest (4.83).
  - Offers benchmarks for expected accommodation quality in each neighborhood.

### **2. Review Rating Decomposition**
- **Description**:
  - A stacked bar chart breaking down review scores into individual components:
    - Location
    - Check-in
    - Cleanliness
    - Communication
  - Uses standardized scores for better comparison across metrics and neighborhoods.
  - Findings:
    - Kitsilano ranks the highest in total standardized review scores.
    - Downtown Eastside has the lowest location score, likely due to its high crime rates.

### **3. Relationship Between Price and Review Categories**
- **Description**:
  - A scatter plot with linear trend lines showing the relationship between standardized review scores and price.
  - Cleanliness emerges as the most impactful factor, with the steepest slope (15.33), followed by Location (10.24) and Communication (8.69).
  - Includes an interactive neighborhood filter to explore localized insights.
  - Limits analysis to listings priced between $0 and $1,000 to address outliers and skewed results.

### **4. Analysis of Reviews by Neighborhoods Dashboard**
- **Description**:
  - A final interactive dashboard combining all three analyses.
  - Allows hosts to compare neighborhoods based on accommodation quality and pricing.
  - Provides an overview of how individual neighborhoods perform against others.

---

## Features
- **Neighborhood-Level Insights**:
  - Benchmarking of review scores by neighborhood.
  - Identification of key factors affecting guest satisfaction.
- **Price Analysis**:
  - Understanding how review scores impact pricing.
  - Insights into marginal financial benefits of improving specific review categories.
- **Interactive Dashboards**:
  - Filters for customized views by neighborhood.
  - Comprehensive visualizations combining multiple analyses.

---

## Tools & Technologies
- **Visualization**: Tableau Public
- **Data Source**: Airbnb Listings and Reviews Data (Vancouver)

---

## Insights
- **Cleanliness is Key**: Among review metrics, cleanliness has the strongest positive impact on price.
- **Neighborhood Matters**: Quality expectations and pricing vary significantly across neighborhoods like Kitsilano and Shaughnessy.
- **Actionable Recommendations**:
  - Hosts in neighborhoods with lower scores can prioritize cleanliness and location-related improvements to drive higher prices and better reviews.

---

## Limitations
1. **Data Scope**:
   - Focused solely on Vancouver, limiting generalizability to other markets.
2. **Statistical Significance**:
   - Linear relationships require further validation for causal inferences.
3. **Data Range**:
   - Analysis restricted to listings priced below $1,000 to avoid outliers.




