# Ecommerce-Follow-Along

## Project Description

This project is a full-fledged E-Commerce Application using the MERN stack (MongoDB, Express.js, React.js, and Node.js). It's designed to provide hands-on experience with real-world development concepts and tools, focusing on building a scalable and feature-rich online shopping platform.

## Key Features

- Built using MERN Stack (MongoDB, Express.js, React.js, Node.js)
- REST API Creation for scalable backend services
- User Authentication for secure login and registration
- Database Schema Design using MongoDB
- Robust Backend Development with Node.js and Express

---

## Milestone 1: Project Overview

- **Introduction to MERN Stack**: Overview of the stack and its benefits.
- **REST API Structure**: Planning endpoints for user authentication and product management.
- **Database Schema Basics**: Understanding MongoDB schema design.
- **Authentication Role**: Importance of secure login and registration.
- **Project Vision**: Discussing key features and goals.
- **Live Demo**: Showcasing the application's functionality.

---

## Milestone 2: Project Setup and Login Page

- **Folder Structure**: Organized `frontend` and `backend` directories.
- **React Setup**: Initialized the React application.
- **Node.js Setup**: Configured a simple Node.js server.
- **Tailwind CSS**: Integrated for responsive styling.
- **Login Page**: Developed a responsive login interface.
- **GitHub Updates**: Committed changes to the repository.

---

## Milestone 3: Project Setup for Backend

- **Backend Structure**: Organized routes, controllers, models, and middleware.
- **Server Setup**: Configured Node.js server with Express.
- **Database Connection**: Integrated MongoDB for data storage.
- **Error Handling**: Implemented basic error handling.
- **GitHub Updates**: Updated repository with backend structure.

```
project-root/
├── backend/
│   ├── routes/         # Defines API routes
│   ├── controllers/    # Contains route handling logic
│   ├── models/         # Defines MongoDB schemas using Mongoose
│   ├── middlewares/    # Includes middleware for error handling
│   ├── config/         # Stores database configuration
│   ├── utils/          # (Optional) Helper functions
│   └── server.js       # Main server file
└── frontend/           # Frontend-related code
```

---

## Milestone 4: User Model and File Uploads

- **User Model**: Designed a schema for user data.
- **User Controller**: Managed user data interactions.
- **File Uploads**: Configured Multer for file uploads.
- **GitHub Updates**: Committed changes for user model and file uploads.

---

## Milestone 5: Sign-Up Page and Form Validation

- **Sign-Up Page**: Developed a user-friendly registration page.
- **Form Validation**: Implemented validation for user inputs.
- **GitHub Updates**: Updated repository with the sign-up page.

---

## Milestone 6: Password Encryption and User Data Storage

- **Password Encryption**: Used bcrypt to hash passwords.
- **User Data Storage**: Saved user data securely in the database.
- **GitHub Updates**: Committed changes for password encryption.

---

## Milestone 7: User Login Endpoint and Credential Validation

- **Login Endpoint**: Created a backend endpoint for user login.
- **User Data Retrieval**: Retrieved user records based on credentials.
- **Password Validation**: Compared hashed passwords securely.
- **Authentication Response**: Provided feedback based on login success.
- **Security Measures**: Implemented protections against common threats.
- **Testing**: Verified login functionality.
- **GitHub Updates**: Updated repository with login endpoint.

---

## Milestone 8: Card Component Creation and Homepage Layout

- **Card Component**: Developed a reusable product card component.
- **Dynamic Rendering**: Implemented mapping for product display.
- **Homepage Layout**: Designed a responsive grid layout.
- **User Experience**: Enhanced browsing and interaction.
- **Testing**: Verified card rendering and layout consistency.
- **GitHub Updates**: Committed changes for card component and layout.

---

## Milestone 9: Product Form Creation and Image Uploads

- **Product Form**: Designed a form for product details.
- **Multiple Image Uploads**: Enabled users to upload multiple images.
- **Form Validation**: Added validation for product inputs.
- **Admin Access**: Discussed restricting uploads to admins.
- **Testing**: Verified form functionality and image uploads.
- **GitHub Updates**: Updated repository with product form.

```
project-root/
├── frontend/
│   ├── dist/               # Production build output
│   ├── node_modules/       # Dependencies
│   ├── src/                # Main source code
│   │   ├── components/     # Reusable UI components
│   │   │   ├── Footer.jsx
│   │   │   ├── HeroSection.jsx
│   │   │   ├── HomePage.jsx
│   │   │   ├── Login.jsx
│   │   │   ├── ProductCard.jsx
│   │   │   └── ProfilePage.jsx
│   │   ├── styles/         # CSS or Tailwind styles
│   │   ├── App.jsx         # Root component
│   │   ├── main.jsx        # React entry point
│   │   ├── index.html      # Main HTML file
│   ├── .gitignore          # Git ignore file
│   ├── eslint.config.js    # ESLint configuration
│   ├── package-lock.json   # Dependency lock file
│   ├── package.json        # Project dependencies and scripts
│   ├── postcss.config.js   # PostCSS configuration
│   ├── tailwind.config.js  # TailwindCSS configuration
│   ├── vite.config.js      # Vite configuration
├── .gitignore              # Global Git ignore file
├── package.json            # Root package file
└── README.md               # Documentation

```

---

## Milestone 10: Product Schema and API Endpoint Creation

- **Product Schema**: Defined product data structure with Mongoose.
- **API Endpoint**: Created a POST endpoint for product data.
- **Data Validation**: Ensured valid data is saved in the database.
- **Testing**: Verified endpoint functionality with Postman.
- **Future Enhancements**: Discussed admin restrictions and user roles.
- **GitHub Updates**: Committed changes for product schema and endpoint.

---

## Milestone 11: Fetching and Displaying Products

- **Backend API**: Created an endpoint to send all product data from MongoDB.
- **Frontend Data Fetching**: Implemented a function to retrieve product data from the backend.
- **Dynamic Display**: Passed fetched data to the `ProductCard` component to render dynamically.
- **Component Reusability**: Utilized `ProductCard` to display multiple products efficiently.
- **Understanding Data Flow**: Learned how to send, receive, and display data using API calls.
- **GitHub Updates**: Committed changes for API integration and dynamic rendering.

```
project-root/
├── backend/
│   ├── config/         # Stores database and multer configurations
│   │   ├── database.js
│   │   └── multer.js
│   ├── controllers/    # Contains route handling logic
│   │   ├── product.controller.js
│   │   └── user.controller.js
│   ├── models/         # Defines MongoDB schemas using Mongoose
│   │   ├── product.model.js
│   │   └── user.model.js
│   ├── routes/         # Defines API routes
│   │   ├── product.routes.js
│   │   └── user.routes.js
│   ├── uploads/        # Stores uploaded files
│   ├── utils/          # (Optional) Helper functions
│   ├── node_modules/   # Node.js dependencies
│   ├── .env            # Environment variables
│   ├── package-lock.json
│   ├── package.json
│   └── server.js       # Main server file
├── frontend/           # Frontend-related code
├── .gitignore          # Git ignore file
├── package.json        # Root package file
└── README.md           # Documentation

```

---

## Milestone 12: My Products Page with User-Specific Product Display

- **Endpoint Creation**: Developed a GET endpoint to fetch all products associated with the logged-in user's email from MongoDB.
- **Frontend Integration**: Wrote a function in the frontend to retrieve user-specific product data from the backend.
- **Dynamic Display**: Utilized the existing product card component to dynamically display the fetched products on the "My Products" page.
- **Data Filtering**: Implemented filtering logic on the backend to ensure only products associated with the user's email are retrieved.
- **Testing**: Verified the functionality of the endpoint and the dynamic display using browser tools and Postman.
- **Future Enhancements**: Considered adding options for editing or deleting user-specific products.
- **GitHub Updates**: Committed all changes related to the endpoint, frontend integration, and dynamic display to the repository.

---

## Milestone 13: Product Update Endpoint and Form Auto-fill

- **Update Endpoint**: Developed a PUT endpoint to receive updated product data and modify the corresponding document in MongoDB.
- **Frontend Integration**: Added an "Edit" button to the product card. Clicking it pre-fills the product form with existing data for editing.
- **Form Auto-fill**: Implemented functionality to populate the product form with the selected product's details, enabling easy modification.
- **Data Persistence**: Ensured that the updated product data is correctly saved to the MongoDB database.
- **Testing**: Verified the update functionality using Postman and by testing the edit flow in the application.
- **GitHub Updates**: Committed all changes related to the update endpoint and form auto-fill to the repository.

---

## Milestone 14: Product Delete Endpoint

- **Delete Endpoint**: Created a DELETE endpoint to remove a product from MongoDB based on its ID.
- **Frontend Integration**: Added a "Delete" button to the product card. Clicking it triggers the deletion of the corresponding product.
- **Confirmation**: Implemented a confirmation dialog before deleting a product to prevent accidental deletions.
- **Data Removal**: Ensured that the product is successfully removed from the MongoDB database.
- **Testing**: Verified the delete functionality using Postman and by testing the delete flow in the application.
- **GitHub Updates**: Committed all changes related to the delete endpoint and frontend integration to the repository.

```
server/
├── config/
│   ├── cloudinary.js
│   ├── database.js
│   └── multer.js
├── controllers/
│   ├── product.controller.js
│   └── user.controller.js
├── middlewares/
│   └── auth.middleware.js
├── models/
│   ├── product.model.js
│   └── user.model.js
├── routes/
│   ├── product.routes.js
│   └── user.routes.js
├── uploads/
├── .env
├── package-lock.json
├── package.json
├── server.js
└── .gitignore
```

---

## Milestone 15: Navigation Component

- **Navigation Component**: Created a reusable `Nav` component with links to "Home," "My Products," "Add Product," and "Cart" pages.
- **Responsive Design**: Made the `Nav` component responsive to different screen sizes using Tailwind CSS.
- **Page Integration**: Integrated the `Nav` component into all pages of the application, providing consistent navigation.
- **Smooth Navigation**: Ensured smooth transitions between pages using React Router.
- **Testing**: Verified the navigation functionality and responsiveness across different devices.
- **GitHub Updates**: Committed all changes related to the `Nav` component and its integration to the repository.

---

## Milestone 16: Product Details Page

- **Product Details Page**: Created a new page to display detailed information about individual products.
- **Dynamic Data**: Implemented dynamic rendering of product details based on the selected product.
- **Quantity and Add to Cart**: Added quantity selection and "Add to Cart" functionality to the product details page.
- **Testing**: Verified the product details page functionality and data display.
- **GitHub Updates**: Committed all changes related to the product details page to the repository.

```
client/
├── src/
│   ├── components/
│   │   ├── CategoryCard.jsx
│   │   ├── Footer.jsx
│   │   ├── Header.jsx
│   │   ├── ProductCard.jsx
│   │   └── ProductForm.jsx
│   ├── pages/
│   │   ├── FavouritePage.jsx
│   │   ├── LandingPage.jsx
│   │   ├── LoginPage.jsx
│   │   ├── ProductPage.jsx
│   │   ├── ProfilePage.jsx
│   │   ├── SearchPage.jsx
│   │   └── SignupPage.jsx
│   ├── styles/
│   ├── App.jsx
│   └── main.jsx
├── .gitignore
├── eslint.config.js
├── index.html
├── package-lock.json
├── package.json
├── postcss.config.js
├── tailwind.config.js
└── vite.config.js
```

---

## Milestone 17: Cart Functionality Implementation

- **Cart Schema Design**: Modified user schema to store cart products with necessary product details and quantities.
- **Cart Storage Endpoint**: Created POST endpoint to handle product details reception and persistent cart storage in database.
- **Data Validation**: Implemented checks for product availability and valid quantities before cart updates.
- **Testing**: Verified cart item persistence and user-specific cart isolation.
- **GitHub Updates**: Committed schema modifications and endpoint implementation to repository. 

---

## Milestone 18: Cart Data Retrieval System

- **Cart Data Endpoint**: Developed GET endpoint to fetch all cart products using authenticated user's email.
- **Product Population**: Implemented product data population from separate collection for complete cart information.
- **Security Checks**: Added authentication middleware to ensure user-specific cart access.
- **Testing**: Validated endpoint response structure and data accuracy.
- **GitHub Updates**: Pushed cart retrieval endpoint implementation.

---

## Milestone 19: Cart Management Interface

- **Cart Page Implementation**: Created frontend cart page with dynamic product display using fetched cart data.
- **Quantity Controls**: Added interactive +/- buttons for real-time quantity adjustment per product.
- **Quantity Update Endpoints**: Built PUT endpoints for increment/decrement operations with inventory checks.
- **Live Price Calculation**: Implemented frontend total calculation based on quantity changes.
- **Sync Optimization**: Added debouncing to quantity update API calls.
- **Testing**: Verified quantity synchronization between frontend and database.
- **GitHub Updates**: Committed cart page components and quantity management endpoints.

---

## Milestone 20: User Profile and Data Management

- **Backend Endpoint for User Data**: Created a backend endpoint to send all user data via email.
- **Frontend Profile Page**: Developed a frontend profile page to display user data.
- **Profile Information Display**:
  - Displayed profile photo, name, and email in one section.
  - Displayed address information in another section with an "Add address" button.
- **Address Handling**:
  - Displayed "No address found" if no addresses are available.
- **Navigation**:
  - Implemented navigation to the address form page when "Add address" is clicked.
- **Testing**: Verified the display of user data and navigation functionality.
- **GitHub Updates**: Committed backend endpoint and frontend profile page components.

---

## Milestone 21: Address Form Integration

- **Address Form Frontend Page**: Created a frontend form to input address details.
- **Address Fields**:
  - Included fields for country, city, address1, address2, zip code, and address type.
- **State Management**: Implemented state to store input address data.
- **Navigation Integration**:
  - Enabled navigation from the profile page to the address form page upon clicking "Add address".
- **Testing**: Verified form functionality and state management.
- **GitHub Updates**: Committed address form components and state management logic.

---

## Milestone 22: Address Storage Endpoint

- **Backend Endpoint for Address Storage**: Developed a backend endpoint to store address data in the user profile.
- **Database Integration**:
  - Added address data to the address array within the user collection in the database.
- **Testing**: Verified address storage functionality and database updates.
- **GitHub Updates**: Committed backend endpoint for address storage.

---

## Milestone 23: Place Order and Select Address

- **Place Order Button**:
  - Added a "Place Order" button inside the cart page.
  - Navigates to the select address page when clicked.
- **Select Address Page**:
  - Created a select address page displaying all available addresses.
  - Provided an option to select one address for delivery.
- **Backend Endpoint for Addresses**:
  - Developed a backend endpoint to retrieve all addresses associated with the user.
  - Ensured the endpoint is secure and only accessible by authenticated users.
- **Testing**: Verified navigation and address selection functionality.
- **GitHub Updates**: Committed the place order button, select address page, and backend endpoint.

---

## Milestone 24: Order Confirmation

- **Order Confirmation Page**:
  - Displayed all products being ordered.
  - Showed the selected delivery address.
  - Displayed the total value of the cart.
- **Place Order Button**:
  - Included a "Place Order" button at the bottom of the confirmation page.
- **Testing**: Verified the order confirmation page functionality.
- **GitHub Updates**: Committed the order confirmation page and related components.

---

## Milestone 25: Place Order Endpoint Implementation

- **Backend Endpoint**: Created a POST endpoint to receive product details, user information, and the selected delivery address.
- **User Identification**: Retrieved the user's `_id` from the database using their email address.
- **Order Creation**: For each product in the cart, a separate order is created and stored in the MongoDB order collection, associated with the user and delivery address.
- **Data Persistence**: Ensured that all order details are correctly saved to the MongoDB database using the order schema.
- **Testing**: Verified the endpoint functionality using Postman to simulate order placement.
- **GitHub Updates**: Committed the place order endpoint implementation to the repository.

---

## Milestone 26: Retrieve User Orders Endpoint

- **Backend Endpoint**: Created a GET endpoint to retrieve all orders associated with a specific user.
- **User Identification**: Received the user's email and retrieved their `_id` from the database.
- **Order Retrieval**: Fetched all orders from the MongoDB order collection that match the user's `_id`.
- **Data Delivery**: Sent all the user's orders in the response.
- **Testing**: Verified the endpoint functionality using Postman to retrieve orders for a specific user.
- **GitHub Updates**: Committed the retrieve user orders endpoint implementation to the repository.

---

## Milestone 27: My Orders Page

- **Frontend Page**: Created a "My Orders" page to display all orders placed by the user.
- **Data Fetching**: Implemented a GET request to the "my-orders" endpoint, sending the user's email to retrieve their orders.
- **Dynamic Display**: Displayed all user orders on the page.
- **Navigation**: Added a link to the "My Orders" page in the navigation bar for easy access.
- **Testing**: Verified the display of user orders on the "My Orders" page.
- **GitHub Updates**: Committed the "My Orders" page and navigation updates to the repository.

---

## Milestone 28: Cancel Order Functionality

- **Frontend Integration**: Added a "Cancel Order" button to each order displayed on the "My Orders" page, except for orders that are already canceled.
- **Backend Endpoint**: Created an endpoint to receive the order ID.
- **Order Status Update**: Retrieved the order using the provided ID, updated the order status to "canceled," and saved the changes to the database.
- **Conditional Rendering**: Implemented logic to hide the "Cancel Order" button if the order is already canceled.
- **Testing**: Verified the cancel order functionality by testing the button and confirming the status update in the database.
- **GitHub Updates**: Committed the cancel order functionality and endpoint implementation to the repository.

---

## Milestone 29: Payment Method Selection and Razorpay Integration

- **Payment Options**: Added radio buttons on the order confirmation page to allow users to select between "Cash on Delivery (COD)" and "Online Payment."
- **Razorpay Integration**: When the "Online Payment" option is selected, Razorpay payment buttons are displayed.
- **Razorpay Setup**:
  - Created a Razorpay account and obtained the necessary API keys.
  - Saved the Razorpay Client ID.
- **Testing**: Verified that the Razorpay payment buttons are displayed correctly when the "Online Payment" option is selected.
- **GitHub Updates**: Committed the payment method selection and Razorpay button display logic to the repository.

---

## Milestone 30: Razorpay Payment Integration

- **Razorpay Integration**: Implemented online payment using Razorpay API using the client key you created earlier.
- **NPM Package**: Downloaded NPM package to provide an component which will display online payment methods.
- **Payment Processing**: Handled the payment processing logic when a user chooses to pay via Razorpay.
- **Testing**: Verified that the Razorpay payment is processing correctly.
- **GitHub Updates**: Committed the Razorpay payment integration and related components.

---

## Milestone 31: Global State Management with Redux

- **NPM Package Installation**: Installed `react-redux` to manage global state.
- **Store Setup**:
  - Created a `store` folder with `store.js` and `userActions.js`.
  - Configured a Redux store in `store.js` with a `userReducer` function to handle the global email state.
- **State Management**:
  - Created a `setEmail` function inside `userActions.js` to update the global email state.
- **Provider Setup**:
  - Wrapped the `App` component inside the `Provider` component in `index.js` and passed the store as a prop.

---

## Milestone 32: Using Redux for Authentication State

- **Dispatch in Login Page**:
  - Implemented the `dispatch` method in the login page to store the user's email in the global state.
- **Accessing Global State**:
  - Used `useSelector` to access the stored email on all relevant pages.
- **Testing**:
  - Verified that the email is correctly stored and accessed across different pages.

---

## Milestone 33: JWT Token Generation and Cookie Storage

- **JWT Package Installation**: Installed `jsonwebtoken` using NPM.
- **Token Creation**:
  - Used the `sign` method to create a JWT token containing the user's email and ID.
  - Set `maxAge` to define an expiration time for the token.
- **Cookie Storage**:
  - Added the JWT token inside the response as a cookie to store it in the browser.

---

## Milestone 34: JWT Validation and Authentication Middleware

- **Token Retrieval**:
  - Extracted the JWT token from the browser cookies and sent it to the backend.
- **Middleware Implementation**:
  - Created a middleware function in the backend to validate the received JWT token.
- **Authentication Enforcement**:
  - Ensured that users cannot access protected pages without a valid login.
- **Testing**:
  - Verified that unauthorized users are blocked from accessing restricted pages.

---

## Milestone 35: Deployment of Frontend and Backend

- **Backend Deployment**:
  - Deployed the backend using a deployment service.
  - Replaced `localhost` with the backend deployment URL in the frontend.
- **Frontend Deployment**:
  - Deployed the frontend using a deployment service.
- **Final Testing**:
  - Ensured that both the frontend and backend were correctly deployed and working as expected.
- **GitHub Updates**:
  - Committed all final deployment-related changes to the repository.