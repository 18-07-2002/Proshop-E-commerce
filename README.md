# **ProShop eCommerce Platform**  

ProShop is a full-featured eCommerce platform built using the MERN stack (MongoDB, Express, React, Node.js) with Redux for state management. It offers a seamless shopping experience, including features like a shopping cart, product reviews, user profiles, and order management. The platform provides admin tools for managing products, users, and orders, along with PayPal/credit card payment integration. With a built-in database seeder for easy setup, this project is designed to be a scalable and robust online store solution.
> A fully functional eCommerce platform developed using the MERN stack (MongoDB, Express.js, React, Node.js) with Redux for state management.

This project was built as part of a comprehensive MERN eCommerce course, focusing on creating a scalable online shopping solution with essential features for both customers and administrators.

---

## **Features**  

- **Full-featured shopping cart**: Add, remove, and manage products in the cart.
- **Product reviews and ratings**: Customers can leave feedback and ratings for products.
- **Top products carousel**: Showcase top-rated or featured products.
- **Product pagination**: Browse through products with pagination.
- **Product search feature**: Search and filter products seamlessly.
- **User profile management**: Track orders and manage personal details.
- **Admin product management**: CRUD operations for product listings.
- **Admin user management**: View, edit, or delete user accounts.
- **Admin order details page**: View detailed order information.
- **Mark orders as delivered**: Admins can update order statuses.
- **Checkout process**: Manage shipping, payment options, and order summary.
- **PayPal/credit card integration**: Secure payment methods.
- **Database seeder utility**: Pre-load sample products and users for testing.

---

## **Setup & Usage**  

### **Environment Variables Configuration**  
Create a `.env` file in the project root directory and add the following variables:

```
NODE_ENV = development  
PORT = 5000  
MONGO_URI = your_mongodb_uri  
JWT_SECRET = 'abc123'  
PAYPAL_CLIENT_ID = your_paypal_client_id  
```

---

### **Install Dependencies**  

Run the following commands to install both frontend and backend dependencies:  

```bash
# Install backend dependencies
npm install  

# Navigate to frontend folder and install frontend dependencies
cd frontend  
npm install  
```

---

### **Running the Application**  

```bash
# Run both frontend (http://localhost:3000) and backend (http://localhost:5000)
npm run dev  

# Run only the backend server
npm run server  
```

---

## **Build & Deploy**  

```bash
# Create production build for frontend
cd frontend  
npm run build  
```

A Heroku post-build script is included. When pushing to Heroku, the frontend will build automatically, eliminating the need for manual builds.

---

### **Database Seeding**  

Use these commands to import or destroy sample data in the database:  

```bash
# Import sample products and users  
npm run data:import  

# Destroy all data from the database  
npm run data:destroy  
```

---

### **Sample User Logins**  

| Role     | Email                | Password |  
|----------|----------------------|----------|  
| Admin    | admin@example.com    | 123456   |  
| Customer | john@example.com     | 123456   |  
| Customer | jane@example.com     | 123456   |  

---

This project serves as a complete eCommerce solution with robust features for end-users, administrators, and seamless third-party integrations.
**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: https://facebook.github.io/create-react-app/docs/code-splitting

### Analyzing the Bundle Size

This section has moved here: https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size

### Making a Progressive Web App

This section has moved here: https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app

### Advanced Configuration

This section has moved here: https://facebook.github.io/create-react-app/docs/advanced-configuration

### Deployment

This section has moved here: https://facebook.github.io/create-react-app/docs/deployment

### `npm run build` fails to minify

This section has moved here: https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify
