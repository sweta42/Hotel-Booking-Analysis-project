# Hotel-Booking-Analysis-project
## Overview <br>
Analysing the data of Hotel Booking

This data set contains booking information for a city hotel and a resort hotel, and includes information such as when the booking was made, length of stay, the number of adults, children, and/or babies, and the number of available parking spaces, among other things. All personally identifying information has been removed from the data.

We will perform exploratory data analysis with python to get insight from the data.

## Table of Content:
- [Motivation](https://github.com/sweta42/Hotel-Booking-Analysis-project?tab=readme-ov-file#motivation)
- [Tools and Libraries Used](https://github.com/sweta42/Hotel-Booking-Analysis-project?tab=readme-ov-file#tools-and-libraries-used)
- Uses
- [Files](https://github.com/sweta42/Hotel-Booking-Analysis-project?tab=readme-ov-file#file)
- Result

## Motivation
### 1.e have tried to answer the following Questions
1.How Many Booking Were Cancelled?
2.What is the booking ratio between Resort Hotel and City Hotel?
3.What is the percentage of booking for each year?
4.Which is the most busy month for hotel?
5.From which country most guest come?
6.How Long People Stay in the hotel?
7.Which was the most booked accommodation type (Single, Couple, Family)?

## After that we made the predictive model to predict whether the booking will be cancelled or not
### We will::
 - Perform the Feature Engineering to make new featuers
 - Perform the Data Selection to select only relevant features
 - Visualize the data with the help of charts and graphs
 - Finally came with few insights by analyzing them 

## Tools and Libraries Used
We have used Python 3 to its following packages:

 - Pandas
 - Matplotlib
 - Seaborn
 - Sklearn

## Usage
1.Clone the repository to your local machine.<br>
2.Run the provided Python scripts to perform hotel boooking data analysis. <br>
3.Explore the generated CSV file containing the results. <br>
Feel free to contribute, report issues, or suggest improvements! <br>

## File

This repository contains two files other than readme file

**Hotel Booking.ipynb:** Jupyter Notebook file contains all the python code, documentation and visualization
**hotel_bookings.csv:** Our dataset file

#### Dataset contains following features:

1.hotel
2.is_canceled
3.lead_time
4.arrival_date_year
5.arrival_date_month
6.arrival_date_week_number
7.arrival_date_day_of_month
8.stays_in_weekend_nights
9.stays_in_week_nights
10.adults
11.children
12.babies
13.meal
14.country
15.market_segment
16.distribution_channel
17.is_repeated_guest
18.previous_cancellations
19.previous_bookings_not_canceled
20.reserved_room_type
21.assigned_room_type
22.booking_changes
23.deposit_type
24.agent
25.company
26.days_in_waiting_list
27.customer_type
28.adr
29.required_car_parking_spaces
30.total_of_special_requests
31.reservation_status
32.reservation_status_date

## Result
We learned that

1.Almost 35% of bookings were canceled.
2.More than 60% of the population booked the City hotel.
3.More than double bookings were made in 2016, compared to the previous year. But the bookings decreased by almost 15% next year.
4.Most bookings were made from July to August. And the least bookings were made at the start and end of the year.
5.Portugal, the UK, and France, Spain and Germany are the top countries from most guests come, more than 80% come from these 5 countries.
6.Most people stay for one, two, or three. -> For Resort hotel, the most popular stay duration is three, two, one, and four days respectively. -> For City hotel, most popular stay duration is one, two, seven(week), and three respectively
7.Couple (or 2 adults) is the most popular accommodation type. So hotels can make arrangement plans accordingly
