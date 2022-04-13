# Citi Bike Analysis

## Project Overview
The client has asked to summarize various bike riding data to determine if a bike-sharing program is a worthwhile business pursuit in Des Moines. This includes:
- Show the length of time that bikes are checked out for all riders and genders
- Show the number of bike trips for all riders and genders for each hour of each day of the week
- Show the number of bike trips for each type of user and gender for each day of the week.

The client also wants all of this information displayed in a visual story via Tableau.

## Methodology
- Tools/Programs/Languages used:
    - Jupyter Notebook
    - Pandas library
    - Tableau
    - [Citi Bike Story](https://public.tableau.com/views/CitiBike_16498186540580/Story2?:language=en-US&:display_count=n&:origin=viz_share_link)

- I used the Pandas library to read the Citi Bike CSV and display it as a DataFrame. Then I changed the data type of the ```tripduration``` column so that the date and time would be displayed. I exported the new DataFrame as a CSV and loaded the new CSV in Tableau to create the story/visuals.  

## Citi Bike Analysis Results

<b>1. Checkout per Users</b>
  - This graph shows that users who ride the bikes for about 3-9 minutes have the highest check-out rates.
  - The longer the trip, the lower the number of users.
![Checkout per Users](https://user-images.githubusercontent.com/44425379/163218262-34a36f50-f8f0-4b6b-8644-a0f7a8f32611.png)

<b>2. Checkout per Gender</b>
  - This graph shows the number of users by gender.
  - The customer base seems to be predminately male.
![Checkout per Gender](https://user-images.githubusercontent.com/44425379/163218115-fbadc62b-a43a-40ad-86c8-6b490c28af3a.png)

<b>3. Trips by Weekday</b>
  - This graph shows the number of trips throughout the week by the hour.
  - Peak hours are from 7-9 AM and 5-7 PM.
  - Most likely people commuting to or from work. 
![Trips by Weekday](https://user-images.githubusercontent.com/44425379/163218603-b3830707-b12e-46bc-b100-84c52ddcd231.png)

<b>4. Trips by Gender</b> 
  - This graph shows the number of trips throughout the week by the hour per gender.
  - Peak hours are from 7-9 AM and 5-7 PM (normal working hours).
  - Males use the bikes more frequently than females. 
![Trips by Gender](https://user-images.githubusercontent.com/44425379/163218543-921d99a6-ab3c-4b3c-b2b9-81a309bf3546.png)

<b>5. Trips by Gender by Weekday</b>
  - This graph shows the number of trips throughout the week by gender, and by user type.
  - Males make up the bulk of the customer base, so they have the most subscriptions and are the most active. 
  - The most active days are Thursdays and Fridays.
![Trips by Gender by Weekday](https://user-images.githubusercontent.com/44425379/163218464-e29eab10-a03a-4996-96e6-95dd9fff27b2.png)

<b>6. Average Trip Duration</b> 
  - This graph shows the average trip duration by birth year.
  - The later the birth year, the longer the ride duration. 
![Average Trip Duration](https://user-images.githubusercontent.com/44425379/163217964-43fcbafd-1d8d-4b65-bab2-d4ff725dfb36.png)

<b>7. Top Starting Locations</b>
   - This graph shows the top starting locations.
   - There's a noticeable difference between people who use the bikes in the Manhattan/Lower Manhattan areas vs. the rest of New York. 
![Top Starting Locations](https://user-images.githubusercontent.com/44425379/163218350-8f32ed26-d414-48ff-adeb-6b27da674a73.png)

