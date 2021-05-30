# DjangoEcomApp
Python Django Web Framework based e-commerce Web Application with Store, Cart, Logged-In User and Guest User functionality.

# Features
- E-commerce Application Store
    - Add to Cart Functionality 
    - View Functionality
- Cart Functionality
    - Product Quantity Increment and Decrement
    - Product Removal
    - Checkout Functionality
    - Payment gateway Integration
- Shopping functionality 
    - For Registered User
    - For Guest User
# Overlooking the Web Application
- **Store**

![](https://github.com/aaqibb13/DjangoEcomApp/blob/master/assets/store.png)

- **Store for Authenticated User**

![](https://github.com/aaqibb13/DjangoEcomApp/blob/master/assets/loggedinstore.png)

- **Cart for Authenticated User**

![](https://github.com/aaqibb13/DjangoEcomApp/blob/master/assets/cart.png)

- **Checkout Page**

![](https://github.com/aaqibb13/DjangoEcomApp/blob/master/assets/checkout.png)

- **Checkout Page with Payment Integration**

![](https://github.com/aaqibb13/DjangoEcomApp/blob/master/assets/checkoutwithpayment.png)
# Prerequistes
- Python Version 3.xx should be installed into your system
- Install Django framework if not installed already:

          pip install Django

# How to Run the Application
-  Clone the repository
-  `cd` to the same directory where the directory is cloned
-  It is ideal to create a Virtual environment to install all the dependencies and run the project in. Run the following command in command prompt:
      
           python -m venv Env

-  Activate the Virtual enviroment by the following command:
      
           c://users/hp/desktop/python/venv/scripts/activate
     
   where, Env is the name of your Virtual environment
- Follow next step, If requirements.txt is already available or generate requirements.txt using:
      
          pip freeze > requirements.txt
          
- Install all the dependencies/requirements:

          pip install -r requirements.txt
          
- Run the server by running the following:
          
          python manage.py runserver

The server should now be running at `127.0.0.1:8000`

## Upcoming Features
- DRF addition
     - Serialization of Data
     - Endpoints for incorporation/opportunity to add frontend frameworks like React/Angular.
