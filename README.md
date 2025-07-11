# City Bike-Share User Behavior Analysis

![City Bike Rental Project-2](https://github.com/user-attachments/assets/781ceda3-b50a-4a4d-aec3-1b11499122c9)

**Overview:**
I analyzed 15,329,730 bike ride records across 21 columns using Google Drive for storage and Google Colab for Python-based data cleaning and analysis.
Due to the large dataset size, I focused on rides between December 31, 2024, and May 31, 2025 to ensure performance and depth of analysis.

This project focus on analyzing customer behavior. I looked at patterns across time, location, and user type.

**Raw Data**
https://s3.amazonaws.com/tripdata/index.html

**Key Questions:**
1. Which month had the most bike rides?
2. Which day of the week is the busiest for rides?
3. What time of day do most rides happen?
4. Do weekdays vs. weekends show different usage patterns?
5. How has usage changed over the year (month/seasonal trend)
6. What percentage of rides come from members vs. casual users?
7. Do members ride more consistently throughout the week than casual users?
8. What are the top 10 most used start stations?
9. Are there specific stations more popular with members vs. casual users?
10. What is the average trip duration by bike type?

**Tools Used:**
**Python:** pandas, seaborn, matplotlib
**Visualization:** Tableau, Power BI
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
**Key Findings:**
*Monthly Ride Trends*
May had the highest number of rides with 4.31 million, followed by April and March with 3.71 million and 3.15 million respectively. The lowest number of rides occurred in December, with only 182 rides, which makes sense given the cold winter weather. Warmer spring months like May likely encouraged more outdoor activity and bike usage.
*Which Days Are Busiest?*
Fridays had the highest overall ride volume, followed by Tuesdays and Thursdays. Interestingly, Saturday saw more rides than Monday, but Sunday had the lowest ride volume overall. This pattern reflects a mix of weekday commuting and weekend leisure usage.
*What Time of Day Do Most Rides Happen?*
As expected, the most popular time to ride is during evening commute hours, with 5 PM being the peak, followed closely by 6 PM and 4 PM. Morning usage peaks at 8 AM, showing a typical office commute pattern. This reinforces the idea that many riders are using City Bike services as part of their daily work routine — just like many retail shoppers follow predictable time-based traffic patterns.
*Weekday vs. Weekend Usage Patterns*
Weekdays saw significantly more ride activity than weekends. A closer look at hourly usage reveals a bimodal pattern on weekdays, with peaks at 8 AM and again around 5–6 PM. This pattern aligns with standard commute times.

In contrast, weekends show a unimodal distribution — rides gradually increase starting at 6 AM, peaking around 2–3 PM, and tapering off afterward. This suggests casual, recreational use that’s spread more evenly across the day.
*Seasonal Trends Over Time*
From December 2024 to May 2025, ride volume steadily increased. While January had a slight bump over December, usage dropped a bit in February before climbing again in March through May. This trend likely reflects improving weather conditions as spring approached. Casual users followed a similar pattern, but with lower overall usage.
*Member vs. Casual Breakdown*
Members made up 85% of total rides, while casual users accounted for 14% — a notable share. Casual usage showed more variability throughout the week, peaking around Friday and Saturday, then dropping off on Sunday. Members showed a more steady weekday pattern, with a slight dip on Fridays and weekends, possibly indicating remote work during Fridays.
*Top Start Stations*
The most-used station was West 21st St & 6th Ave, with just under 60,000 rides starting there. Other high-traffic stations included key Manhattan. These stations likely serve both commuters and tourists, making them valuable hotspots for resource allocation — just like high-performing retail locations.
*Trip Duration by Station and User Type*
Across the top 10 stations with the longest average trips, casual riders had consistently longer durations, ranging from 15 to over 35 minutes. Members averaged 12 to 15 minutes, even at the same stations. Stations near Central Park and Grand Army Plaza had the biggest gaps — likely due to casual riders using them for sightseeing. This mirrors retail behavior where loyal customers shop quickly and efficiently, while casual visitors browse longer.
*Bike Preferences and Duration*
The average trip duration was 12 minutes for classic bikes and 11 minutes for electric bikes — a small difference. However, both members and casual riders preferred electric bikes overall, especially during peak commute hours. This suggests a user preference for speed and convenience, much like consumers choosing faster or more premium retail experiences.

**Power BI Dashboard:** Due to my database containing 15,000,000 rows, which exceeds Tableau Public’s 10,000,000-row limit, I have shared a static image instead of an interactive dashboard.
<img width="3160" height="1800" alt="Dashboard 1" src="https://github.com/user-attachments/assets/cc819270-d70b-4c97-977a-813581c6254b" />
<img width="3160" height="1800" alt="Dashboard 2" src="https://github.com/user-attachments/assets/97185d02-a8b9-4476-a1ed-f9c9f5e2e6b8" />


