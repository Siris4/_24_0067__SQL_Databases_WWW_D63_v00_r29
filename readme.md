# Siris's Book Collection

A Flask-based web application to manage a collection of books. This application allows users to add, view, update, and delete books from a SQLite database.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Routes](#routes)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Installation

### Prerequisites

- Python 3.7 or higher
- Flask
- Flask-SQLAlchemy

### Steps

1. **Clone the repository**:

   ```bash
   git clone https://github.com/yourusername/siris-book-collection.git
   cd siris-book-collection
Create a virtual environment and activate it:

bash
Copy code
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
Install the required packages:

bash
Copy code
pip install Flask Flask-SQLAlchemy
Run the application:

bash
Copy code
python app.py
The application will be available at http://127.0.0.1:5000/.

Usage
Adding a Book
Navigate to http://127.0.0.1:5000/add_form.
Fill in the book details (title, author, rating).
Click the "Add Book" button.
Viewing Books
Navigate to http://127.0.0.1:5000/.
You will see a list of all the books in your collection.
Updating a Book Rating
From the main list of books, click the "Edit Rating" link next to the book you want to update.
Fill in the new rating and submit the form.
Deleting a Book
From the main list of books, click the "Delete Book" button next to the book you want to delete.
Alternatively, navigate to http://127.0.0.1:5000/delete_form, enter the title of the book, and click the "Delete Book" button.
Routes
/: List all books.
/add_form: Form to add a new book.
/delete_form: Form to delete a book by title.
/edit_form/<int:book_id>: Form to edit a book's rating.
/delete/<int:book_id>: Delete a book by its ID.
/delete_book: Delete a book by its title (via form submission).
/check_db: Check the database and list all books (for debugging).
Contributing
Fork the repository.
Create a new branch (git checkout -b feature-branch).
Make your changes.
Commit your changes (git commit -am 'Add new feature').
Push to the branch (git push origin feature-branch).
Open a Pull Request.
License
This project is licensed under the MIT License - see the LICENSE file for details.

Contact
Siris - siris1Dev@gmail.com

Project Link: https://github.com/Siris4/_24_0067__SQL_Databases_WWW_D63_v00_r29
