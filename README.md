# Hotel-Booking-Analysis
Business Objective
The objective of this project is to perfrom an EDA on hotel booking dataset to gain some insights which will be helpful in understanding the patterns and trends in booking analysis, cancellation analysis, Revnue analysis, customer segmentation and competitive analysis. The valuable insights gained will be helpful in improving the operational efficiency, better finance management, increasing revnue, support data-driven decision-making and competitive positioning.
Dataset
There are 119390 rows and 32 columns in this dataset.
Variable descrition
hotel: Categorical - Resort hotel or city hotel.
is_canceled: ‘1’ for booking and ‘0’ not cancelled.
lead_time: Period between time of booking and checking in (considered in days here).
arrival_date_month: Arrival month
country: Country of origin. List of 158 countries.
days_in_waiting_list: Number of waiting days.
Deposit_type: Categorical - No-deposit, Non-Refund, Refundable.
Adr: Average Daily rate as defined by the average rental revenue earned for an occupied room per day.
Adults, Babies, Children: Number of adults, babies and children.
Assigned Room Type: Code for the type of room assigned to the booking.
Booking Changes: Number of changes/amendments made to the booking from the moment the booking was entered on the PMS until the moment of check-in or cancellation.
Distribution_channel: Booking distribution channel.
Is_repeated_guest’: Categorical- repeated guest(1) or not (0).
Company: ID of the company/entity that made the booking or responsible for paying the booking.
Customer Type: Categorical:
Contract – when the booking has an allotment or other type of contract associated to it
Group – when the booking is associated to a group;
Transient – when the bookings is not part of a group or contract, and is not associated to other transient booking;
Transient party – when the booking is transient to at least other transient booking.
Market_segment: Market segment designation.
Previous_cancellations: Number of previous bookings that were cancelled by the customer prior to the current booking.
Required_car_parking_spaces: Number of car parking spaces required by the customer.
Reservation_status:Categorical:
Cancelled – booking was cancelled by the customer.
Check Out – customer has checked in but already departed.
No Show – customer did not check in and did inform the hotel of the reason why.
Reservation_status_date: Date at which the last status was set. This variable can be used in conjunction with the Reservation Status to understand when was the booking canceled or when did the customer checked-out of the hotel.
Reserved_room_type: Code of room type reserved.
Types_of_special_requests: Number of special requests made by the customer (e.g. Twin bed or high floor)
Stays_in_weekend_nights, Stays_in_week_nights: Number of weekend nights and week nights the guest stayed or booked to stay at the hotel.
