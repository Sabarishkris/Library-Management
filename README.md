# Library Management System

Welcome to the Library Management System! This project is designed to help manage a library's books, users, and their interactions efficiently.

## Features

- **User Authentication:** Admin and user login functionality.
- **Library Setup:** Initialize and configure library details.
- **Book Management:** Add, update, search, and remove books.
- **User Management:** Add new users, create credentials, and manage user details.
- **Book Borrowing:** Users can borrow and return books, with validation on book availability and user limits.
- **Data Persistence:** All data is saved and loaded from JSON files.

## Modules

- **LoginView:** Handles user login and authentication.
- **LibrarySetupView:** Manages the initial setup and configuration of the library.
- **BookView:** Provides functionalities for managing books.
- **GetBookView:** Manages the process of borrowing and returning books.
- **ManageUserView:** Handles the addition of new users and creation of their credentials.
- **LibraryDataBase:** Manages data persistence, reading, and writing data to JSON files.

## Getting Started

1. **Download the repository project:**
    - Extract the zip
    - Open the Application 
3. **Run the Application:**
    ```sh
    javac com/zsgs/librarymanagement/LibraryManagement2024.java
    java com.zsgs.librarymanagement.LibraryManagement2024
    ```

## Dependencies

- **Jackson:** For JSON processing.
- **Java SE:** Ensure Java is installed on your machine.

## Usage

1. **Login:**
    - Use default admin credentials (`zsgs`, `admin`) to log in initially.
    
2. **Setup Library:**
    - Follow prompts to enter library details.

3. **Manage Books:**
    - Add, update, search, and remove books through the BookView.

4. **Manage Users:**
    - Add new users and manage their credentials through ManageUserView.

5. **Borrow and Return Books:**
    - Use GetBookView to borrow and return books.

## Contributing

Contributions are welcome! Please create a pull request or open an issue to discuss your ideas.

## License

This project is licensed under the MIT License.


## ScreenShot
[Library Screen shot and Features.pdf](https://github.com/user-attachments/files/15802884/Library.Screen.shot.and.Features.pdf)


