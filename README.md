# The-Flight-Booking-System

A seat reservation system for small airline company (Virgin Airline) to carry out seat reservation for its flights.

The program is menu driven with the following options:
1 Display available flights
2 View flight
3 Seat availability
4 Seat booking
5 Exit

Option One (1)
The program lists all flight numbers that have at least one seat available. The screen display shows the flight number, departure date and time, departure airport code, arrival airport code and the number of seats available with their class.

Option two (2)
The program prompts the user for a flight number. The program then searches the database for the requested flight. An appropriate error message appears if the flight is not present. If the flight is found then the display shows all available seat numbers together with their class, the total number of available seats in each class, the departure and arrival airports, the departure date and time.

Option three (3)
The program prompts the user for a flight number. It then requests the number of seats required by the customer. Then the program searches the flight to see if that number of seats is available. If they are then a message giving the seat numbers available appears on screen. If not an appropriate error message will be given.

Option four (4)
The program prompts for a flight number and seat location in order to make a booking. Seats are numbered by rows 1..60 and A..F in each row. If the seat is available, it is allocated and does not show as available any more. If a non-available seat is requested an error message will appear.

Option four (5)
Upon exit the modified data will be written to the same file (called flights.dat) in the same format as originally.

The format of the file is:

blank line separates flights
// Flight number e.g. VA502
// Date and time
// 20 char for departure airport
// 20 char for arrival airport
// Row number, class, seats A..F if available

