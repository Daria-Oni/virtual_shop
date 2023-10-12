# Virtual Shop

Virtual Shop is a simple Flask-based online store. I created this during a YouTube lesson to practice developing Flask applications. The project helped me connect a Bootstrap template, integrate a database for storing items, design a form to add new products, and implement a payment method for transactions.

## Features:

- Display a list of available products sorted by price.
- Add new products to the database through a form.
- Process payments via CloudIPSP.

## Possible improvements:

1. **User authentication**: incorporate user registration and login functionality. Users should be able to sign up, log in, and view their purchase history.
2. **Product images**: allow sellers to upload images for the products they're listing.
3. **Reviews and ratings**: implement a feature where buyers can leave reviews and ratings for products they've purchased.
4. **Shopping cart**: instead of immediate payment upon clicking a product, allow users to add multiple products to a cart and then checkout.
5. **Search functionality**: allow users to search for specific products.

## Setup:

To get this project up and running, follow these steps:

1. Clone the repository.
2. Install the required packages using `pip install -r requirements.txt`
3. Run `app.run()` from `main.py`.
