# 🛒 Online Grocery Store

**Online Grocery Store** is a full-stack eCommerce web application developed by **Aditya Andotra** for a Web Programming project. The platform allows users to explore grocery items, search with filters, manage cart items, and complete orders. Registered users can access a personal dashboard to view and manage account details, payment methods, wallet transactions, and past orders.

---

## 📂 GitHub Repository

🔗 [https://github.com/adityaandotra0/grocerystore](https://github.com/adityaandotra0/grocerystore)

---


---

## 🛠 Technologies Used

### Frontend:
- HTML, CSS, JavaScript
- **Framework:** Bootstrap
- **Library:** jQuery

### Backend:
- Node.js
- Express.js
- MongoDB

### Additional Tools & Libraries:
- Tota11y (Accessibility testing)
- HTML Validator
- Visual Studio Code
- MongoDB Compass / CLI
- NPM

---

## 💻 System Requirements

- Node.js
- MongoDB (version 3.4+)
- Code Editor (Recommended: Visual Studio Code)

---

## 📦 NPM Dependencies

```json
"bcrypt": "^1.0.2",
"body-parser": "^1.17.1",
"connect-flash": "^0.1.1",
"cookie-parser": "^1.4.3",
"cookie-session": "^2.0.0-beta.1",
"express": "^4.15.2",
"express-handlebars": "^3.0.0",
"express-passport": "^0.1.0",
"express-passport-logout": "^0.1.0",
"express-session": "^1.15.2",
"handlebars-intl": "^1.1.2",
"handlebars-paginate": "^0.1.0",
"mongodb": "^2.2.26",
"passport": "^0.3.2",
"passport-local": "^1.0.0",
"path": "^0.12.7",
"randomstring": "^1.1.5",
"uuid": "^3.0.1",
"validator": "^7.0.0",
"xss": "^0.3.3"



Getting Started
Clone the repository

bash
Copy
Edit
git clone https://github.com/adityaandotra0/grocerystore
cd grocerystore
Install dependencies

bash
Copy
Edit
npm install
Import sample data
Import the products collection from the /database folder into MongoDB. Other collections (e.g., users, orders) are created at runtime.

Start the development server

bash
Copy
Edit
npm start
Visit http://localhost:3000

🔑 Core Features
👥 User Authentication
Sign up / Sign in to make purchases.

Forgot password feature included.

🧾 User Dashboard
Account Settings: Update profile and password.

Payment Settings: Manage saved cards.

Wallet Settings: Add/manage funds, track transactions (limit: $1000 per transaction, $10,000 total).

Order History: View past purchases with date, product, and payment details.

Newsletter Subscriptions

Secure Logout

🛒 Cart Functionality
Add, update (max 5 per item), and remove items.

Real-time price calculations and checkout.

🔎 Search & Filter
Keyword search by product ID, name, brand, or category.

Filter by price range or category.

Category-based navigation available.

📦 Product Information
Detailed product pages with description and "Add to Cart" option.

💳 Payment Simulation
Fake gateway: Choose between saved cards, new cards, or wallet.

Confirmation screen with transaction summary.

Transactions logged in user dashboard.



### To Use:
1. Copy the above content into your project’s `README.md` file.
2. Push it to GitHub using:

```bash
git add README.md
git commit -m "Update README with improved formatting and content"
git push origin main
