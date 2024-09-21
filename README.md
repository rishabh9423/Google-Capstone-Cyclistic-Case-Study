# Google-Capstone-Cyclistic-Case-Study

## Company Profile
In 2016, Cyclistic launched a successful bike-share offering. Since then, the program has grown to a fleet of 5,824 bicycles that are geotracked and locked into a network of 692 stations across Chicago. The bikes can be unlocked from one station and returned to any other station in the system anytime. 

Until now, Cyclistic’s marketing strategy relied on building general awareness and appealing to broad consumer segments. One approach that helped make these things possible was the flexibility of its pricing plans: single-ride passes, full-day passes, and annual memberships. Customers who purchase single-ride or full-day passes are referred to as casual riders. Customers who purchase annual memberships are Cyclistic members.


## Case
Cyclistic’s finance analysts have concluded that annual members are much more profitable than casual riders. Although the pricing flexibility helps Cyclistic attract more customers, Moreno believes that maximizing the number of annual members will be key to future growth. Rather than creating a marketing campaign that targets all-new customers, Moreno believes there is a solid opportunity to convert casual riders into members. She notes that casual riders are already aware of the Cyclistic program and have chosen Cyclistic for their mobility needs.

**Moreno wants to know:**

**1. How do annual members and casual riders use Cyclistic bikes differently?**

**2. How can we convert casual riders into annual members?**


## Dataset
Dataset included the following columns:
1. ride_id: A unique ID is generated for each ride.
2. rideable_type: Type of ride used. (This particular dataset included only docked_bikes)
3. started_at: Date and time that the ride started at.
4. ended_at: Date and time that the ride ended at.
5. start_station_name: Name of the station where the ride was initiated.
6. start_station_id: Unique ID of the station where the ride was initiated.
7. end_station_name: Name of the station where the ride ended.
8. end_station_id: Unique ID of the station where the ride was initiated.
9. member_casual: Type of rider.

### Dataset before creating the variables.
![Screenshot 2024-09-21 135740](https://github.com/user-attachments/assets/87f7a3ad-bb85-4446-8fbd-b9866f906d31)

## Analysis
1. Created a new variable, "**duration**," to calculate the duration of each ride by subtracting the start and end times.
2. Created a new variable, "**weekday**," to analyze ride behaviour by day.
3. To understand the distribution of rider types, I calculated the **percentage of total rides** for members and casual riders. A pie chart was created to visually represent this breakdown.

### Dataset after creating the above mentioned variables
4. ![Screenshot 2024-09-21 135604](https://github.com/user-attachments/assets/8c263e77-098f-4448-96eb-b8ba550bd272)

5. To compare the ride durations of members and casual riders, I calculated the average duration for each group and visualized the difference using a bar chart.
6. Used a pivot table to:
     a. Analyze ride counts by day of the week and rider type.
     b. Examine average ride durations by day of the week and rider type.
7. Pie chart visualizing the distribution of members and casual riders.
   
   ![Screenshot 2024-09-21 140242](https://github.com/user-attachments/assets/1273a500-5536-4ed9-a80d-1422513b9ea3)
9. Bar chart visualizing the average ride duration of members and casual riders.
    
    ![Screenshot 2024-09-21 140311](https://github.com/user-attachments/assets/f4234a1b-8eee-4307-bf40-6409a0fba66c)
11. Bar chart visualizing the average ride duration of members and casual riders by day of the week.
    
    ![Screenshot 2024-09-21 140355](https://github.com/user-attachments/assets/61bf906c-f37e-48d8-968f-98635cc30f1a)
13. Bar chart visualizing the number of rides of members and casual riders by day of the week.
    ![Screenshot 2024-09-21 140426](https://github.com/user-attachments/assets/09e92d75-37f9-48e8-bc3c-b36194a7fa09)





## Findings
1. Majority of riders are **members**.
2. **72.1%** riders are annual members
3. While **27.9%** of riders are casual riders who do **not** own an annual subscription.
4. **Weekends** see a surge in both casual and member riders.
5. **Sundays** have the **highest** number of riders.
6. Casual riders have an average ride duration of **73.07 minutes**, while members have an average of **21.47 minutes**.
7. This indicates that casual riders typically use bikes for approximately **3.4 times** longer than members.
8. Casual riders use bikes **longer than members** throughout the week.
9. However, this difference peaks on **Fridays**, which note the **highest average duration** of casual rides.


## Conclusion:
1. Although members use bikes more often than casual riders, casual riders tend to use it longer than the members.
2. Casual riders exhibit the longest average ride durations on Fridays compared to any other weekday.
3. Weekends consistently see the highest number of rides for both members and casual riders, with Sunday being the peak day.
4. Members exhibit consistent bike usage throughout the workweek, suggesting regular commuting patterns.


## Recommendations
1. Introducing **day passes** and **monthly subscription plans** can encourage casual riders to use the services without committing to a long-term membership. This could lead to increased familiarity and a higher likelihood of purchasing an annual plan.
2. Provide **exclusive member perks** such as priority access to bikes which will encourage casual riders to buy a subscription plan.
3. Offering **weekday discount plans** which will attract more casual riders to use the service during off-peak hours. Since weekends see the highest number of casual riders, targeting them during these times can be particularly effective.
4. Introducing **referral programs** which will encourage members to refer friends and family, providing incentives for both the referrer and the new member.

