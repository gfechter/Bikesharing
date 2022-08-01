# Bikesharing

## Project Overview 
There is interest in potentially starting a bike-share program, similar to Citi Bike in Des Moines. To determine if the program would work well in Des Moines, an analysis was conducted using Citi Bike data to determine trends and how the program works. After the initial analysis was completed, additional analysis was requested to convince investors to invest in this program. Tableau was used to analyze the data. 

[Tableau Story](https://public.tableau.com/views/NYCitibikeChallenge_16593243842350/NYCitibikeChallenge?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)

## Resources
- Data: 
  - Citibike Data: https://ride.citibikenyc.com/system-data (Data from August 2019 was used)
- Tableau, Python 


## Results

### Deliverable 1 - Change Trip Duration to a Datetime Format

Python and Pandas were used to convert the "tripduration" column from an integer to a DateTime datatype. This allowed the data to be shown in hours, minutes, and seconds. This was necessary to create visualizations that show how many trips are taken out by the hour and for how many minutes. After the "tripduration" column was converted, the DataFrame was converted to a CSV file. 

<img width="1196" alt="Screen Shot 2022-07-31 at 10 45 38 PM" src="https://user-images.githubusercontent.com/103774401/182072563-b4f36999-830c-49eb-b459-773365e2b8ac.png">

### Deliverable 2 - Create Visualization for the Trip Analysis
The majority of trips begin in Manhattan - primarily below 59th Street. The majority of trips end in Manhattan - primarily below 59th Street. Brooklyn follows Manhattan with the second highest Citi Bike usage, Queens has the third highest usage, The Bronx has the second to lowest usage, and Staten Island has the lowest usage. 

Top Starting Locations

<img width="971" alt="Screen Shot 2022-07-31 at 11 24 05 PM" src="https://user-images.githubusercontent.com/103774401/182072535-b9561251-8237-40cf-9687-d71bffd0a925.png">

Top Ending Locations 

<img width="982" alt="Screen Shot 2022-07-31 at 11 24 23 PM" src="https://user-images.githubusercontent.com/103774401/182072551-3a76b199-744b-442d-9d90-836f170fccc3.png">

When looking at usage, Citi Bike usage is heavy during the mornings and evenings during the week. On the weekends, Citi Bike usage is fairly high throughout the day. This seems to show that people often use Citi Bike to get to and from work. One thing to mention - that is shown in the second visualization below - is that even though there is a range of usage times, short rides are far more common than longer rides. This seems to indicate that if people are using Citi Bikes to get to and from work, it is not a long ride to and from their office. 

Citi Bike Trips by Weekday Per Hour

<img width="826" alt="Screen Shot 2022-07-31 at 2 05 55 PM" src="https://user-images.githubusercontent.com/103774401/182072579-77584634-20c0-4fa0-a561-da2f867188ed.png">

Checkout Times by Users

<img width="999" alt="Screen Shot 2022-07-31 at 10 01 00 PM" src="https://user-images.githubusercontent.com/103774401/182072605-104bf99c-2fb2-4b1c-bdec-bd01116f49b6.png">

When breaking down trends by gender, it is apparent that men use Citi Bikes more often than women. Men tend to be subscribers of Citi Bike more often than women. As mentioned previously, short rides are far more common than long rides. Men took 108,087 rides that lasted five minutes whereas women took 34,151 rides that lasted six minutes. This indicates that women tend to take slightly longer rides than men. Finally, as is noted above, Citi Bike usage is high during the mornings and evenings, especially for men. This seems to indicate that out of men who use Citi Bike, a large portion of them use Citi Bike to get to and from work. 

Customer v. Subscriber Trips per Weekday by Gender

<img width="1000" alt="Screen Shot 2022-07-31 at 2 42 12 PM" src="https://user-images.githubusercontent.com/103774401/182072664-c06b4460-8ca1-447c-824f-98da8ea6dde0.png">

Trips by Gender (Weekday Per Hour)

<img width="1099" alt="Screen Shot 2022-07-31 at 2 37 36 PM" src="https://user-images.githubusercontent.com/103774401/182072689-5f11342c-c721-46b2-a5a6-9c1dc49b7a43.png">

Checkout Times by User (Gender)

<img width="1020" alt="Screen Shot 2022-07-31 at 1 46 37 PM" src="https://user-images.githubusercontent.com/103774401/182072711-d1146397-fdf3-49f9-bb10-ae736befa605.png">

### Deliverable 3 - Create a Story and Report for the Final Presentation
[Tableau Story](https://public.tableau.com/views/NYCitibikeChallenge_16593243842350/NYCitibikeChallenge?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)

## Summary
Citi Bike is an extremely popular program. Many individuals use Citi Bike primarily in the mornings and evenings during the week and throughout the weekend. The most common checkout time for the bike is about five minutes, which means the bikes are primarily used for short distances. A program similar to Citi Bike could potentially work in Des Moines. However, some additional visualizations, as described below, would need to be done before deciding if it is a smart move to start a bike share program in Des Moines. One thing to note is that a pilot program would be best before fully implementing a program exactly like Citi Bike's.

Two additional visualizations would be beneficial. One would be to determine the number of Citi Bike stations in each borough. It is entirely possible that people who do not live in Manhattan would like to use Citi Bike more often but cannot do so because there are not enough stations. If there are not enough stations, the next questions become why and if there were more stations in those boroughs, would more people use Citi Bike in those boroughs? A second visualization that would be useful would be to determine if individuals starting a Citi Bike ride in an outer borough are riding to Manhattan or if they are staying within the borough they picked it up in. The answer could lead to a determination if having a bike share would be only useful in downtown Des Moines or if spreading it throughout all neighborhoods of Des Moines would be more beneficial.
