# Car Rental System

A Java-based Car Rental System that allows customers to rent and return cars through a console interface. It manages cars, customers, and rentals, providing an interactive menu for renting, returning, and viewing available cars.

## Features
- **Car Management**: Manage car availability and calculate rental prices based on days.
- **Customer Management**: Add customers and track rental history.
- **Rental Process**: Rent available cars for a specified number of days.
- **Return Process**: Return rented cars and update availability.

## Program Structure

The program consists of multiple classes:
1. **Car**: Represents a car with attributes like ID, brand, model, daily rental price, and availability status.
2. **Customer**: Represents a customer with a unique ID and name.
3. **Rental**: Represents a rental with the rented car, customer, and rental duration.
4. **CarRentalSystem**: Manages cars, customers, rentals, and provides a menu-driven interface.
5. **Main**: Entry point to initialize the system and start the menu.

### Class Breakdown

- **Car**:
  - Stores car details and calculates the rental price based on rental days.
  - Manages rental status with methods to rent and return the car.

- **Customer**:
  - Stores customer details including a unique ID and name.

- **Rental**:
  - Stores details about a specific rental transaction, including the car, customer, and rental duration.

- **CarRentalSystem**:
  - Stores and manages lists of cars, customers, and rentals.
  - Handles car renting and returning, and provides an interactive menu for user operations.

### Main Program Flow

1. **Start the Program**:
   - Initializes a set of cars and starts the interactive menu.

2. **Menu Options**:
   - **Rent a Car**: Allows users to choose an available car, specify rental days, and view the total price.
   - **Return a Car**: Allows users to return a rented car by entering the car's ID.
   - **Exit**: Ends the program.

3. **Example Walkthrough**:
   - **Rent a Car**:
     ```plaintext
     ===== Car Rental System =====
     1. Rent a Car
     2. Return a Car
     3. Exit
     Enter your choice: 1
     
     == Rent a Car ==
     Enter your name: John Doe
     
     Available Cars:
     C001 - Toyota Camry
     C002 - Honda Accord
     C003 - Mahindra Thar
     
     Enter the car ID you want to rent: C001
     Enter the number of days for rental: 3
     
     == Rental Information ==
     Customer ID: CUS1
     Customer Name: John Doe
     Car: Toyota Camry
     Rental Days: 3
     Total Price: $180.00
     
     Confirm rental (Y/N): Y
     
     Car rented successfully.
     ```

   - **Return a Car**:
     ```plaintext
     ===== Car Rental System =====
     1. Rent a Car
     2. Return a Car
     3. Exit
     Enter your choice: 2
     
     == Return a Car ==
     Enter the car ID you want to return: C001
     
     Car returned successfully by John Doe.
     ```

## Getting Started

### Prerequisites
- **Java**: Ensure Java is installed on your system.

### Running the Program
1. Compile the program:
 ```bash
   javac Main.java
```

2. Run the program:
 ```bash
java CarRentalSystem.Main
```

## Folder Structure
- CarRentalSystem: Package containing the classes Car, Customer, Rental, CarRentalSystem, and Main.
- Main.java: Entry point to initialize the system and start the program
