# Airline Reservation System

## Overview

The Airline Reservation System is a simple console-based Java application designed to simulate the core functionalities of booking airline tickets. It allows users to view available flights, enter passenger details, and reserve seats for a specific flight. This project emphasizes object-oriented programming principles such as encapsulation, class design, and user interaction through a command-line interface.

## Features

- View list of available flights with flight number, destination, and remaining seats.
- Book a flight by providing passenger name, age, passport number, and flight number.
- Store and display booked passenger information for each flight.
- Seat availability management.

## Technologies Used

- **Java** – Core language for implementation.
- **OOP Concepts** – Encapsulation, class design (Passenger and Flight), and dynamic lists.
- **Console I/O** – Interaction through Java’s `Scanner` class.

## How It Works

- Flights are initialized at program startup using a predefined list.
- The user navigates through a simple menu to either list flights, book a flight, or exit.
- If the booking is successful (i.e., seats are available), passenger details are stored and seat count is updated.
- The system loops until the user chooses to exit.

## File Structure

- `AirlineReservationSystem.java` – Main file containing all the logic for flight initialization, user menu, booking, and class definitions.

## Getting Started

1. Compile the Java file:

   ```bash
   javac AirlineReservationSystem.java



## Future Improvements

- Add persistent data storage (e.g., using files or databases).
- Add flight search and cancellation options.
- GUI-based implementation using JavaFX or Swing.


