Sure! Below is a detailed `README.md` file that you can include in your project. It provides step-by-step instructions on how to install and run the Inventory and Manufacturing Management System. 

```markdown
# Inventory and Manufacturing Management System

## Overview

This project is a simplified version of an inventory and manufacturing unit management system. It focuses on managing orders and inventory with features like order listing, order details, inventory management, and item manipulation. The application is built using Next.js and styled with Tailwind CSS.

## Features

- **Order List Page**: View and filter orders by status (Pending, Completed), with sorting options by customer name and item count.
- **Order Details Page**: Detailed view of an order with item details, quantities, and stock availability. Includes functionality to mark an order as completed.
- **Inventory Management**: List all items with stock levels, filter by stock availability (in stock, out of stock), add, edit, and delete items.
- **Add Items**: Form to add new items to the inventory.
- **Delete Items**: Remove items from the inventory list.
- **Search Functionality**: Quickly find orders or items.
- **Pagination**: Handle large lists of orders and inventory items.
- **Local Storage**: Persist state between page reloads.

## Prerequisites

Before you begin, ensure you have the following installed:

- [Node.js](https://nodejs.org/) (v14 or later)
- [npm](https://www.npmjs.com/) (Node package manager)

## Setup and Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/lokaesshwar/Inventory-Management-system.git
   cd Inventory-Management-system
   ```

2. **Install Dependencies**

   ```bash
   npm install
   ```

3. **Run the Development Server**

   ```bash
   npm run dev
   ```

4. **Access the Application**

   Open your browser and go to `http://localhost:3000`. You should see the home page of the Inventory and Manufacturing Management System.

## Project Structure

- `pages/`: Contains the Next.js pages.
  - `index.js`: Home page.
  - `orders.js`: Order list page.
  - `order/[id].js`: Order details page.
  - `inventory.js`: Inventory management page.
- `public/`: Static assets and JSON data.
- `components/`: Reusable components like buttons, forms, and tables.
- `styles/`: Tailwind CSS and custom styles.
- `data.json`: Sample data for orders and inventory.

## Code Overview

- **Data Handling**: The application uses `data.json` to simulate a backend.
- **State Management**: React hooks (`useState`, `useEffect`) manage state.
- **UI Components**: Tailwind CSS for styling, with custom components for a responsive design.

