# SwapNShop

SwapNShop is an e-commerce platform that allows users to browse, search, and purchase products. It also includes a unique bargaining feature where buyers can negotiate the price with sellers.

## Features

- **Browse Products:** Users can browse through a wide range of products.
- **Search Products:** Users can search for products using product names.
- **Product Details:** Detailed view of each product.
- **Add to Cart:** Users can add products to their shopping cart.
- **Checkout:** Secure checkout process for purchasing products.
- **Bargain Functionality:** Buyers can bargain with sellers for a better price.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/Dkhalasi12/SwapNShop.git
    ```

2. Navigate to the project directory:
    ```bash
    cd swapnshop
    ```

3. Install dependencies:
    ```bash
    npm install
    ```

4. Set up environment variables. Create a `.env` file in the root directory and add the following:
    ```env
    DATABASE_URL=your_database_url
    SECRET_KEY=your_secret_key
    ```

5. Run the development server:
    ```bash
    npm start
    ```

## Usage

1. **Browse Products:**
   - Navigate to the home page to see a list of products.
   - Use the categories and filters to narrow down your search.

2. **Search Products:**
   - Use the search bar at the top of the page to find products by name.

3. **View Product Details:**
   - Click on a product to view detailed information, including price, description, and images.

4. **Add to Cart:**
   - On the product detail page, click the "Add to Cart" button to add the item to your shopping cart.

5. **Checkout:**
   - Navigate to your cart and click "Checkout" to proceed with the purchase.
   - Follow the prompts to complete your order.

6. **Bargain:**
   - On the product detail page, click the "Bargain" button.
   - Enter your desired price and submit your offer.
   - Wait for the seller's response. You will be notified if your offer is accepted or countered.

## Technologies Used

- **Frontend:**
  - React
  - Bootstrap

- **Backend:**
  - Node.js
  - Express.js
  - MongoDB

- **Authentication:**
  - JWT (JSON Web Token)

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch:
    ```bash
    git checkout -b feature-name
    ```
3. Make your changes.
4. Commit your changes:
    ```bash
    git commit -m 'Add some feature'
    ```
5. Push to the branch:
    ```bash
    git push origin feature-name
    ```
6. Open a pull request.
   ### Week 1: Initial Setup and Basic Implementation

**Date:** [Start Date] - [End Date]

**Goals:**
- Set up the development environment.
- Install necessary dependencies.
- Create the basic structure of the application.
- Implement a simple Express.js server.

**Tasks Completed:**
1. **Development Environment Setup:**
   - Installed Node.js and npm.
   - Created the project directory (SwapNShop).

2. **Project Initialization:**
   - Initialized the project with `npm init -y`.

3. **Dependency Installation:**
   - Installed Express.js using `npm install express`.

4. **Basic Server Implementation:**
   - Created `app.js` with a basic Express.js server.
   - Set up a route to serve the home page.

5. **Static File Serving:**
   - Created a `public` directory with `index.html`.
   - Configured Express to serve static files from the `public` directory.

6. **Testing:**
   - Ran the server and verified it works by accessing `http://localhost:3000`.

**Challenges:**
- None reported.

**Next Steps:**
- Add more routes to the server.
- Design database schema and set up database connection.
- Implement user authentication.
- Develop basic front-end pages using HTML/CSS.

### Week 2: Adding Routes and Database Integration

**Date:** [Start Date] - [End Date]

**Goals:**
- Define and implement main application routes.
- Set up database connection (e.g., MongoDB or PostgreSQL).
- Create models for users, products, and listings.

**Tasks Completed:**
1. **Route Implementation:**
   - Created routes for user registration, login, and profile management.
   - Set up routes for creating, reading, updating, and deleting product listings.

2. **Database Setup:**
   - Installed database driver (e.g., `mongodb` for MongoDB or `pg` for PostgreSQL).
   - Established connection to the database.

3. **Model Creation:**
   - Defined schema for users, products, and listings.
   - Created models and integrated them with the routes.

4. **Testing:**
   - Tested API endpoints using Postman.

**Challenges:**
- Database connection issues.

**Next Steps:**
- Implement user authentication and authorization.
- Build front-end pages for user interactions.
- Start integrating front-end with back-end APIs.

### Week 3: User Authentication and Front-end Development

**Date:** [Start Date] - [End Date]

**Goals:**
- Implement user authentication and authorization.
- Develop front-end pages for user registration, login, and profile management.
- Integrate front-end with back-end APIs.

**Tasks Completed:**
1. **Authentication:**
   - Implemented user registration and login functionality.
   - Set up session management or JWT for authentication.

2. **Front-end Development:**
   - Designed and developed pages for user registration and login.
   - Created a user profile page with editable information.

3. **API Integration:**
   - Integrated front-end forms with back-end API endpoints for authentication.

4. **Testing:**
   - Conducted end-to-end testing of user registration and login flows.

**Challenges:**
- Ensuring secure password storage and authentication mechanisms.

**Next Steps:**
- Develop product listing pages and search functionality.
- Implement user authorization for protected routes.
- Start working on the main marketplace interface.

### Week 4: Product Listings and Marketplace Interface

**Date:** [Start Date] - [End Date]

**Goals:**
- Develop product listing and search functionality.
- Create the main marketplace interface.
- Enhance user experience with improved UI/UX design.

**Tasks Completed:**
1. **Product Listings:**
   - Implemented routes and views for creating and managing product listings.
   - Added search functionality to filter product listings.

2. **Marketplace Interface:**
   - Designed and developed the main marketplace page.
   - Integrated product listings and search functionality into the marketplace interface.

3. **UI/UX Enhancements:**
   - Improved overall design and user experience of the application.

4. **Testing:**
   - Tested product listing and search features extensively.

**Challenges:**
- Designing an intuitive and responsive UI.

**Next Steps:**
- Implement messaging functionality between buyers and sellers.
- Develop notification system for user interactions.
- Optimize the application for performance and scalability.

### Week 5: Messaging, Notifications, and Optimization

**Date:** [Start Date] - [End Date]

**Goals:**
- Implement messaging functionality.
- Develop a notification system for user interactions.
- Optimize application performance and scalability.

**Tasks Completed:**
1. **Messaging Functionality:**
   - Implemented real-time messaging between buyers and sellers using Socket.io.
   - Set up the necessary back-end and front-end components for messaging.

2. **Notification System:**
   - Developed a notification system to alert users of important interactions.
   - Integrated notifications into the user interface.

3. **Optimization:**
   - Conducted performance testing and identified bottlenecks.
   - Implemented optimization strategies to improve application performance.

4. **Final Testing and Deployment:**
   - Conducted thorough testing of all features.
   - Prepared the application for deployment.

**Challenges:**
- Ensuring real-time communication is reliable and efficient.

**Next Steps:**
- Deploy the application to a cloud platform (e.g., AWS, Heroku).
- Monitor the application and address any post-deployment issues.
- Plan for future feature enhancements and updates.
