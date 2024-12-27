# Music-Store-Management-System
A Java-based console application to manage an online music store. Features include admin functions for adding, deleting, and listing albums, as well as viewing orders and history. Customers can browse albums, view their cart, place orders, and check order history. Designed for simple interaction via a menu-driven interface.

## Features

### Admin Features
- Login functionality with a predefined admin account.
- Add new albums to the store.
- Delete existing albums from the store.
- List all available albums.
- View and manage orders.

### Customer Features
- Browse the available albums.
- View items in their cart.
- Place an order for albums.
- View their order history.

## Project Structure

### Main Classes
1. **OnlineMusicStore**: The main class of the application containing the entry point and handling the overall flow.
2. **User**: Represents a user with credentials (username and password).
3. **Album**: Represents an album in the store, including title, artist, and price.
4. **Order**: Represents an order containing a list of albums and total amount.

### Workflow
1. The application starts with a main menu where users can log in as either an admin or a customer.
2. Admins can manage albums and view orders.
3. Customers can browse albums, manage their cart, and place orders.

## Usage

### Running the Application
1. Compile all the `.java` files.
    ```bash
    javac OnlineMusicStore.java
    ```
2. Run the main class.
    ```bash
    java OnlineMusicStore
    ```

### Admin Login
- Default credentials:
  - Username: `Tanvir`
  - Password: `903`

### Customer Features
- Customers can select options from the customer dashboard to browse albums, view their cart, or place an order.

## Future Improvements
- Add persistence using a database or file storage.
- Implement a cart system for customers.
- Enhance user authentication with role-based access.
- Add input validation and error handling.

## Technologies Used
- **Language**: Java
- **IDE**: Any Java-compatible IDE (e.g., IntelliJ IDEA, Eclipse, etc.) or text editor.

## Author
- **Tanvir Rahim Zim**
