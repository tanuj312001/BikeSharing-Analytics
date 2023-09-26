# BikeSharing-Analytics

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
   - **Metric:**
     - **Ratio of Registered to Casual Users**
   - **Why it’s Important:**
     - Understanding the composition of the user base is crucial. A higher number of registered users typically indicates a more stable and predictable revenue stream, and it can signify higher user engagement and loyalty. This metric can also aid in tailoring marketing strategies to convert casual users to registered ones.
   - **Data Needed:**
     - User type (Registered/Casual) from the ride history table.
   - **Additional Consideration:**
     - Monitoring the conversion rate of casual users to registered users over time can provide insights into the effectiveness of strategies aimed at encouraging user commitment.
