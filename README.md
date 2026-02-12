# CosmoCart-Ecommerce-Website

A modern and responsive E-Commerce Web Application built using HTML, CSS, and JavaScript.
This app allows users to register, log in, browse products, view details, add items to a cart, and manage their orders — all wrapped in a clean and interactive UI.

# Features

~ User registration and login system
~ Browse products fetched from Fake Store API
~ Search products by name
~ View detailed information of a single product
~ Add and remove items in the cart
~ User-specific cart saved in localStorage
~ Responsive design for mobile, tablet, and desktop
~ Modern UI with gradients, hover effects, and clean layouts

# Technologies Used

~ HTML – Structure of the web pages
~ CSS – Styling, layout, and responsive design
~ JavaScript – DOM manipulation, Fetch API, localStorage, event handling

# How It Works

~ User registers an account or logs in
~ Products are displayed on the home page in a grid layout
~ Users can search for products in real-time
~ Clicking a product opens the single product view
~ Users can add products to their cart
~ The cart page allows removing items and viewing totals
~ Logout option to end session

# Project Structure

CosmoCart_E-Commerce-Website/
│
├── index.html # Home page with product grid and search
├── singleProduct.html # Single product detail page
├── cart.html # User cart page
├── login.html # User login page
├── register.html # User registration page
├── index.css # Styling for home page
├── singleProduct.css # Styling for single product page
├── cart.css # Styling for cart page
├── login.css # Styling for login page
├── register.css # Styling for register page
├── index.js # Home page logic, product fetching, search
├── singleProduct.js # Single product page logic and Add to Cart
├── cart.js # Cart page logic, delete functionality
├── login.js # Login functionality
└── register.js # Registration functionality

This project helped me strengthen my understanding of:

~ DOM manipulation and event handling
~ Fetching and displaying data from APIs
~ Managing user sessions with localStorage
~ Building interactive and responsive web applications
~ Implementing CRUD operations for cart management

# How to use/setup

1. Clone the repository
git clone https://github.com/srivanipaspunoor1234/CosmoCart-Ecommerce-Website.git
cd CosmoCart-Ecommerce-Website

2. Open the project in your code editor
~ Open the folder in VS Code or any editor of your choice.

3. Connect to a JSON server (optional)
~ If you want to use a local JSON server for products and cart data:
  1.Install json-server globally (if not installed):
  npm install -g json-server
  2.Create a db.json file in the project root with sample data:
  3.Start the JSON server:
  json-server --watch db.json --port 5000
  4.Update API URLs in your JS files (if needed) to
   http://localhost:5000/users.

4. Open the project in a browser
~ You can simply open index.html in a browser, or use a live server extension in VS Code.   

5. Test the application
~ Register a new user, log in, browse products, add items to the cart, and manage orders.
   


