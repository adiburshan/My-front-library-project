# Library Du Moi Frontend

Welcome to Library Du Moi, a web application for managing a library's resources and user interactions.
Here you can see all the books that exist in the library, loan book as you wish, return books, see what you have loaned

It is built with HTML, CSS, JS, Bootstrap, and integrates with a Flask backend.
Technologies Used:
Front-End: HTML, CSS, JavaScript, Axios-makes requests to the backend, its a process of sending and receiving data from the server
Frameworks/Libraries: Bootstrap
Backend: Flask (REST API)

SERVER = "https://my-library-back-project-to-render-2.onrender.com";

## Getting Started
To get started with the project, follow these steps:

Before you will start:
1. create virtual environment 
2. activate the virtual environment
3. Clone the repository:
   git clone https://github.com/adiburshan/My-front-library-project.git
4. install all the requirements ('pip install -r requirements.txt')


Start the Development Server:
Run the Flask server: python app.py
Open index.html in your browser to begin using the application.



Features
Navbar: Responsive navigation bar with links to browse books, login, register, and log out.
Carousel: Displays featured images of books with captions.
Sidebar: Accessible via a toggle button, displays user account details and admin-specific links dynamically.
Account Management: Allows users to update their information and view account details.


Contact
For issues or questions, please contact Library Du Moi at:
Email: librarydumoi@mail.com
Phone: 03-9301202

index.html:
Contains register, login, logout, and account info

account.html:
Contains the account info, update customer by the customer

register.html:
Contains the form to register 

login.html:
Contain the login info for the login, saves the access token to local storage

customers.html:
contains - Customer Management: View, update, and delete customer information.
Filter and Search- Filter customers by activity status and search by user name.
Authentication- Uses JWT authentication to secure API requests.

add_book.html:
The "Add Book" function allows the admin to add new books to the library collection through a web interface.
Form Fields-
Title: Enter the title of the book.
Author: Provide the name of the book's author.
Published Date: Enter the year the book was published.
Type: Select the loan type duration from the dropdown menu.
Photo: Upload a cover photo of the book in JPG, PNG, or GIF format.

books_for_admin:
Admin can perform various actions such as seeing all the books that ever existed in the DB, update the book and delete the book(after deleting the books he will not be deleted from the DB, he will be marked as not active)

loan_book.html:
Book Display- View a list of books with details like title, author, published date, and availability.
Loan Functionality- Users can loan available books directly from the interface.
Responsive Design- Designed using Bootstrap for a responsive and user-friendly experience.

return.html:
Contains the function to return book, fter you will return the book, the book availability will be updated to availablle in the DB

show_books.html:
Display a list of available books with details.
Allow users to search for books by title.

show_admin_all_loans.html:
Allows the admins to view all the loans that was ever existed, present who borrowed which book ,the date of loan and the date of return

all_late_loans.html:
Displays all overdue loans in the book management system, allowing admin to track and manage late returns.
Loan Details- Displays loan ID, customer name, book title, loan date, and expected return date.
Provides clear indication of overdue loans.

show_my_loans.html:
The "My Loans" page displays all current loans for the logged-in user, providing details such as loan date and return date

show_my_late_loans.html:
The "My Late Loans" page displays all loans that are overdue for the logged-in user, highlighting them in red for easy identification.
Lists all overdue loans by the logged-in user.
Loans are highlighted in red to indicate they are overdue.

from the navbar you can navigate where ever you want


Enjoy:)





