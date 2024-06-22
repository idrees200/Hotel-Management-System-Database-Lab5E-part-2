# Hotel Management System Database (Lab5E)

This project involves setting up a hotel management system database (`lab5E`) with tables for hotels, rooms, guests, and bookings. The SQL script includes table creation, data insertion, and various queries to manage and retrieve data effectively.

## Database Structure

### Tables

1. **Hotel**
   - Attributes: `hotelno` (Primary Key), `hotelname`, `city`
   - Stores information about different hotels.

2. **Room**
   - Attributes: `roomno`, `hotelno` (Foreign Key), `type`, `price`
   - Represents various rooms available in different hotels.

3. **Guest**
   - Attributes: `guestno` (Primary Key), `guestname`, `guestaddress`
   - Contains details about the guests staying at the hotels.

4. **Booking**
   - Attributes: `hotelno` (Foreign Key), `guestno` (Foreign Key), `datefrom`, `dateto`, `roomno`
   - Records the bookings made by guests for specific rooms and dates.

## Key Operations

1. **Data Insertion**
   - Populating tables with initial data for hotels, rooms, guests, and bookings.

2. **Table Alterations**
   - Adding primary keys, foreign key constraints, and ensuring data integrity.

3. **Data Retrieval**
   - Executing queries to fetch specific information based on various conditions.

4. **Data Analysis**
   - Performing aggregations, comparisons, and joining tables to derive insights.

## Sample Queries

- Retrieve all bookings stored in the database.
- Fetch details of all guests registered in the system.
- View information about all hotels available.
- Obtain a list of all rooms registered in the system.
- Retrieve guest names and addresses for guests located in London, sorted alphabetically.
- Count the number of rooms available in each hotel.
- Calculate the average room price for hotels located in London.
- Identify the room number and price for the most expensive single, double, and family rooms.
- Determine the count of available room types and their availability in each hotel.
- List hotels in London that have not been booked by any guest.
- Retrieve hotels along with the count of reservations made for each, sorted by the number of reservations in descending order.
- Find guest names for those currently checked in (i.e., `dateto` is `NULL`).
- Retrieve hotel names and room numbers for bookings made in the years 2001 and 2002.
- List hotels that have no bookings recorded.
- Retrieve hotel names, cities, and room numbers for family rooms using a right outer join.
- Count the total number of unique guests who stayed in the hotels until June 2015.

## How to Use

1. **Create Database and Tables**
   - Execute the provided SQL script to create the `lab5E` database and its corresponding tables.

2. **Insert Initial Data**
   - Insert sample data into the tables as demonstrated in the script.

3. **Execute Queries**
   - Run SQL queries to retrieve, update, or analyze data as required for hotel management tasks.

This setup provides a comprehensive database structure for managing hotel-related information efficiently. The queries included facilitate various operations such as booking management, guest tracking, and room availability analysis.
