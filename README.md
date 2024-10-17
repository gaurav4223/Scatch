Scatch
# Introduction
This is a virtual e-commerce website developed using Node.js, Express.js, and Mongoose. It simulates a real online store where users can browse products, add items to their cart, and complete purchases. 

To access the admin panel located at /admin, you will need an admin email and password.

## Technology Stack
The application is built using the following technologies:

Node.js (v12.16.3)
MongoDB (v4.2.0)
Express.js (v4.16.1)
Bootstrap (v4.4.1)
FontAwesome (v5.13.0)
Stripe API (v3): For payment processing on the checkout page
Mapbox API: Displays a map on the "About Us" page
AdminBro: Customized to create the admin panel
Nodemailer: Sends emails through the "Contact Us" form
Passport: Handles user authentication
Express Validator: Validates form inputs
Features
### User Features:
Account Management: Users can sign up, log in, and log out.
Product Browsing: View products added by the admin.
Shopping Cart: Add or remove products from the cart, and view its contents.
Checkout: Users must be logged in to proceed with checkout, and payment is processed using Stripe. The order history is available in the user’s profile.
#### Admin Features:
Admin Panel: Accessible by logging in with admin credentials.
Database Management: Admins can view, add, edit, and delete users, products, orders, and categories. However, the cart model cannot be modified by the admin, as it is managed by users before purchase or deleted after purchase.





