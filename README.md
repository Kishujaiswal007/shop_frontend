# **E-Commerce Application**

An interactive and user-friendly e-commerce web application designed to enhance online shopping experiences. This project showcases seamless functionality, intuitive UI/UX design, and efficient state management. Built with **React**, the application integrates modern libraries and tools to ensure a robust and scalable solution.

---

## **Features**

### **1. User Authentication**
- Secure **login** and **registration** system.
- Backend API integration for user authentication.
- **Access Tokens** and **Refresh Tokens** stored securely in `sessionStorage`.

### **2. Dynamic Product Listing**
- Fetches product data from an external API dynamically.
- Displays products in a grid format with sorting functionality:
  - Sort products by **price (Low to High / High to Low)**.
- Clickable product cards navigate to a **detailed product view**.

### **3. Shopping Cart**
- **Global State Management** with the Context API:
  - Add items to the cart.
  - Adjust quantities or remove items.
  - Clear the entire cart.
  - Calculate total price dynamically.
- **Persistence**:
  - Cart data is saved in `localStorage` for a consistent experience across page reloads.
- **Payment Integration**:
  - Integrated with a payment gateway to simulate transactions.

### **4. User Profile**
- Displays personalized user information such as:
  - Name, email, address, and wallet balance.
- Features:
  - Edit profile picture functionality.
  - **Protected Route** to ensure only authenticated users can access their profile.

### **5. Toast Notifications**
- Integrated with **react-toastify** to provide instant feedback on user actions like:
  - Adding items to the cart.
  - Successful login/registration.

### **6. Error Handling**
- A custom **404 Error Page** with an animated "Page Not Found" display for undefined routes.

---

## **Tech Stack**

### **Frontend**
- **React**: Component-based architecture for building reusable UI elements.
- **React Router**: Efficient navigation and protected routing.
- **Context API**: Global state management for cart functionality.
- **react-toastify**: User-friendly notifications.

### **Styling**
- **Tailwind CSS**: Utility-first CSS framework for responsive and consistent styling.

### **Backend Integration**
- **Axios**: For API communication (login, registration, fetching user data, and payments).
- **RESTful APIs**: Backend communication for user authentication, product data, and payments.

---

## **Project Highlights**
- **State Persistence**:
  - Cart data is persisted using `localStorage`, allowing users to pick up where they left off.
- **Responsive Design**:
  - Optimized for both desktop and mobile users with clean and modern UI.
- **Dynamic Data Fetching**:
  - Fetches product and user data from APIs dynamically, ensuring up-to-date information.
- **Payment Integration**:
  - Simulates payment processing through Razorpay (or similar gateways).

---

## **How to Run the Project**
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
2. Install dependencies::
   ```bash
   npm install
3. Create a .env file in the root directory and add:
   ```bash
   VITE_API_URL=<your-backend-api-url>
4. Start the development server:
   ```bash
   npm run dev
5. Open the app in your browser at:
   ```bash
   [npm install](http://localhost:3000)

---

## **Future Enhancements**
- **Order History**:
  - Allow users to track their previous purchases.
- **Search Functionality**:
  - Enable users to search for specific products.
- **Admin Dashboard**:
  - Manage products, users, and orders.
