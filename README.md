### 数据集网址：
https://www.kaggle.com/jessemostipak/hotel-booking-demand

### 数据集描述
Features in the DataFrame:
hotel: Resort Hotel or City Hotel
is_canceled: Value indicating if the booking was canceled (1) or not (0)
lead_time: Number of days between the booking date to the arrival date
arrival_date_year: Year of arrival
arrival_date_month: Month of arrival
arrival_date_week_number: Week number according to year of arrival
arrival_date_day_of_month: Day of arrival
stays_in_weekend_nights: Number of weekend nights booked (Saturday or Sunday)
stays_in_week_nights: Number of week nights booked (Monday to Friday)
adults: Number of adults
children: Number of children
babies: Number of babies
meal: Type of meal booked
country: Country of origin
market_segment: Market segment designation, typically influences the price sensitivity
distribution_channel: Booking distribution channel, refers to how the booking was made
is_repeated_guest: Value indication if the booking was from a repeated guest (1) or not (0)
previous_cancellations: Number of previous cancellations prior to current booking
previous_bookings_not_canceled: Number of previous booking not canceled prior to current booking
reserved_room_type: Code of room type reserved
assigned_room_type: Code for the type of room assigned to the booking
booking_changes: Number of changes made to the booking since entering the hotel management system
deposit_type: Type of deposit made for the reservation
agent: ID of the travel agency that made the booking
company: ID of the company/organization that made the booking or is responsible for payment
days_in_waiting_list: Number of days booking was in the waiting list until it was confirmed
customer_type: Type of booking
adr: Average Daily Rate (the sum of transactions divided by the number of nights stayed)
required_car_parking_spaces: Number of car parking spaces requested
total_of_special_requests: Number of special requests made by the customer
reservation_status: Last reservation status (Canceled, Check-Out, No-Show)
reservation_status_date: Date at which the last status was set
### Objective
Predicting if a booking will be canceled.

Chosen Feature:
is_canceled column

0 means the booking was not canceled
1 means the booking was canceled

### Motive:
Like any business, hotels are also looking to gain profit. A model that predicts if the booking is likely to be canceled could be a good indication for hotels, as they may prefer to accept the lower risk bookings first.
