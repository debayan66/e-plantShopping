# 🌱 E-Plant Shopping - React Redux Application

A responsive plant shopping cart web application built using **React, Redux Toolkit, and Vite**.  
This project was completed as part of the **IBM Full Stack Software Developer Professional Certificate** program on Coursera.

The original starter project was provided through the IBM course material, and the implementation was completed by adding React component logic, Redux state management, and shopping cart functionality.

---

## 📌 Project Overview

E-Plant Shopping is an e-commerce style application where users can browse plant products, add items to a shopping cart, update quantities, and manage selected products.

The main objective of this project was to understand:

- Component-based frontend development
- React state management
- Redux Toolkit workflow
- Managing application-wide data
- Building interactive UI features

---

## 🚀 Features Implemented

### 🪴 Product Listing
- Displays available plant products
- Product cards with details
- Add products to cart functionality

### 🛒 Shopping Cart
- Add items to cart
- Increase item quantity
- Decrease item quantity
- Remove items from cart
- Calculate total number of products dynamically

### 🔄 Redux State Management
Implemented Redux store functionality including:

- Cart state initialization
- Actions and reducers using Redux Toolkit
- Global cart updates

Reducers:

```javascript
addItem()
removeItem()
updateQuantity()
```

---

## 🛠️ Technologies Used

- React.js
- JavaScript (ES6+)
- Redux Toolkit
- React Redux
- Vite
- HTML5
- CSS3
- Git & GitHub
- GitHub Pages

---

## 📂 Project Structure

```text
e-plantShopping/

├── src/
│   ├── ProductList.jsx
│   ├── CartItem.jsx
│   ├── CartSlice.jsx
│   ├── store.js
│   ├── App.jsx
│   └── main.jsx
│
├── package.json
├── vite.config.js
└── README.md
```

---

## ⚙️ Installation and Setup

Clone the repository:

```bash
git clone <repository-url>
```

Navigate into the project:

```bash
cd e-plantShopping
```

Install dependencies:

```bash
npm install
```

Run development server:

```bash
npm run dev
```

---

## 📦 Deployment

Build project:

```bash
npm run build
```

Deploy using GitHub Pages:

```bash
npm run deploy
```

---

## 🎯 Learning Outcomes

Through this project, I practiced:

- Creating reusable React components
- Managing global state using Redux Toolkit
- Dispatching Redux actions
- Working with reducers and store configuration
- Debugging dependency and deployment issues
- Version control using Git

---

## 📚 Course Reference

This project was developed while completing the:

**IBM Full Stack Software Developer Professional Certificate**  
Platform: Coursera

---

## 👨‍💻 Author

**Debayan Nath**

B.Tech Computer Science (Cyber Security) Student

---

## Note

This repository is based on IBM Coursera learning material.  
Additional implementation, debugging, Redux logic integration, and deployment configuration were completed as part of my learning process.
