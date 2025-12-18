🍽️ Food-Del – Food Delivery Platform  
A full-stack food delivery application that allows users to browse food items, add them to a cart, and place orders online, along with a dedicated admin panel to manage food items and customer orders, backed by a Node.js/Express backend.

🚀 Features  

Customer Application (frontend folder)  
Food Listing: Browse and view available food items.  
Food Details: View detailed information and images of each food item.  
Cart Management: Add, remove, and update items in the cart.  
User Authentication: Secure user login and signup functionality.  
Order Placement: Place food orders through a checkout flow.  
Order History: View previously placed orders.  

Admin Panel (admin folder)  
Food Management: Add, update, and delete food items with images.  
Food Listing: View and manage the complete food inventory.  
Order Management: Track and update the status of customer orders.  

🛠️ Tech Stack  

Client (Frontend & Admin)  
Framework: React (JSX)  
Build Tool: Vite  
Styling: CSS / Tailwind CSS  

Server (Backend)  
Runtime: Node.js  
Framework: Express.js  
Database: MongoDB (Mongoose)  
Image Storage: Cloudinary  
Authentication: JWT (JSON Web Tokens)  

📦 Installation and Setup  

This project follows a monorepo structure with separate folders for frontend, admin, and backend.

Prerequisites  
Node.js (LTS version)  
MongoDB (local or cloud)  
Cloudinary account for image storage  

1. Backend Setup  
Navigate to the backend directory:  
cd backend  

Install dependencies:  
npm install  

Create a `.env` file and add required environment variables such as database URL, JWT secret, and Cloudinary credentials.

2. Frontend and Admin Setup  

Customer Frontend:  
cd frontend  
npm install  

Admin Panel:  
cd ../admin  
npm install  

▶️ Running the Application  

Start the Backend Server:  
cd backend  
node server.js  

The API will run on the configured port (e.g., http://localhost:4000).

Start the Customer Frontend:  
cd frontend  
npm run dev  

The application will typically run at http://localhost:5173.

Start the Admin Panel:  
cd admin  
npm run dev  

The admin panel will typically run at http://localhost:5174.
