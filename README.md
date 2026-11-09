# Paradise Nursery Shopping Application

Welcome to the **Paradise Nursery Shopping Application**, a dynamic and responsive web application designed for an online plant nursery. Built with **React** and **Redux Toolkit**, this e-commerce platform allows plant enthusiasts to explore a diverse collection of houseplants, add them to a virtual cart, adjust quantities, and view real-time cost calculations.

---

## 🌿 Project Overview

Paradise Nursery is an online haven for plant lovers, offering a wide selection of indoor plants categorized by their unique benefits. The goal of this application is to deliver an intuitive, aesthetic, and user-friendly shopping experience with seamless client-side state management.

---

## ✨ Features

- **Landing Page**:
  - Welcoming hero section with company branding and background imagery.
  - Comprehensive "About Us" section detailing company mission and values.
  - "Get Started" call-to-action button transitioning directly to the plant catalog.

- **Navigation Bar**:
  - Global navigation accessible on both the Product Listing and Shopping Cart pages.
  - Direct links to **Home**, **Plants**, and **Cart**.
  - Dynamic cart icon displaying the real-time total quantity of all selected plants.

- **Product Catalog (`ProductList`)**:
  - Over 30 unique houseplants categorized into 5 distinct groups:
    - *Air Purifying Plants*
    - *Aromatic Fragrant Plants*
    - *Insect Repellent Plants*
    - *Medicinal Plants*
    - *Low Maintenance Plants*
  - Detailed product cards featuring thumbnail images, plant names, descriptions, and unit prices.
  - Interactive **Add to Cart** buttons that automatically disable and change visual state once added.

- **Shopping Cart (`CartItem`)**:
  - Complete list of selected items displaying thumbnail, name, unit cost, and line-item total.
  - Real-time **Total Cart Amount** calculation.
  - Quantity controls (`+` and `-`) to increment, decrement, or automatically remove items when quantity reaches zero.
  - **Delete** button to remove items from the cart.
  - **Continue Shopping** button to return to the catalog.
  - **Checkout** button alerting users with a "Coming Soon" notification.

- **State Management**:
  - Powered by **Redux Toolkit** (`CartSlice`) managing actions: `addItem`, `removeItem`, and `updateQuantity`.

---

## 🛠️ Technologies Used

- **React 18** (Functional components, hooks: `useState`, `useEffect`)
- **Redux Toolkit & React-Redux** (Global state management, slices, dispatchers, and selectors)
- **Vite** (Next-generation front-end tooling and development server)
- **CSS3** (Responsive flexbox, grid, animations, and pseudo-elements)

---

## 🚀 Getting Started

### Prerequisites

- Node.js (version 16 or later)
- npm or yarn

### Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/e-plantShopping.git
   cd e-plantShopping
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Run the development server:
   ```bash
   npm run dev
   ```

4. Open [http://localhost:5173](http://localhost:5173) in your browser.

---

## 📄 License

This project is licensed under the MIT License.
