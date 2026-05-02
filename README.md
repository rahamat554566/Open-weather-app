⚙️ Backend Setup & Installation
Follow these steps to get the backend server running on your local machine:

1. 🛠️ Prerequisites
Node.js: Ensure you have the latest stable version installed. Download Node.js

MongoDB: You will need a database via MongoDB Atlas or MongoDB Compass.

Weather API: Register for a free API key at OpenWeatherMap.


2. 📂 Navigate to Backend
Open your terminal in the project root and move into the backend folder:

-->cd backend


3. 📦 Install Dependencies
Install the core MERN backend packages (express, dotenv, cors, and mongoose):

-->npm install


4. 🔐 Environment Configuration
Create a file named .env inside the backend folder and add your credentials:

PORT=5000
MONGO_URI=your_mongodb_connection_string
WEATHER_API_KEY=your_openweather_api_key
⚠️ Important: Your .gitignore is already configured to keep backend/.env private. Never share this file!


5. 🚀 Run the Server
Start the server using Node.js:

-->node server.js

The server should now be running at http://localhost:5000.








🎨 Frontend Setup & Installation (React + Vite)
The frontend is built using React with the Vite build tool for a high-performance development experience.

1. 🏗️ Create the Project
If starting fresh, the project was initialized using:


npm create vite@latest frontend -- --template react


2. 📂 Navigate and Install
Enter the frontend directory and install the necessary dependencies:


cd frontend
npm install


3. 🔗 Backend Integration & Dependencies
To connect the UI to the backend and handle styling, the following packages are required:

Axios: For making API requests to the Node.js server.

Bootstrap 5: For responsive and professional UI components.

Install via terminal:


npm install axios bootstrap



4. 🎨 Global Styling
To enable Bootstrap throughout the application, add this import to your src/main.jsx:


import 'bootstrap/dist/css/bootstrap.min.css';


5. 🚀 Run the Application
Start the development server:

npm run dev
The application will be accessible at http://localhost:5173.
