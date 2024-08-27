# Hospitality-Analysis

**Overview:**

The dataset comprises five CSV files that contain metadata and detailed information across various dimensions and facts related to hotel bookings. These files are:

1.dim_date
2.dim_hotels
3.dim_rooms
4.fact_aggregated_bookings
5.fact_bookings

**Column Descriptions:**

**dim_date:**
1.**date:** Represents the individual dates spanning May, June, and July.
2.**mmm yy:** Displays the date in the format "mmm yy" (e.g., May 24).
3.**week no:** A unique identifier for the week number corresponding to each date.
4.**day_type:** Indicates whether the day falls on a Weekend or a Weekday.

**dim_hotels:**

**1.property_id:** A unique identifier for each hotel.
**2.property_name:** The name of the hotel.
**3.category:** Defines the hotel’s class, such as Luxury or Business.
**4.city:** Specifies the location of the hotel.

**dim_rooms:**

**1.room_id:** Identifies the room type (e.g., RT1, RT2, RT3, RT4) within a hotel.
**2.room_class:** Classifies the room type into categories like Standard, Elite, Premium, or Presidential.

**fact_aggregated_bookings:**

**1.property_id:** Corresponds to the unique ID of each hotel.
**2.check_in_date:** Captures the check-in dates of customers.
**3.room_category:** Specifies the room type (e.g., RT1, RT2, RT3, RT4) in the hotel.
**4.successful_bookings:** Records the number of successful bookings for a specific room type at the hotel on the given date.
**5.capacity:** Represents the maximum number of rooms available for a specific room type at the hotel on that date.

**fact_bookings:**

**1.booking_id:** A unique identifier for each booking made by customers.
**2.property_id:** Represents the unique ID for each hotel.
**3.booking_date:** Indicates the date when the customer made the booking.
**4.check_in_date:** The date when the customer checks into the hotel.
**5.check_out_date:** The date when the customer checks out of the hotel.
**6.no_guests:** The number of guests staying in a specific room within the hotel.
**7.room_category:** Specifies the type of room booked (e.g., RT1, RT2, RT3, RT4).
**8.booking_platform:** Indicates the platform through which the booking was made.
**9.ratings_given:** The ratings provided by the customer for the hotel's services.
**10.booking_status:** Describes the final status of the booking, whether Cancelled, Checked Out, or No Show.
**11.revenue_generated:** The total revenue generated from the booking.
**12.revenue_realized:** The final revenue earned by the hotel, taking into account the booking status. If the booking is Cancelled, 40% of the generated revenue is deducted, and the remaining amount is refunded to the customer. For Checked Out or No Show statuses, the entire revenue is retained by the hotel.



