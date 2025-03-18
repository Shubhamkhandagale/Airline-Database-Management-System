# Airline-Database-Management-System

airline database project. I’ll cover the tables, relationships, and any notable features. Let’s dive in!

🚦 1. Database Name: air_itv
🛫 2. Tables Overview:
airline

Airline_id (Primary Key)
Airline_name
aircraft

aircraft_id (Primary Key)
aircraft_name
Airline_id (Foreign Key → airline)
Flight_no (Foreign Key → flight)
flight

Flight_no (Primary Key)
Source
Destination
Departure_time
Arrival_time
aircraft_employee

Employee_id (Primary Key)
Employee_name
Position
aircraft_id (Foreign Key → aircraft)
passenger

Passenger_id (Primary Key)
Passenger_name
Flight_no (Foreign Key → flight)
ticket

Ticket_id (Primary Key)
Passenger_id (Foreign Key → passenger)
Flight_no (Foreign Key → flight)
Seat_number
🔗 3. Relationships:
One Airline → Operates Multiple Aircrafts.
One Aircraft → Assigned to One Flight.
One Flight → Carries Multiple Passengers.
One Passenger → Has One Ticket.
One Aircraft → Managed by Multiple Employees.
📊 4. Sample Data:
Airlines include Air India and IndiGo.
Aircrafts like Airbus A320neo and Boeing 787-8 Dreamliner.
Flight details between various cities.
⚙️ 5. Notable Queries:
Queries to track passenger counts per flight.
Queries to assign crew members to aircraft.
Queries to fetch flight details based on passenger names.
