<img src="https://github.com/lnshewmo/Bikesharing/blob/main/images/citibike_image.png" height="200" width="400" >

# NYC Citibikes
## Using Tableau to Create Visualizations

View the entire NYC Citibikes Story on Tableau Public **[here](https://public.tableau.com/views/CitiBike_Challenge_16616353157500/Story1?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)** for a more expanded explanation of the findings.

### Resources
 - **Data:** from the CitiBike System Data [page](https://s3.amazonaws.com/tripdata/index.html), the selected set is 201908-citibike-tripdata.csv.zip
 - Tableau Public 2022.2
 - Jupyter Notebook 6.4.8
 - Pandas library - trip duration data from the 201908-citibike-tripdata.csv file was converted to a *datetime* datatype **([here](https://github.com/lnshewmo/Bikesharing/blob/main/NYC_Citibike_Challenge.ipynb))** before uploading to Tableau.
  
## Overview

Visualizations using the NYC CitiBikes dataset were prepared for an investor meeting to demonstrate proof of concept for a similar bikesharing venture in Des Moines, Iowa.  The selected dataset represents the month of August (2019) which was determined to be an optimal month for bike rentals.

## Results

Total ridership for August:  2,344,224 total rides

----

Breakdown of subscribers vs. short-term customers:  The primary client type is male subscribers age 25-35
<img src="https://github.com/lnshewmo/Bikesharing/blob/main/images/user_gender.png" height="300" width="300">

----

Daily peak times for trips:  Usage patterns differ between weekdays and weekends. 

Weekdays: Peak times spike at 8a and 5p, typical commuter time periods

<img src="https://github.com/lnshewmo/Bikesharing/blob/main/images/peak_weekday_use.png" height="300" width="500">

Weekends: There is a more gradual mid-day build between 10a-7p with a steady peak from 12-5p

<img src="https://github.com/lnshewmo/Bikesharing/blob/main/images/peak_weekend_use.png" height="300" width="500">

-----

Trip duration for all riders and genders: The majority of trips are less than an hour in duration with a significant spike at 5-6min duration.

<img src="https://github.com/lnshewmo/Bikesharing/blob/main/images/users_checkout_time.png" height="300" width="600">

<img src="https://github.com/lnshewmo/Bikesharing/blob/main/images/checkout_time_by_gender.png" height="300" width="550">

-----

Number of trips taken by the hour for each day of the week for all riders:

<img src="https://github.com/lnshewmo/Bikesharing/blob/main/images/hourly_weekly.png" height="300" width="400">

This heatmap can be used to approximate the number of bikes needed to cover peak usages.

With breakout for gender:

<img src="https://github.com/lnshewmo/Bikesharing/blob/main/images/hourly_weekly_gender.png" height="300" width="700">

----

Days of the week is a user more likely to rent a bike:

<img src="https://github.com/lnshewmo/Bikesharing/blob/main/images/weekly_gender_user.png" height="300" width="350">

----

Individual bike usage (as measured by total hours in service and total number of trips)

<img src="https://github.com/lnshewmo/Bikesharing/blob/main/images/bikeID_subscriber.png" height="400" width="400"><img src="https://github.com/lnshewmo/Bikesharing/blob/main/images/bikeID_customer.png" height="400" width="400">

### Summary
<img src="https://github.com/lnshewmo/Bikesharing/blob/main/images/icon.png" height="20" width="20">  The client base is primarily male subscribers most likely making commuter trips during the week (8a and 5pm) with a typical commute time of 5-6 mins.  The non-subscriber customer base is most active in a more spreadout pattern across midday.
<img src="https://github.com/lnshewmo/Bikesharing/blob/main/images/icon.png" height="20" width="20">  Individual bikes requiring maintenance can be identified either by their total hours in service or number of trips made.  







 
 
- what are the highest-traffic starting locations?
- what are the highest-traffic ending locations?

