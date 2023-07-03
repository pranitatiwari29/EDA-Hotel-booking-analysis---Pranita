# Hotel-Booking-Analysis
## Business Objective
The objective of this project is to perfrom an EDA on hotel booking dataset to gain some insights which will be helpful in understanding the patterns and trends in booking analysis, cancellation analysis, Revnue analysis, customer segmentation and competitive analysis. The valuable insights gained will be helpful in improving the operational efficiency, better finance management, increasing revnue, support data-driven decision-making and competitive positioning.
## Dataset
There are 119390 rows and 32 columns in this dataset.
### Variable description
1. **hotel**: Categorical - Resort hotel or city hotel.
2. **is_canceled**: ‘1’ for booking and ‘0’  not cancelled.
3. **lead_time**: Period between time of booking and checking in (considered in days here).
4. **arrival_date_month**: Arrival month
5. **country**: Country of origin. List of 158 countries.
6. **days_in_waiting_list**: Number of waiting days.
7. **Deposit_type**: Categorical - No-deposit, Non-Refund, Refundable.
8. **Adr**: Average Daily rate as defined by the average rental revenue earned for an occupied room per day.
9. **Adults, Babies, Children**: Number of adults, babies and children.
10. **Assigned Room Type**: Code for the type of room assigned to the booking.
11. **Booking Changes**: Number of changes/amendments made to the booking from the moment the booking was entered on the PMS until the moment of check-in or cancellation.
12. **Distribution_channel**: Booking distribution channel.
13. **Is_repeated_guest’**: Categorical- repeated guest(1) or not (0).
14. **Company**: ID of the company/entity that made the booking or responsible for paying the booking.
15. **Customer Type**: Categorical:
- Contract – when the booking has an allotment or other type of contract
associated to it
- Group – when the booking is associated to a group;
- Transient – when the bookings is not part of a group or contract, and is not associated to other transient booking;
- Transient party – when the booking is transient to at least other transient booking.
16. **Market_segment**: Market segment designation.
17. **Previous_cancellations**: Number of previous bookings that were cancelled by the customer prior to the current booking.
18. **Required_car_parking_spaces**: Number of car parking spaces required by the customer.
19. **Reservation_status**:Categorical:
- Cancelled – booking was cancelled by the customer.
- Check Out – customer has checked in but already departed.
- No Show – customer did not check in and did inform the hotel of the reason why.
20. **Reservation_status_date**: Date at which the last status was set. This variable can be used in conjunction with the Reservation Status to understand when was the booking canceled or when did the customer checked-out of the hotel.
21. **Reserved_room_type**: Code of room type reserved.
22. **Types_of_special_requests**: Number of special requests made by the customer (e.g. Twin bed or high floor)
23. **Stays_in_weekend_nights**, **Stays_in_week_nights**: Number of weekend nights and week nights the guest stayed or booked to stay at the hotel.
  ## Problem statement
  Q1) Which agent makes the most no. of bookings?

 Q2) Which room type is in most demand and which room type generates the highest ADR?

 Q3) Which meal type is the most preferred meal for customers?

 Q4) What is the percentage of bookings in each hotel?

 Q5) Which is the most common channel for booking hotels?

 Q6) Which are the busiest months?

 Q7) From which country most of the guests are coming?

 Q8) How long do people stay at the hotels?

 Q9) Which hotel seems to make more revenue?

 Q10) Which hotel has a higher lead time?

 Q11) What is the preferred stay length in each hotel?

 Q12) Which hotel has a higher bookings cancellation rate?

 Q13) Which hotel has a high chance that its customer will return for another stay?

 Q14) Which channel is mostly used for the early booking of hotels?

 Q15) Which channel has a longer average waiting time?

 Q16) Which distribution channel brings better revenue-generating deals for hotels?

 Q17) Which significant distribution channel has the highest cancellation percentage?

 Q18) Does a longer waiting period or longer-lead time causes the cancellation of bookings?

 Q19) Whether not getting allotted the same room type as demand the main cause of cancellation for bookings?

 Q20) Does not allowing the same room as demanded to affect ADR?