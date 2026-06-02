# e-plantShopping

## Project: Paradise Nursery Shopping Application

Repository name: e-plantShopping

### Overview

Paradise Nursery is a front-end React application that lets users browse houseplants, add them to a shopping cart, change quantities, and view checkout information. This project demonstrates React, Redux Toolkit, and Vite and was built for training purposes.

### Features

- A Landing page with a button linking to the product listing page
- A navigation bar with links to the landing, product listing, and shopping cart pages
- A card for each plant that showcases the different plants along with their images, name, description, cost and an Add to cart button.
- A minimum of two sections describing the plants in that section. For example, "Aromatic Plants" and "Medicinal Plants".
- A cart page which displays the products in the cart.
- The cart should have a card for each type of plant in the cart. Each card should have the thumbnail, the unit cost, the cost for all of the plants of that type and buttons to increase and decrease the quantity along with Delete button.
- A Continue Shopping and Checkout buttons


### Key files (for grading)

- `README.md`
- `src/AboutUs.jsx` — About Us content
- `src/App.css` — includes landing page background styles
- `src/App.jsx` — landing page and navigation
- `src/ProductList.jsx` — product listing and Add-to-Cart logic
- `src/CartItem.jsx` — shopping cart UI and quantity/remove controls
- `src/CartSlice.jsx` — Redux slice implementing cart logic
- `src/store.js` — Redux store configuration
