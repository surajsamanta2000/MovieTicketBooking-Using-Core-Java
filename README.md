# Movie Ticket Booking System 🎟️

A simple Java console-based application to simulate a movie theater ticket booking system. This project demonstrates object-oriented programming concepts and user interaction via the terminal.

## 📋 Features

- Book movie tickets by selecting a row and seat
- Prevent double-booking of seats
- Check the status of a booking using a booking ID
- Display current seating arrangement
- Simple and interactive CLI-based menu

## 🏗️ Project Structure

- `Theater`: Manages seating arrangements and bookings
- `FrontDesk`: Handles user interaction and delegates to the `Theater`
- `MovieTicketBookingSystem`: The main entry point with the app loop

## 🧪 How to Run

### Prerequisites
- Java installed (JDK 8 or later)
- A terminal/command line interface

### Steps
1. Clone the repository:
   ```bash
  https://github.com/surajsamanta2000/MovieTicketBooking-Using-Core-Java
   cd MovieTicketBooking-Using-Core-Java
2.Compile the code:
   javac com/sl/project/MovieTicketBookingSystem.java
3.Run the application:
  java com.sl.project.MovieTicketBookingSystem

💡 Example:

   Menu:
1. Book Ticket
2. Check Booking Status
3. Exit
Enter your choice: 1
Enter desired row number: 2
Enter desired seat number: 5
Enter booking ID: 101
Booking successful!
