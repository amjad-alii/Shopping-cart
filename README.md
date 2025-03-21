# Shopping-cart

1. Introduction
The Shopping Cart System is a web-based application that allows users to browse products, add them to their cart, and proceed with checkout. This system is built using Spring Boot (backend), MySQL (database), and HTML, CSS, and Bootstrap (frontend). The project follows an MVC architecture and integrates RESTful APIs for smooth communication between the frontend and backend.

2. Features
User Module

✔️ User Registration & Login (JWT Authentication)

✔️ User Profile Management

✔️ Browse Products (Categories, Search, Filters)

✔️ Add to Cart, Remove from Cart, and Update Quantity

✔️ Checkout & Order Placement

Admin Module

✔️ Admin Login

✔️ Manage Products (Add, Edit, Delete)

✔️ View Customer Orders

✔️ Manage Inventory


Shopping Cart & Order Processing

✔️ View Cart Items & Update Quantities

✔️ Secure Checkout with Payment Integration (Optional: Razorpay, Stripe, PayPal)

✔️ Order Summary & Confirmation Email

3. Technologies Used

Component	Technology

Backend	Spring Boot 3.9.8, Spring MVC, Spring Data JPA

Frontend	HTML, CSS, Bootstrap

Database	MySQL

Tools	Spring Tool Suite (STS), Postman for API testing

Security	JWT Authentication & Spring Security

5. System Architecture

The system follows a three-tier architecture:

Frontend (Presentation Layer) - HTML, CSS, and Bootstrap provide a responsive UI.

Backend (Business Logic Layer) - Spring Boot handles API requests, processes business logic, and interacts with the database.

Database (Persistence Layer) - MySQL stores user, product, order, and transaction data.

5. API Endpoints (Backend)
   
HTTP Method	Endpoint	Description

POST	/api/auth/register	Register a new user

POST	/api/auth/login	Authenticate user & return JWT token

GET	/api/products	Get all products

POST	/api/cart/add	Add product to cart

DELETE	/api/cart/remove/{id}	Remove product from cart

POST	/api/order/checkout	Process checkout

GET	/api/admin/orders	View all orders (Admin only)

7. Deployment Options
   
Backend: Deployed using Render, AWS EC2

Frontend: Hosted on Netlify or GitHub Pages

Database: Hosted on Amazon RDS or MySQL local server

9. Future Enhancements
    
🔹 Implement payment integration (PayPal/Stripe)

🔹 Add order tracking & invoice generation

🔹 Introduce wishlist & product ratings

🔹 Use React.js or Angular for an enhanced frontend experience


11. Conclusion
The Shopping Cart System provides an efficient way for users to purchase products online. With a well-structured backend using Spring Boot and MySQL, and a clean frontend with Bootstrap, this project is a solid foundation for real-world e-commerce applications.
