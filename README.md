# Django REST API for Product Management

A simple Django REST API to manage products using Django and Django REST Framework.

1. Clone the repository and navigate to the folder:
 
   git clone <repository-url>
   cd ecommerce_project

Here’s a concise version of the README.md:

markdown
Copy code
# Django REST API for Product Management

A simple Django REST API to manage products using Django and Django REST Framework.

## Features
- **POST /api/products/create/**: Create a product.
- **GET /api/products/**: Retrieve all products.

## Setup
1. Clone the repository and navigate to the folder:
  
   git clone <repository-url>
   cd ecommerce_project
## Create and activate a virtual environment:
python -m venv venv
venv\Scripts\activate
## Install dependencies and run migrations:

pip install django djangorestframework
python manage.py makemigrations
python manage.py migrate
## Start the server:

python manage.py runserver
## Testing
Use Thunder Client or any API tool to get and post

