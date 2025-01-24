# E-commerce Website

A responsive e-commerce website built with HTML, CSS, and JavaScript, featuring Firebase authentication and real-time database integration using Firestore.

## Features

### User Authentication
- User signup and login functionality
- Firebase Authentication integration
- Secure user sessions
- Logout capability
- Protected routes for authenticated users

### Product Management
- Category-wise product display
- Dynamic product loading from Firebase
- Product details view
- Buy now functionality (requires authentication)


### Categories
- Electronics
- Fashion
- Grocery
- Home & Furniture
- Toys & Kid Accessories

## Technologies Used

- HTML5
- CSS3
- JavaScript
- Firebase
  - Authentication
  - Firestore Database
- Custom Web Components

## Project Structure

e-commerce-website/
│
├── components/
│   └── header.js                 # Reusable header component
│
├── css/
│   └── style.css                 # Global styles
│
├── js/
│   └── firebase-config.js        # Firebase configuration
│
├── pages/
│   ├── Electronics.html          # Electronics category page
│   ├── Fashion.html             # Fashion category page
│   ├── Grocery.html             # Grocery category page
│   ├── Home.html                # Home & Furniture category page
│   ├── Toys.html                # Toys category page
│   ├── login.html               # User login page
│   └── register.html            # User registration page
│
├── images/                       # Image assets
│   ├── slider/                  # Slider images
│   ├── categories/              # Category images
│   └── products/                # Product images
│
├── index.html                   # Home page

## Features to be Added

- Shopping cart functionality
- Payment integration
- Order history
- User profile management
- Product search
- Product filtering

## License

This project is licensed under the MIT License.

