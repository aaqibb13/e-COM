# E-com
Python Django Web Framework based e-commerce Web Application with store, cart and checkout functionality.

# Prerequistes
- Python Version 3.xx should be installed into your system
- Install Django framework if not installed already
     > pip install Django

# How to Run the Application
1. Clone the repository
2. cd to the same directory where the directory is cloned
3. It is ideal to create a Virtual environment to install all the dependencies and run the project in. Run the following command in command prompt:
     > python -m venv Env
4. Activate the Virtual enviroment by the following command:
     > c://users/hp/desktop/python/venv/scripts/activate
where, Env is the name of your Virtual environment
5. Follow Step 6, If requirements.txt is already available or generate requirements.txt using:
     > pip freeze > requirements.txt
6. Install all the dependencies/requirements:
     > pip install requirements.txt
7. Run the server by running the following:
     > python manage.py runserver
The server should now be running at `127.0.0.1:8000`

# Functionalities
- E-commerce Application Store
    - Add to Cart Functionality 
    - View Functionality
- Cart Functionality
    - Checkout Functionality
    - Payment gateway Integration
- Shopping functionality 
    - For Registered User
    - For Guest User
