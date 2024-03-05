# Bus-reservation-system-using-BST
This program is a simple implementation of a Bus Reservation System using a Binary Search Tree (BST) data structure. It allows users to view available buses, book tickets, cancel bookings, view bus seat status, and check reservation information.

Features:-
View Bus List: Display a list of available buses along with their destinations, charges, and departure times.
Book Tickets: Allow users to book tickets by choosing a bus and selecting seats.
Cancel Booking: Provide functionality to cancel a reservation by entering the reservation number.
Buses Seat Info: View the status of seats in a particular bus.
Reservation Info: Check reservation information by entering the reservation number and customer ID.

Code Structure:-
main(): Entry point of the program, displays the main menu and handles user input.
busLists(): Displays a list of available buses.
status(): Displays the status of bus seats.
reservationInfo(): Displays reservation information based on customer ID.
insert(): Inserts a node into the Binary Search Tree.
displaySeat(): Displays the status of seats in a bus.
cost(): Calculates the ticket cost based on the bus.
deleteNode(): Deletes a node from the Binary Search Tree.
cancel(): Cancels a booking.
isBooked(): Checks if a seat is already booked.

Note:-
1.The program uses a Binary Search Tree to manage and search reservations efficiently.
2.Seats are represented by a 2D array where 0 indicates an empty seat and 1 indicates a booked seat.
