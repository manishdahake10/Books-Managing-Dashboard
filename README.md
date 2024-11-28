# Library Management System Project

## Overview
This is a Library Management System application built in Java, which allows users to manage books in a library. Users can add, view, edit, and delete books. The system provides a graphical user interface (GUI) for ease of use, where users can interact with the system to perform these operations.

## Features
- Add new books to the library.
- View the list of available books with details like Book ID, Title, Author, Publisher, Year of Publication, ISBN, and number of copies.
- Edit existing book information.
- Delete books from the library system.
- Clear the form fields to add new books.
- Exit the system gracefully.

## GUI Elements
- **Input Fields**: 
    - Book ID
    - Book Title
    - Author
    - Publisher
    - Year of Publication
    - ISBN
    - Number of Copies
- **Buttons**:
    - **Add**: Adds a new book to the system.
    - **View**: Displays the current list of books.
    - **Edit**: Allows updating book details.
    - **Delete**: Removes a book from the system.
    - **Clear**: Clears input fields to enter new book details.
    - **Exit**: Exits the application.

## Technologies Used
- **Java**: The programming language used for building the system.
- **Swing**: Java’s GUI toolkit used for building the graphical user interface.
- **JDBC**: (Optional) For database integration to store and retrieve book data (if applicable).
- **Text-based Interface**: Basic text-based operations for debugging or testing.

## Requirements
- Java 8 or above.
- Java Development Kit (JDK) installed on your system.

## Installation
1. Clone this repository to your local machine:
    ```bash
    git clone https://github.com/manishdahake10/LibraryManagementSystem.git
    ```

2. Navigate to the project directory:
    ```bash
    cd LibraryManagementSystem
    ```

3. Compile the `Library_management.java` file:
    ```bash
    javac Library_management.java
    ```

4. Run the application:
    ```bash
    java Library_management
    ```

## Usage
Once the program runs, you will be presented with a GUI window with the following options:
- Enter details for a new book and click **Add** to add it to the system.
- Click **View** to see a list of all books currently in the system.
- Select an existing book and click **Edit** to modify its details.
- Select a book and click **Delete** to remove it from the system.
- Click **Clear** to reset the input fields for adding a new book.
- Click **Exit** to close the application.

### Output ScreenShots

ScreenShot 1 :<br>
![Capture2](https://github.com/user-attachments/assets/163878ee-e075-4704-97fe-e02ce85644b8)<br><br>
ScreenShot 2 :<br>
![Capture1](https://github.com/user-attachments/assets/ae68e870-7830-47dc-b398-537083885e6e)<br><br>
ScreenShot 3 :<br>
![Capture3](https://github.com/user-attachments/assets/bc34e3a7-13c9-4573-bd98-ed852db3d2cf)<br><br>
ScreenShot 4 :<br>
![Capture4](https://github.com/user-attachments/assets/4672cc83-acd5-4e17-a49e-ae6c13684e97)<br><br>
ScreenShot 5 :<br>
![Capture5](https://github.com/user-attachments/assets/5600d347-fdcc-4366-b054-5ac9c4417da2)<br><br>
ScreenShot 6 :<br>
![Capture6](https://github.com/user-attachments/assets/dbfc7073-14a6-4d31-a440-d2b53d927f45)<br><br>

## Code Structure
The project consists of the following structure:

- `Library_management.java`: The main file that handles the user interface and integrates the book management functionality.
- `Book.java`: A model class that defines the book's properties and methods for book-related operations.

## Contribution
Feel free to fork this repository and contribute by opening issues or pull requests. Suggestions for additional features or improvements are always welcome!

## Author
**Manish Dahake**  
GitHub: [manishdahake10](https://github.com/manishdahake10)

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.






