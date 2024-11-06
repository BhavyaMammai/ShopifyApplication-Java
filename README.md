# ShopifyApplication
This Spring Boot shopping application provides a comprehensive e-commerce experience, allowing users to browse products, manage their carts, place orders, and complete secure payments. Admins have access to order management and receive notifications for real-time updates on new orders.

# Features
I. User Features
   
1. User Registration and Login
- Users can register an account, log in, and securely manage their profile.
- Passwords are encrypted for security, and session management ensures only logged-in users can place orders.
2. Product Catalog with Categories
- Products are organized into categories for easy browsing.
- Detailed product pages include descriptions, pricing, and options for adding items to the cart.
3. Shopping Cart
- Users can add products to their cart, view the selected items, adjust quantities, and remove items.
- Cart totals update in real-time based on item selections, making it easy to review before checkout.
4. Checkout and Payment Integration
- Integrated payment system for completing purchases.
- Secure payment gateway ensures that all transactions are handled with encrypted data.
- Upon successful payment, users receive a confirmation message, and the order is saved to their order history.
5. Order History
- Users can view their previous purchases with details on items, dates, and transaction status.
- This feature adds convenience and enables users to reorder or track past orders.
6. Notifications
- Users receive an order confirmation email upon completing a purchase.
- Real-time notifications for status updates ensure a seamless customer experience.
- 
II. Admin Features

1. Order Management Dashboard
- Admins can view all orders, including pending, completed, and canceled statuses.
- Order details are displayed in a user-friendly dashboard, enabling efficient management.
2. Email Notifications
- Admins receive real-time email notifications when a new order is placed.
- Notifications include order details and customer information, allowing quick action.
3. Product Management
- Admins can manage product listings, including adding, updating, and deleting items.
- The inventory management system keeps product information organized and up-to-date.
4. Responsive and Enhanced UI
- The interface is built with Thymeleaf templates and is responsive for mobile and desktop views.
- Bootstrap, Javascript and CSS framework is used to enhance styling and create a seamless, user-friendly experience.

# Technology Stack
- Backend: Spring Boot, Spring MVC, Spring Security, JPA
- Frontend: Thymeleaf, Bootstrap
- Database: MySQL
- Payment Integration: Secure payment API integrated at checkout
- Email Notifications: SMTP integration for sending user and admin emails

# Setup Instructions
1.Clone the repository:

- bash
- Copy code
- git clone https://github.com/yourusername/shopping-application.git
2. Navigate to the project directory and install dependencies:

- bash
- Copy code
- cd shopping-application
- ./mvnw clean install
3. Run the application:

- bash
- Copy code
- ./mvnw spring-boot:run
4. Access the application at http://localhost:8080.

5. Configuration
- Email Notification Setup
- Configure email SMTP settings in application.properties to enable email notifications:

6. properties
- Copy code
- spring.mail.host=smtp.example.com
- spring.mail.port=587
- spring.mail.username=your-email@example.com
- spring.mail.password=your-email-password
- spring.mail.properties.mail.smtp.auth=true
- spring.mail.properties.mail.smtp.starttls.enable=true


# Usage
1. User Journey
- Account Creation: Register and log in.
- Browse Products: Explore categories and view individual product details.
- Add to Cart: Select items and adjust quantities.
- Checkout: Complete payment to finalize the purchase.
- Order Confirmation: Receive a confirmation email with order details.
- Order History: View previous purchases.
2. Admin Journey
- Order Monitoring: Receive an email notification upon order placement.
- Order Management: Use the dashboard to manage and update orders.
- Product Updates: Add or update products in the catalog.
# Future Enhancements
- Advanced Product Filtering and Search: Adding filters by price, ratings, etc.
- Customer Reviews: Allow users to review products post-purchase.
- Wishlist Feature: Enable users to save items for later.
- Multi-language Support: Localize the app for a global user base.
- Advanced Analytics: Track sales trends, customer demographics, and top products on an admin dashboard.
