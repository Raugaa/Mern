# E-Mandi: A Direct Farmer-to-Buyer Marketplace

**E-Mandi** is a MERN stack-based web platform that connects farmers directly with buyers, eliminating middlemen to ensure transparent pricing and efficient transactions. The platform allows farmers to list their agricultural products, while buyers can browse, order, and confirm delivery through a streamlined interface.

## Table of Contents
- [Features](#features)
- [Technology Stack](#technology-stack)
- [Getting Started](#getting-started)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Future Enhancements](#future-enhancements)
- [Contributing](#contributing)
- [License](#license)

## Features
- **User Registration & Login**: Separate sign-up for farmers and buyers.
- **Product Listings**: Farmers can add and manage product listings with images and descriptions.
- **Search & Filter**: Buyers can search products and filter by category and price.
- **Order Management**: Buyers can add products to their cart, place orders, and track order statuses.
- **OTP-Based Confirmation**: Secure order confirmation via OTP.
- **Product Reviews**: Buyers can leave ratings and reviews for products and sellers.

## Technology Stack
- **Frontend**: React.js, Bootstrap, CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JWT (JSON Web Token)
- **APIs**: Custom API integrations for order management, OTP, and payments

## Getting Started
Follow the instructions below to set up and run the **E-Mandi** platform locally.

### Prerequisites
Ensure that you have the following installed on your system:
- Node.js
- npm (Node Package Manager)
- MongoDB (local or cloud instance)

### Installation
1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/e-mandi.git

git clone https://github.com/yourusername/e-mandi.git
### Navigate to the project directory:
2. ** Navigate to the project directory**:
   ```bash
   cd e-mandi

### Install dependencies for both frontend and backend:
3. **Install dependencies for both frontend and backend**:
   ```bash
   npm install
###Usage
 1. **Starting the Frontend: Navigate to the frontend directory and start the frontend server**:
    ```bash
    cd Frontend
    npm strat
    
2. **Starting the Backend: Open a new terminal window and navigate to the backend directory**:
   ```bash
   cd Backend
   npm start
The backend API will be running on http://localhost:7000.

Database Setup: Make sure MongoDB is running. You can either use a local MongoDB instance or connect to MongoDB Atlas for cloud hosting.

Structure:
E-Mandi/
├── Frontend/            
├── Backend/             
├── models/             
