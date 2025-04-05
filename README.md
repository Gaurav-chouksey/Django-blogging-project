# Django Blogging Project

This project is a full-stack web application built with Django and Django REST Framework. It serves as a blogging platform where users can register, create and manage blog posts, and engage in discussions through comments. The project demonstrates a solid command of Django fundamentals and modern web development practices.

## Key Features

### User Authentication & Profile Management:

* User registration with email, username, and password validation.
* Secure login and logout functionality.
* Dedicated user profile page displaying user details, along with the posts and comments they have created.

### Blog Posts:

* CRUD (Create, Read, Update, Delete) operations for blog posts.
* Image upload functionality for posts.
* Pagination to display a limited number of posts per page.
* Search functionality to filter posts by keywords.
* "Like" feature allowing users to like/unlike posts.

### Comments:

* Users can add, edit, and delete comments on blog posts.
* Each comment supports a "like" system.

### User Interface:

* A clean, responsive UI built using Bootstrap with custom styling.
* Consistent card-based layouts for forms (e.g., New Post and Profile update pages).
* A hero section on the homepage to welcome users and highlight key features.

## Technologies Used

### Backend:

* Python
* Django
* Django REST Framework

### Frontend:

* HTML
* CSS
* Bootstrap

### Database:

* SQLite (by default; can be configured for other databases)

### Other:

* Pillow (for image handling)
