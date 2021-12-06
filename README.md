# Hotel-Bookings
Hotel Booking Prediction Modeling and Strategy. 


# Problem Statment 
    Levarage Guest data and Booking Behaviour patterns to devise a strategy for Hotel Revenue Management using data science and machine learning 
    
    
# Summary
In hotels, many people books the rooms and then at the and they apply for ticket cancellation and refunds. The hotels give them a refund on the basis of the days before arrival. At last, the customer is satisfied to get the refund he got but the hotel usually bears a load of loss as the hotel has a 40% to 50% of the booking amount but the room is most likely going to be empty so it could have been booked for another guest if the cancellation was done before the deadline or as early as possible.

In this project i created a model to find the guests who are most likely going to cancel their hotel booking. I also find the target population on whom we should focus more and how to target them.

This project can help the hotels to boost their revenue as the hotel rooms can be given to another person if the cancelation is confirmed before some time and not at the last moments.


# Dataset
    This data set contains booking information for a city hotel and a resort hotel and includes information such as when the booking was made, length of stay, the number of adults, children, and/or babies, and the number of available parking spaces, among other things. This data set is from kaggel
    Dataset Features:
    hotel                          : Type of hotel example resort.
    is_canceled                    : Status of the ticket.
    lead_time                      : The time taken between when a customer makes a reservation and their actual arrival.
    arrival_month_year             : Month and year of arrival.
    arrival_date_year              : Date and year of arrival.
    arrival_date_month             : Date and month of arrival.
    arrival_date_week_number       : Date week no of arrival.
    arrival_date_day_of_month      : day of month of arrival.
    stays_in_weekend_nights        : Total days of stay on weekend nights.
    stays_in_week_nights           : Total days of stay on weeknights.
    adults                         : Total no of adults.
    children                       : Total no of children.
    babies                         : Total no of babies.
    meal                           : Type of meal taken (BB, BF). 
    country                        : Country from which guest arriving.
    is_repeated_guest              : Has the guest visited before(0, 1).
    previous_cancellations         : Has the guest had any cancellations before.
    reserved_room_type             : Type of room reserved(A, B, C, D...).
    assigned_room_type             : Type of room Assigned to guest (A, B, C ...).
    booking_changes                : Has the booking made changed in date or time.
    agent                          : Is the booking made through an agent.
    adr                            : Measure of the average rate paid per room. ADR(Average Daily Rate)
    required_car_parking_spaces    : Number of car parking spaces required by guest.
    total_of_special_requests      : Total no of special Requests.
    reservation_status             : Status of reservation.
    reservation_status_date        : date of reservation status.
    
    
        
# Recommendation

Based on the above data we can target the high ADE and Low Lead time guests first and the management can call them and get the status of the booking and get connected to them. Because as soon we got to know they are going to cancel their booking we can give the room to someone else
