### INF601 - Advanced Programming in Python
### Tanzeem Siddique
### Mini Project 4


# Mini Project 4 - Django Polls Application with Authentication

## Description

This project is a Django-based web application for creating and participating in polls. It allows users to view the latest polls, vote on choices, and see the results. Additionally, it incorporates a user registration and login system to manage user access. The application utilizes Bootstrap for responsive styling and includes a modal for displaying general information.

### Key features include:

* **View Latest Polls:** Displays a list of the most recently published polls on the homepage.
* **Vote on Polls:** Allows users to select a choice and cast their vote on a specific poll.
* **View Poll Results:** Shows the vote counts for each choice in a poll.
* **User Registration:** Enables new users to create an account with a username and password.
* **User Login:** Allows registered users to log in to the application.
* **User Logout:** Provides a way for logged-in users to securely log out.
* **Django Admin:** Utilizes the built-in Django admin interface for managing polls, questions, and choices with customized styling.
* **Bootstrap Integration:** Uses Bootstrap for responsive design and includes a modal for displaying information.

## Getting Started


### Dependencies

1.  **Install Required Packages:**
    * Install the packages using pip:
    ```
    pip install -r requirements.txt
    ```

2.  **Initialize the Database:**
    * Make Migrations:
    ```
    python manage.py makemigrations
    ```
    
3.  **Initialize the Database:**
    * Apply Migrations:
    ```
    python manage.py migrate
    ```
4.  **Create a Superuser (for Django Admin):**
    * Make Migrations:
    ```
    python manage.py createsuperuser
    ```

### Executing program

1.  **Run the Application:**
    * Start the development server::
    ```
    python manage.py runserver
    ```

### Output

* **Homepage (Latest Polls):** Navigate to `http://127.0.0.1:8000/` to view the list of the latest polls.
* **Django Admin:** Access the Django admin interface by navigating to `http://127.0.0.1:8000/admin/`. Log in with the superuser credentials you created earlier to manage your polls, questions, and choices through a web interface.
* **About Us:** Navigate to `http://127.0.0.1:8000/about/` to view the "About Us" page.
* **Contact Us:** Navigate to `http://127.0.0.1:8000/contact/` to view the "Contact Us" page.

## Authors

Tanzeem Siddique

## Acknowledgments

Inspiration, code snippets, etc.
* [Django](https://docs.djangoproject.com/en/4.2/intro/)
* [Bootstrap](https://flask.palletsprojects.com/en/stable/tutorhttps://getbootstrap.com/docs/5.3/getting-started/introduction/)
* [YouTube](https://www.youtube.com/watch?v=lSqCJqnwCb8)
