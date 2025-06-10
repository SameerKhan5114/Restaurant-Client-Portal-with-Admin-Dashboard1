
---

## Frontend Setup (React)

1. **Navigate to the frontend directory:**
   ```sh
   cd restaurant-portal/frontend


2.Install dependencies:

npm install

3.Configure environment variables:

Create a .env file in the frontend directory:
 REACT_APP_API_BASE_URL=http://localhost:5000/api
 REACT_APP_MAP_API_KEY=your-google-maps-api-key



4.Start the React development server:

npm start





Backend Setup (Node.js / Express)
Navigate to the backend directory:
cd restaurant-portal/backend


Install dependencies:
npm install


Configure environment variables:

Create a .env file in the backend directory:
PORT=5000
MONGO_URI=<your-mongodb-connection-string>
JWT_SECRET=<your-jwt-secret>
ADMIN_EMAIL=<admin-email>
ADMIN_PASSWORD=<admin-password>


Replace the placeholders with your actual values.


Start the backend server:
npm run dev