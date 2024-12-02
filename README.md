# E-Commerce Cart Application

This is a simple **React and Redux** based e-commerce application with cart functionality. The app demonstrates concepts such as state management, API integration, and responsive UI using modern web development tools.

---

## Features

1. **Home Page**: 
   - Fetches and displays a list of products from a fake API (`https://fakestoreapi.com/products`).
   - Users can view products along with their title, description, price, and image.

2. **Cart Functionality**:
   - Add or remove items to/from the cart.
   - Displays the total number of items and total amount in the cart.
   - "Checkout Now" button for future integration of payment functionality.

3. **State Management**:
   - State is managed using **Redux Toolkit**.
   - Cart state includes actions for `add` and `remove`.

4. **Notifications**:
   - **React Hot Toast** is used to show notifications for actions like adding or removing items from the cart.

5. **Routing**:
   - **React Router** enables navigation between the Home and Cart pages.

6. **Icons**:
   - Icons are rendered using `react-icons`.

---

## Installation and Setup

### Prerequisites

- Node.js and npm installed on your system.

### Steps

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/ecommerce-cart.git
   cd ecommerce-cart
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Start the development server:

   ```bash
   npm start
   ```

4. Open the application in your browser at `http://localhost:3000`.

---

## Project Structure

```plaintext
src
├── components
│   ├── CartItem.js          # Component for individual cart items.
│   ├── Product.js           # Component for individual products.
│   ├── Spinner.js           # Loading spinner component.
├── pages
│   ├── Home.js              # Home page displaying the products.
│   ├── Cart.js              # Cart page displaying cart summary.
├── redux
│   ├── Slices
│   │   ├── CartSlice.js     # Redux slice for cart functionality.
│   ├── Store.js             # Redux store configuration.
├── App.js                   # Main application component.
├── index.js                 # Entry point of the application.
├── index.css                # Global styles.
```

---

## Technologies Used

- **React**: Component-based library for building the UI.
- **Redux Toolkit**: State management library.
- **React Router**: Navigation and routing library.
- **React Hot Toast**: For user-friendly notifications.
- **FakeStore API**: Dummy API for fetching product data.
- **React Icons**: Collection of icons for UI.

---

## API Used

The application uses the [FakeStore API](https://fakestoreapi.com/) to fetch product data.

Endpoint:  
`GET https://fakestoreapi.com/products`

---

## Future Enhancements

- Integration of user authentication.
- Persistent cart using local storage or a database.
- Payment gateway integration.
- Product search and filtering functionality.

---

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes and push to the branch:
   ```bash
   git push origin feature-name
   ```
4. Submit a Pull Request.

---
