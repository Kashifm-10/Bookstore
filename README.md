Bookstore Application (Adding New Books)

This is a basic bookstore application that allows users to register new books. It demonstrates the core functionality of adding books to a database using Spring Boot and HTML.

Technologies Used

Spring Boot: A framework for building Spring-based applications.
Thymeleaf: A templating engine for creating HTML views.
Spring Data JPA: A framework for interacting with databases.
MySQL Database: An in-memory database for development purposes.


Features

Add New Books:
Provides a form to input book details (title, author, ISBN).
Submitting the form saves the new book to the database.

Project Structure
bookstore-app/

├── src/main/java/com/bookstore/
│   └── BookstoreApplication.java

├── src/main/java/com/bookstore/model/
│   └── Book.java

├── src/main/java/com/bookstore/repository/
│   └── BookRepository.java

├── src/main/java/com/bookstore/controller/
│   └── BookController.java

├── src/main/resources/templates/
│   └── addBook.html

├── src/main/resources/application.properties
├── pom.xml

Running the Application

After running the application, you can access the book adding form at http://localhost:1000/addBook. You can add new books by filling out the form and submitting it.

Notes

This is a basic example and can be expanded to include other features like displaying books, searching, and more.
The MySQL database is used for demonstration purposes.
The redirect:/addBook in the addBook() method ensures that the user is redirected back to the form after adding a book. This provides a better user experience.



