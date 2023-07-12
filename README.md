# online-shop

# Lessons

1. Introduction
2. Install Tools
3. Create React App
4. Create Git Repository
5. List Products
   1. create products array
   2. and product images
   3. render products
   4. style products
6. Add routing
   1. npm i react-router-dom
   2. create route for home screen
   3. create router for product screen
7. Create Node.JS Server
   1. run npm init in root folder
   2. Update package.json set type: module
   3. Add .js to imports
   4. npm install express
   5. create server.js
   6. add start command as node ackend/server.js
   7. require express
   8. create route for / return backend is ready.
   9. move products.js from frontend to backend
   10. create route for /api/products
   11. return products
   12. run npm start
8. Fetch Products From BackEnd
   1. set proxy in package.json
   2. npm install axios
   3. use state hook
   4. use effect hook
   5. use reducer hook
9. Manage State By Reducer Hook
   1. define reducer
   2. update fetch data
   3. get state from useReducer
10. Add bootstrap UI Framework
   1. npm install react-bootstrap bootstrap
   2. update App.js

11. Create Product and Rating Component
   1. Create Rating component
   2. create Product Component
   3. Use Rating Component in Product Component
12. Create Product Details Screen
   1. fetch product from backend
   2. create 3 columns for image, info and action
13. Create Loading and Message Component
   1. create loading component
   2. use spinner component
   3. create message component
   4. create utils.js to define getError function
14. Implement Add to Cart
   1. Create React Context
   2. Define Reducer
   3. Create Store Provider
   4. Implement add to cart button click handler
15. Complete Add to Cart
   1. check exist item in the cart
   2. check count in stock in backend
16. Create Cart Screen
   1. Create 2 Columns
   2. Display items list
   3. Create Action Column
17. Complete Cart Screen
   1. click handler for inc/dex item
   2. click handler for remove item
   3. click handler for checkout
18. Create Signin Screen
   1. create sign in form
   2. add email and password
   3. add signin button
19. Connect to MongoDB Database
   1. create atlas mongodb database
   2. install local mongodb database
   3. npm install mongoose
   4. connect to mongodb database
20. Seed Sample Data
   1. create Product model
   2. create User model
   3. create seed route
   4. use seed route
   5. seed sample product
21. Seed Sample Users
   1. create user model
   2. seed sample users
22. Create Signin Backend API
   1. create signin api
   2. npm install jsonwebtoken
   3. define generateToken
23. Complete Signin Screen
   1. handle submit action
   2. save token in store and local storage
   3. show user name in header
24. Create Shipping Screen
   1. create form inputs
   2. handle save shipping address
   3. add checkout wizard bar