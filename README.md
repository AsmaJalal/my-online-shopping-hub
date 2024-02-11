# This is a online-shopping-app
## A Ecommerce Website made with React.js Framework and configureStore @reduxjs/toolkit.
## Screenshots

![App Screenshot](https://raw.githubusercontent.com/AsmaJalal/online-shopping-app/master/public/assets/ss4.jpg)

![App Screenshot](https://raw.githubusercontent.com/AsmaJalal/online-shopping-app/master/public/assets/ss3.jpg)

![App Screenshot](https://raw.githubusercontent.com/AsmaJalal/online-shopping-app/master/public/assets/ss2.jpg)

![App Screenshot](https://raw.githubusercontent.com/AsmaJalal/online-shopping-app/master/public/assets/ss1.jpg)



## Gif Images


![App Screenshot](https://firebasestorage.googleapis.com/v0/b/react-apps-5ed78.appspot.com/o/ecom1.gif?alt=media&token=417cd4c6-5d32-420b-88fe-ea99517f4cbb)

![App Screenshot](https://github.com/AsmaJalal/online-shopping-app/blob/master/public/images/ecom.gif)

![App Screenshot](https://github.com/AsmaJalal/online-shopping-app/blob/master/public/images/ecom.gif)

## Features
- Fully Responsive

## Product Listing: 
- Fetch products from the API and display them in a grid or list format on the home page or a dedicated products page (Products component).

## Product Details: 
- Implement a feature where users can click on a product to view its details. You can use the Product component to display detailed information about a specific product.

## Categories and Filtering: 
- Allow users to filter products by categories such as electronics, clothing, etc. You can utilize the category information provided by the API to implement this feature.

## Search Functionality: 
- Implement a search bar that allows users to search for products based on their titles or descriptions. You can use the search functionality provided by the API.

## Shopping Cart: 
- Implement a shopping cart feature where users can add products to their cart and view the items they've added. Use the Cart component to display the cart contents.

## User Authentication: 
- Implement user authentication using the Login and Register components. Allow users to create accounts, log in, and securely access their profile and order history.

## Checkout Process: 
- Allow users to proceed to checkout once they've added items to their cart. Use the Checkout component to collect shipping and payment information before completing the purchase.

## Order History: 
- Implement a feature where registered users can view their order history. You can use the fakestoreapi.com endpoints to simulate order placement and retrieval.

## Responsive Design: 
- Ensure that your app is mobile-friendly and responsive across different devices and screen sizes to provide a seamless shopping experience.

## Loading Indicators: 
- Display loading indicators or placeholders while fetching data from the API to provide feedback to users and improve the perceived performance of your app.

## Pagination: 
- If the API supports pagination, implement pagination functionality to fetch and display products in smaller, more manageable chunks.

##📂 What's inside?
A quick look at the folder structure of this project.

    .
    ├── public
    │   ├───assets
    │   │   ├───images
    │   ├───index.html
    │   ├───logo.png
    │   ├───manifest.json
    ├── src
    │   ├───components
    │   │   ├───Footer.jsx
    │   │   ├───index.js
    │   │   ├───main.jsx
    │   │   ├───Navbar.jsx
    │   │   ├───Products.jsx
    │   ├───pages
    │   │   ├───AboutPage.jsx
    │   │   ├───Cart.jsx
    │   │   ├───Checkout.jsx
    │   │   ├───ContactPage.jsx
    │   │   ├───Home.jsx
    │   │   ├───index.js
    │   │   ├───Login.jsx
    │   │   ├───PageNotFound.jsx
    │   │   ├───Product.jsx
    │   │   ├───Products.jsx
    │   │   ├───Register.jsx
    │   ├───redux
    │   │   ├───action
    │   │   │   ├───index.js
    │   │   ├───reducer
    │   │   │   ├───handleCart.js
    │   │   │   ├───index.js
    │   │   │   ├───store.js
    │   └───index.js
    

* [React](https://reactjs.org/)
* [Redux](https://redux.js.org/)
* [Bootstrap](https://getbootstrap.com/)
* [Fake Store API](https://fakestoreapi.com/)

# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
