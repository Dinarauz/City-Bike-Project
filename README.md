# City Bike-Share User Behavior Analysis for Urban Transportation
**Industry:** Urban Transportation | Shared Mobility Analytics
**Analysis Type:** Customer Behavior & Time Series Analysis

![City Bike Rental Project-2](https://github.com/user-attachments/assets/781ceda3-b50a-4a4d-aec3-1b11499122c9)

## Executive Summary:
This project analyzes 15.3 million bike rides from December 2024 to May 2025 to understand user behavior patterns. The data shows that members make up 85% of rides with predictable weekday commute patterns, while casual riders lean toward weekend recreational use. Peak usage hits at 5-6 PM during evening rush hour, with strong seasonal growth from winter to spring. These insights help operations teams deploy bikes effectively and give marketing clear targets for converting casual riders into members.

## Business Problem
Urban bike-share programs need to figure out where bikes should go, when they're needed most, and how to convert casual riders into regular users.

**Questions I wanted to answer:**
1. When do people actually use these bikes?
2. Which stations are the busiest?
3. How do members and casual riders behave differently?
4. What seasonal patterns show up in the data?

## Solution & Methodology
Analyzed ride patterns by hour, day, and month | Compared member vs casual rider behavior | Mapped station-level traffic | Analyzed trip duration by user type | Identified commute vs recreational usage windows

**Tools Used:**
**Python:** Pandas, Seaborn, Matplotlib
**Storage:** Google Drive
**Dashboards:** Tableau, Power BI
**Techniques:** Time series analysis, customer segmentation, geospatial mapping

**Data Source**
https://s3.amazonaws.com/tripdata/index.html (15.3M rides, Dec 2024 - May 2025)

**Analysis Code:**


## Key Findings:
**Seasonal & Weekly Patterns**
May hit 4.31M rides while December only saw 182K - the winter-to-spring climb shows clear weather impact. Friday, Tuesday, and Thursday were busiest, with Saturday beating Monday but Sunday showing lowest volume. Members ride consistently all week; casual riders spike Friday-Saturday, creating a clear conversion opportunity.

**Rush Hour & Daily Patterns**
5 PM leads (evening rush), followed by 6 PM and 4 PM. Morning peak hits at 8 AM. Weekdays show bimodal patterns (morning/evening), while weekends peak at 2-3 PM for recreational use. This tells operations to stock commuter stations before 8 AM and 5 PM, then shift bikes to recreational spots on weekends.

**Member vs Casual Behavior**
Members: 85% of rides (efficient 12-15 min commutes) | Casual: 14% of rides (longer 15-35 min trips, weekend-focused). Casual riders at Central Park stations average much longer trips - likely sightseeing. Both groups prefer electric bikes during commute hours.

**Station Hotspots**
West 21st St & 6th Ave leads with ~60K rides. High-traffic stations cluster in Manhattan, serving both commuters and tourists. These locations need priority deployment during peak hours to avoid stockouts.

## Business Recommendations
**Operations:** Deploy more bikes to West 21st St & 6th Ave during 5-6 PM | Rebalance from Sunday to Friday-Saturday | Stock electric bikes during commute hours (8 AM, 5-6 PM)

**Marketing:** Target casual Friday-Saturday riders with membership campaigns | Run winter promotions to smooth seasonal dips | Highlight electric bike time savings
Infrastructure: Expand top 10 high-volume stations | Add stations along commute corridors | Upgrade Central Park area for recreational traffic

**Revenue:** Launch weekend packages for casual riders | Offer off-peak discounts (Sundays, midday) | Bundle electric bikes into premium memberships

## Expected Impact
My Python analysis identified the 5 PM peak and West 21st St & 6th Ave hotspot (~60K rides), directly informing where to deploy bikes. The 85% vs 14% split and different weekly patterns show marketing exactly who to target. The trip duration gap (members 12-15 min vs casual 15-35 min) backs up efficiency messaging. The seasonal swing (4.31M May vs 182K December) quantifies weather impact for fleet planning.

Dashboards let teams monitor real-time demand and adjust deployment hour by hour.

## Next Steps
**Future Enhancements:** Weather integration for demand forecasting | Customer lifetime value analysis for conversion ROI | A/B testing for membership messaging | Real-time alerts when stations run low

**Current Limitations:** Only 6 months of data (full year would show all seasons) | No weather data | Missing user demographics | No cost data for ROI calculations


## Power BI Dashboard:
**Note:** Due to dataset size (15M+ rows exceeding Tableau Public's 10M limit), a Power BI dashboard was created.
1. [City Bike Project.pdf](https://github.com/user-attachments/files/21237785/City.Bike.Project.pdf)

**Dashboard Features:**
   • Monthly and hourly ride trends
   • Member vs casual usage comparison
   • Station-level heatmaps
   • Bike type preference analysis
**PDF Power BI Dashboard:**

--------------------------------------------------------
|  Category        | Tools / Skills                     |
|------------------|------------------------------------|
| Data Wrangling   | Python (pandas)                    |
| Visualization    | Tableau, Power BI                  |
| Analysis         | seaborn, matplotlib                |
| Time-Based Trends| Grouping by hour, day, and month   |
| User Segmentation| Members vs. casual riders          |
| Geo Insights     | Station-level analysis & mapping   |
---------------------------------------------------------

**Tableau Dashboard Pictures**
<img width="3160" height="1800" alt="Dashboard 1" src="https://github.com/user-attachments/assets/701dbe0e-4c20-49f9-a52b-5eb4d959fc28" />
<img width="3160" height="1800" alt="Dashboard 2" src="https://github.com/user-attachments/assets/97185d02-a8b9-4476-a1ed-f9c9f5e2e6b8" />


