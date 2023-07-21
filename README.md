# Book Issue System of Library

## Description
The Book Issue System of Library is a simple console-based software application that allows a librarian to manage student book issue records in a library. It provides functionalities to save student information with issued book details and display all the books that have been issued.

## Features

- **Save Student Info**: The librarian can enter and save student information, including roll number, student name, department, book issued, genre, and the date of issue.

- **Display Issued Books**: The application allows the librarian to view all the books that have been issued along with the corresponding student details and the date of issue.

## How to Use

1. Clone the repository to your local machine or download the source code.

2. Compile the code using a C compiler, such as GCC.

3. Run the compiled executable to start the application.

4. The application will present a menu with the following options:

   - Enter 1: Save Student Info.
   - Enter 2: Display All Books Issued.
   - Enter 3: Exit

5. To save student information and issued book details:
   - Choose option 1.
   - Enter the roll number, student name, department, book issued, genre, and the date of issue as prompted.
   - The data will be saved to a file named `libr.dat` in binary format.

6. To display all the books issued:
   - Choose option 2.
   - The application will read the data from the `libr.dat` file and display the details of all the issued books.

7. To exit the application:
   - Choose option 3.

## File Management

The application stores the student information and book issue details in a binary file named `libr.dat`. It creates the file if it does not exist and appends new records to it each time a student's information is saved.

Please ensure that the file path for `libr.dat` is correct. In the provided code, the file is assumed to be located at `C:/Users/AYUSH/Desktop/MCP-PIC/libr.dat`. If you want to change the file location, modify the file path accordingly in the `fopen` and `fclose` functions.

## Contributing

We welcome contributions to enhance the features or fix any issues in the Book Issue System of Library. If you wish to contribute, feel free to create a pull request with your changes.

## License

The Book Issue System of Library is open-source software licensed under the [MIT License](LICENSE.md).

## Contact

If you have any questions, suggestions, or encounter any problems while using the Book Issue System of Library, you can contact the project team at `ayushbulbule@gmail.com`. We appreciate your feedback!
