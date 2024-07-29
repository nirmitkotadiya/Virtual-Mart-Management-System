# Virtual Mart Management System

## Introduction

A Virtual Mart Management System is a software application developed to enhance and streamline the operations within a virtual marketplace. It offers comprehensive management tools for handling products, orders, customers, and producers, ensuring efficient and effective marketplace administration.

## Key Features

### User Roles:
- **Admin**: Manages product requests, approves or rejects requests from producers.
- **Producer**: Submits product requests for approval.
- **Customer**: Views and buys products available in the mart.

### Functionality:
- **Product Management**: Adding, viewing, and deleting products.
- **Order Processing**: Facilitating product purchases by customers.
- **User Management**: Handling user registrations, logins, and access control.
- **Product Requests**: Producers can request to add new products, which admins approve or reject.
- **Billing and Invoicing**: Generates bills for customers after successful purchases.
- **Product Availability**: Displays current stock and availability of products.

## Technologies Used

- **Java**: Platform-independent programming language used for development.
- **Scanner**: For user input and interaction.
- **In-Memory Data Structures**: Utilizes `HashMap` and `ArrayList` for efficient management of users, products, and product requests.
- **Object-Oriented Programming (OOP)**: Principles used for modular and scalable code design.

## Architecture

- **Java-Based**: Developed in Java to ensure platform independence and robustness.
- **Database Management**: Uses in-memory `HashMap` and `ArrayList` for efficient management of users, products, and product requests.
- **Object-Oriented Design**: Utilizes OOP principles for modular and scalable code structure.

## User Interface

- **Console-Based UI**: Interaction through a command-line interface for simplicity and ease of use.
- **Menu-Driven Navigation**: Users navigate through different functionalities via intuitive menus.

## File Structure

- **`ui/`**: Contains the main application logic and user interface.
  - `Main.java`: Entry point of the application and main logic.

- **`database/`**: Manages user and product data.
  - `Database.java`: Handles in-memory storage and retrieval of user and product data.

- **`models/`**: Contains model classes representing entities in the system.
  - `Admin.java`: Represents an admin user.
  - `Customer.java`: Represents a customer user.
  - `Producer.java`: Represents a producer user.
  - `Product.java`: Represents a product in the mart.
  - `ProductRequest.java`: Represents a request for adding new products.

- **`services/`**: Provides services related to product management.
  - `ProductService.java`: Handles operations related to products.

- **`billing/`**: Manages billing and invoicing.
  - `Bill.java`: Generates billing information for purchases.

## Setup

1. **Clone the repository**:
    ```bash
    git clone https://github.com/nirmitkotadiya/Virtual-Mart-Management-System
    cd Virtual-Mart-Management-System
    ```

2. **Compile the Java files**:
    ```bash
    javac ./ui/Main.java
    ```

3. **Run the application**:
    ```bash
    java ui.Main
    ```

## Usage

1. **Start the application**:
    Run the `Main` class to start the Virtual Mart Management System.

2. **Choose an option**:
    - Login as Admin, Producer, or Customer.
    - Sign up as a new user.
    - Exit the application.

3. **Perform role-specific tasks**:
    - **Admin**: View and manage product requests.
    - **Producer**: Submit product requests.
    - **Customer**: Browse products, make purchases, and generate bills.

## Benefits

- **Efficiency**: Streamlines product management and order processing, reducing manual effort.
- **Transparency**: Provides real-time information on product availability and order status.
- **Scalability**: Easily scales to accommodate more users, products, and transactions.
- **Security**: Ensures secure access control and data protection through authentication mechanisms.

## Contributing

If you would like to contribute to this project, please follow these steps:

1. Fork the project.
2. Create a new branch for your feature or bug fix.
3. Make your changes and ensure that the code is properly documented.
4. Test your changes thoroughly.
5. Submit a pull request with a clear description of your changes.


## Author
This Virtual Mart Management System was created by Nirmit Kotadiya & his Team.

Feel free to use and modify this Virtual Mart Management System for your own educational purposes or as part of a Java project. If you have any questions or need assistance, please contact the author.

Enjoy the Virtual Mart Management System!

