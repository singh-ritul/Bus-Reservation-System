# Bus Reservation System

This C program simulates a bus reservation system where users can view available seats, reserve seats, and cancel reservations.

## Features

- Initialize the bus with a specific number of seats.
- Display available seats.
- Reserve a seat.
- Cancel a reservation.

## How to Use

1. **Initialization:** Enter the bus number.
2. **Menu Options:**
   - **Display Available Seats:** Shows which seats are available.
   - **Reserve a Seat:** Allows you to reserve a specific seat.
   - **Cancel Reservation:** Cancels a previously reserved seat.
   - **Exit:** Terminates the program.

## Usage

Compile and run the program (`project.c`):
```bash
gcc project.c -o bus_reservation
./bus_reservation
```
> **Note:**Seat numbers start from 1 to the maximum number of seats defined (max_seats).
> Invalid seat numbers are handled gracefully with error messages.
