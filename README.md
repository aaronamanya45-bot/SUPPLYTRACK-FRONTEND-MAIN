#SUPPLYTRACK FRONTEND

The client-side web application for **SupplyTrack**, built with React. It provides intuitive user interfaces for customers, suppliers, station workers, and administrators to interact seamlessly with the supply chain and order tracking system.

## Features

* **Multi-Role Dashboards**: Tailored views and controls designed specifically for Customers, Suppliers, Station Managers, and Administrators[cite: 2].
* **Secure Navigation**: Protected route wrappers and role-based validation to safeguard sensitive application pages[cite: 2].
* **Shopping & Order Workflows**: Product browsing, detailed item views, shopping cart management, checkout flows, and comprehensive order history tracking featuring visual timelines[cite: 2].
* **Administration Portals**: Dedicated management tools for handling categories, inventory items, users, orders, and pickup stations[cite: 2].

## Tech Stack

* **Library**: React (powered by Vite)[cite: 2]
* **State Management & Routing**: React Context (`AuthContext`, `CartContext`) and structured layout components (`DashboardLayout`, `PublicLayout`)[cite: 2]
* **Styling**: Custom CSS stylesheets and modular UI components[cite: 2]

## Project Structure

* `src/components/`: Reusable UI elements (Navbar, ItemCard, LoadingSpinner, TrackingTimeline, OrderStatusBadge, ProtectedRoute, etc.)[cite: 2]
* `src/context/`: Global state context providers for authentication and cart handling[cite: 2]
* `src/layouts/`: Layout wrappers defining structures for public pages and role dashboards[cite: 2]
* `src/pages/`: Page views categorized by user permissions and roles (`admin/`, `customer/`, `public/`, `station/`, `supplier/`)[cite: 2]
* `src/services/`: API communication abstraction layers (`api.js`, `authService.js`, `orderService.js`, `cartService.js`, etc.)[cite: 2]
* `src/utils/`: Helper utilities for currency formatting and dates[cite: 2]

## Getting Started

### Prerequisites

* Node.js and npm installed on your machine[cite: 2]

### Installation & Setup

1. Clone the frontend repository[cite: 2].
2. Install the project dependencies:
   ```bash
   npm install
