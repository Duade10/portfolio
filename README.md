# Portfolio Site

This is a portfolio site built with Django and Django REST Framework, allowing users to create and showcase their portfolios. Users can register, log in, and manage their portfolio items, while visitors can view public portfolios.

## Features

- User registration and authentication
- Create, update, and delete portfolio items
- Upload images and files for portfolio items
- View public portfolios of other users
- Admin panel for managing users and portfolios

## Technologies Used

- Python
- Django
- Django REST Framework
- PostgreSQL (or any other database supported by Django)
- HTML/CSS/JavaScript

## Installation

1. Clone the repository: 
    > git clone [https://github.com/your-username/portfolio-site.git](https://github.com/Duade10/portfolio.git)
2. Navigate to the project directory:
    > cd portfolio-site
3. Create a virtual environment and activate it:
    > python -m venv env 
   
    > source env/bin/activate 
   
    On Windows
    > env\Scripts\activate
4. Install the required dependencies:
    > pip install -r requirements.txt
5. Set up the database:
   > python manage.py migrate
6. Create a superuser for the admin panel:
   > python manage.py createsuperuser
7. Start the development server:
   > python manage.py runserver

The site should now be accessible at `http://localhost:8000`.

## Usage

- Register a new account or log in with an existing account.
- Go to the admin panel (`/admin`) and create portfolio items.
- Visit the portfolio detail page to view and manage your portfolio.
- Visit the public portfolio list page to view portfolios of other users.

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them with descriptive commit messages.
4. Push your changes to your forked repository.
5. Submit a pull request with a detailed description of your changes.

## License

This project is licensed under the [MIT License](LICENSE).
