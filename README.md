# TAL
 TAL coding test
 
Data file: The data file is saved as \Data\RoomBooking.txt. Please update the hardcoded file path in DBIO_Booking.vb before running the application.

Area of improvements as below
1. Database tables should be used to save the data instead of using file input/output
2. I would create couple more tables to make this application more like a real-life app. 
   [Table Room] (RoomID, Room Description)
   [Table TimeSlotDefinition] (TimeSlotID, Time Slot Description). For example (sl1, 9:00AM to 9:30AM | sl2, 9:30AM to 10AM ...)
   [Table Booking] (RoomID, Date, TimeSlotID, Status)
   So that it supports multiple room bookings on any day.
3. There is definitely room for improvement on UI. Maybe a grid to show the slots is more user friendly and also a message should be displayed once the booking is made sucessfully.
