Personal Muneem 💰

A full-stack personal finance tracker to manage incomes and expenses efficiently.

🚀 Tech Stack

Frontend

React
Axios
Styled Components
Chart.js

Backend

Node.js
Express
Mongoose
CORS
dotenv

Database

MongoDB
⚙️ Getting Started
1. Install Dependencies
Backend
cd Personal-Muneem/backend
npm install
Frontend
cd Personal-Muneem/frontend
npm install
2. Configure Environment Variables
Backend

Create a .env file inside Personal-Muneem/backend:

MONGO_URL=your_mongodb_connection_string
PORT=5000
Frontend (Optional)

Create a .env file inside Personal-Muneem/frontend:

REACT_APP_BASE_URL=http://localhost:5000/api/v1/

If not set, the frontend defaults to:

http://localhost:5000/api/v1/
3. Run the Backend
cd Personal-Muneem/backend
npm run dev

Or:

npm start

📍 Backend runs on:
http://localhost:5000

4. Run the Frontend

Open a new terminal:

cd Personal-Muneem/frontend
npm start

📍 Frontend runs on:
http://localhost:3000

📜 Available Scripts
Backend
npm run dev → Start server with nodemon
npm start → Start server with Node.js
Frontend
npm start → Run React development server
npm run build → Create production build
npm test → Run tests
🔗 API Endpoints

Base URL: /api/v1

Income
POST /add-income
GET /get-incomes
DELETE /delete-income/:id
Expense
POST /add-expense
GET /get-expenses
DELETE /delete-expense/:id
📝 Notes
Main application code is inside Personal-Muneem/
Root package.json is a placeholder and not used to run the full app
MongoDB must be running or accessible via MONGO_URL
🚧 Future Improvements
Add authentication
Improve validation and error handling
Add editing for transactions
Add test coverage (frontend + backend)
