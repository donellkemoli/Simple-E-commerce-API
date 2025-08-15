 Simple E-commerce API

 Overview
A backend API built to handle e-commerce operations such as product listings, shopping cart management, and payment processing. Designed with a modular, secure architecture for easy scaling.
 
 Features
1. User Management
- JWT Authentication-for secure access.
- User roles:
  - Admin: Can create, update, delete products, view orders, manage stock.
  - Customer: Can browse products, manage cart, checkout, view orders.
- Register, login, and manage user profile.

 2. Product Management
- CRUD operations for products (Admin only).
- Fields: `name`, `description`, `price`, `category`, `stock`, `imageURL`.
- Product listing with search, filter, and pagination.

3. Shopping Cart
- Add, update, and remove items from cart.
- View cart details with total price calculation.
- Cart linked to logged-in user.
 4. Checkout & Payment
- Integration with **Stripe** or **PayPal** sandbox.
- Stock updated only after successful payment.
- Order status tracking.
5. Orders
- View past orders and their statuses.
- Admin can view all orders.

 Coding Rules & Workflow

 Coding Rules & Workflow

To maintain code quality and collaboration, follow these rules:

 1. Always Pull Latest Code from `main`
```bash
git checkout main
git pull origin main

### 2. Create a Working Branch for Each Issue
git checkout -b feature/issue-<issue-number>-<short-description>

3. Work on Your Feature or Bugfix

Make your changes and commit them:

git add .
git commit -m "Describe your changes"

4. Push Your Branch
git push origin feature/issue-<issue-number>-<short-description>

5. Create a Pull Request

Go to the repository on GitHub.

Create a Pull Request from your branch to main.

Request a code review.

Note: Always pull from the main branch before starting new work to ensure you have the latest codebase.

