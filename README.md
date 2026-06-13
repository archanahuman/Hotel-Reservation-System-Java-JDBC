# Hotel Reservation System

A console-based Hotel Reservation System developed using Java, JDBC, and MySQL.

## Features

- Reserve a room
- View reservations
- Get room number by reservation ID and guest name
- Update reservation details
- Delete reservations

## Technologies Used

- Java
- JDBC
- MySQL

## Database Schema

### Table: reservations

| Column | Type |
|----------|------|
| reservation_id | INT (Primary Key) |
| guest_name | VARCHAR(100) |
| room_number | INT |
| contact_number | VARCHAR(20) |
| reservation_date | TIMESTAMP |

## How to Run

1. Clone the repository.
2. Create the database using `hotel_db.sql`.
3. Update database credentials in `HotelReservationSystem.java`.
4. Add MySQL Connector JAR.
5. Run the program.

## Project Structure
