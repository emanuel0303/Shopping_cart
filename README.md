# Shopping Cart Page

This is a simple shopping cart page implemented in Java using SQLite for database operations.

## Setup Instructions

1. Make sure you have Java installed on your system.
2. Ensure you have SQLite installed or have access to a SQLite database file.
3. Clone the repository to your local machine.

## Usage

1. Run the `CartServiceMain` class.
2. Follow the prompts to perform operations like adding items to the cart, removing items, or signing out the cart.

## Code Structure

- `CartServiceMain`: Contains the main method to run the application.
- `User`, `Product`, `Cart`: Classes representing entities in the application.
- `CartService`: Class responsible for interacting with the database and performing cart-related operations.

## Database Setup

No additional setup is required if you already have a SQLite database file. Otherwise, you can create a new database file and provide its path when instantiating `CartService`.

## Dependencies

This project uses only Java standard libraries and SQLite for database operations.
