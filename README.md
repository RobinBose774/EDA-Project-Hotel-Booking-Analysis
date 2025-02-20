# EDA-Project-Hotel-Booking-Analysis
![--](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)
**AlmaBetter Verified Project** - [**Credentials**](https://certificates.almabetter.com/en/verify/08074312957644)
![--](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

## Obective:
I have Hotel Booking dataset.The main objective of this project is explore the given dataset and find useful conclusion about general trends in hotel booking and discover how these factors affect on hospitality business.
## Dataset:
The given dataset have information of city and resort hotel. This dataset have 119390 rows and 32 columns. The columns from the dataset is as follows:

- hotel: Name of hotel ( City or Resort)
- is_canceled: Whether the booking is canceled or not (0 for no canceled and 1 for canceled)
- lead_time: time (in days) between booking transaction and actual arrival.
- arrival_date_year: Year of arrival
- arrival_date_month: month of arrival
- arrival_date_week_number: week number of arrival date.
- arrival_date_day_of_month: Day of month of arrival date
- stays_in_weekend_nights: No. of weekend nights spent in a hotel
- stays_in_week_nights: No. of weeknights spent in a hotel
- adults: No. of adults in single booking record.
- children: No. of children in single booking record.
- babies: No. of babies in single booking record. 
- meal: Type of meal chosen 
- country: Country of origin of customers (as mentioned by them)
- market_segment: What segment via booking was made and for what purpose.
- distribution_channel: Via which medium booking was made.
- is_repeated_guest: Whether the customer has made any booking before(0 for No and 1 for 
                     Yes)
- previous_cancellations: No. of previous canceled bookings.
- previous_bookings_not_canceled: No. of previous non-canceled bookings.
- reserved_room_type: Room type reserved by a customer.
- assigned_room_type: Room type assigned to the customer.
- booking_changes: No. of booking changes done by customers
- deposit_type: Type of deposit at the time of making a booking (No deposit/ Refundable/ No refund)
- agent: Id of agent for booking
- company: Id of the company making a booking
- days_in_waiting_list: No. of days on waiting list.
- customer_type: Type of customer(Transient, Group, etc.)
- adr: Average Daily rate.
- required_car_parking_spaces: No. of car parking asked in booking
- total_of_special_requests: total no. of special request.
- reservation_status: Whether a customer has checked out or canceled,or not showed 
- reservation_status_date: Date of making reservation status.

## Data cleaning and manipulation:
## **Duplicate values**
Dataset have 31994 duplicate values. so these duplicate values are removedfrom dataset using.drop_dupliactes(). After droping duplicate value shape of the dataset become 87396 rows and 32 columns.
## **Missing values/null values**
Given dataset have 4 columns company, aent, country and children missing values so these values are replace by usin .fillna() function.
## **Adittion of new columns**
Total_people and Total_stay these two columns are added in given dataset
Some rows are removed from columns adults, children and babies.
## EDA:
The EDA is done by using 3 analysis Univariate, Bivariate and Multivariate analysis. For the datavisualization following charts are used:

Pie chart

Barplot

Countplot

Heatmap

Pairplot

### Univariate analysis:
**In univariate analysis following questions are tried to solve:**
1) Which type of hotel is mostly prefered by the guests?
2) Which agent made the most bookings?
3) What is the percentage of repeated guests?
4) What is the most preferred room type by the customers?
5) What type of food is mostly prefered by the guests?
6) In which month most of the bookings happened?
7) Which distribution channel is mostly used for hotel booking?
8) which year had highest bookings?
     
## Conclusion:
1) City hotel has more bookings.
2) Agent no. 9 made most of the bookings.
3) There are very few guests booking for the same hotel again.
4) A type rooms are most prefered rooms.
5) BB type food is most preferred food.
6) August month has maximum number of bookings.
7) Mostly used distribution channel is TA/TO channel.
8) 2016 has highest bookings.
### Bivariate and Multivariate analysis:
**In bivariate and multivariate analysis following questions are tried to solve:**
1) Which hotel type has the highest ADR?
2) which hotel has longer waiting time?
3) Which distribution channel contributed more to adr in order to increase the income?
4) What is optimal stay length in both types of hotel?
5) Relationship between the repeated guests and previous bookings not canceled?
6) Relationship between ADR and total number of people?

## Conclusion:
1) City hotel has highest adr.
2) City hotel has longer waiting time.
3) GDS distribution channel contributed more to ADR in city hotel.
4) Optimal stay length in both hotel type is less than 7 days.
5) Repeated guests do not cancel there bookings.
6) Number of people increases adr also going to increase.

### Conclusion from correlation heatmap
1) arrival_date_year and arrival_date_week_number columns has negative correlation which is -0.51.
2) stays_in_week_nights and total_stay has positive correlation which is 0.95.

## Overall conclusion:
1) City hotel has almost 66.45% bookings and resort hotel has 33.55% bookings.
2) Agent no. 9 made most bookins and those bookings are 31961.
3) Percentage of repeated guest is just 4%.
4) Room type A is most preferred room type 46283 guests preferred A room type.
5) BB type food is most preferred food type and 67907 preferred this food.
6) Auust month has maximum number of bookings and those bookings are 11242.
7) TA/TO distribution channel is mostly prefderred channel and the bookings are 69141.
8) 2016 year has 42313 bookings.
9) City hotel has highest ADR and trhe average ADR is 111.27.
10) City hotel has longer waiting time means city hotel is busy hotel type.
11) GDS contribution channel contributed more to ADR in order to incerease income in city hotel.
12) Optimal stay length in both hotel type is leaa than 7 days.
13) Repeated do not cancel there bookings.
14) The number of people increases ADR increases.
15) arrival_date_year and arrival_date_week_number columns has negative correlation which is -0.51.
16) stays_in_week_nights and total_stay has positive correlation which is 0.95.
