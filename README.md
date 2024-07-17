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
  - Redux
  - Bootstrap

- **Backend:**
  - Node.js
  - Express.js
  - MongoDB

- **Authentication:**
  - JWT (JSON Web Token)

- **Payment Gateway:**
  - Stripe

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

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any inquiries or feedback, please contact us at support@swapnshop.com.
