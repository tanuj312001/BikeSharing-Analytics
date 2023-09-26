# BikeSharing-Analytics

Feel free to check the python notebook for detailed analysis . Here , I talk about 2 major things

- 3 metrics to be tracked
-  Source and Sink problem ( issue where common to bike sharing program where imbalance in the frequency with which bikes are picked up versus dropped )


![bicle](https://github.com/tanuj312001/BikeSharing-Analytics/assets/60888384/a2bedf55-ba28-49b6-91da-6433a4741566)

- First things first  , what data do we have?

This dataset (`data.csv`) comes from a Washington DC bike-sharing program. Each row in the bikeshare table represents a single ride within a 3-month period in 2012. Some of the columns are-

![sq](https://github.com/tanuj312001/BikeSharing-Analytics/assets/60888384/f2ba0314-e80d-40fc-aae8-a0c126500317)


- duration seconds: duration of the ride (in seconds)
- start time, end time: datetimes representing the beginning and end of the ride
- start station, end station: name of the start and end stations for the ride
- bike number: unique identifier for the bike used for the ride
- rider-type: indicates whether user was a "registered member" (Annual Member or 30-Day Member) or a "casual rider" (Single Trip or 24-Hour/3-Day/5-Day Pass)

### As a PM , I would want to track these three metrics

### 1. **User Acquisition / Conversion Rate:**

![download](https://github.com/tanuj312001/BikeSharing-Analytics/assets/60888384/acce66ea-edf1-43a4-b32b-6a1003d146d9)


   - **Metric:**
     - **Ratio of Registered to Casual Users**
   - **Why it’s Important:**
     - Understanding the composition of the user base is crucial. A higher number of registered users typically indicates a more stable and predictable revenue stream, and it can signify higher user engagement and loyalty. This metric can also aid in tailoring marketing strategies to convert casual users to registered ones.
   - **Data Needed:**
     - User type (Registered/Casual) from the ride history table.
   - **Additional Consideration:**
     - Monitoring the conversion rate of casual users to registered users over time can provide insights into the effectiveness of strategies aimed at encouraging user commitment.
    

### 2. **Operational Efficiency and User Satisfaction:**
   - **Metric:**
     - **Bike Availability and Utilization Rate**
   - **Why it’s Important:**
     - Ensuring that bikes are adequately available and well-utilized is crucial for user satisfaction and operational efficiency. Analyzing availability and utilization can highlight areas for redistributing bikes and can inform maintenance scheduling to minimize downtime.
   - **Data Needed:**
     - Real-time bike availability data from each station.
     - Ride history data for calculating utilization rate.
   - **Additional Consideration:**
     - Gathering and analyzing customer feedback and satisfaction scores can provide qualitative insights into user experiences, unmet needs, and potential areas for service improvement.
    
     ### 3. **Financial Health and Sustainability:**
   - **Metric:**
     - **Monthly Revenue and Operating Cost**
   - **Why it’s Important:**
     - Assessing the revenue against the operating costs is foundational for understanding the financial sustainability of the program. It can reveal whether the program is operating at a profit or a loss and can inform adjustments to pricing or cost structures.
   - **Data Needed:**
     - Revenue data (potentially from user subscriptions and casual ride fees).
     - Operating cost data (including maintenance, redistribution, and overhead costs).
   - **Additional Consideration:**
     - Analyzing the Average Revenue per User (ARPU) and the Lifetime Value (LTV) of a customer can inform decisions regarding marketing spend, customer acquisition strategies, and customer retention efforts.



# Source and Sink Problem
- Let's look at the top source and top sinks in Washington DC

  ![source and sink](https://github.com/tanuj312001/BikeSharing-Analytics/assets/60888384/9163364f-10cd-44e4-9d93-35ce03013821)


