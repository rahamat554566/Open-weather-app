⚙️ Backend Setup & Installation
Follow these steps to get the backend server running on your local machine:

1. Prerequisites
Ensure you have Node.js installed on your system.

Ensure you have a MongoDB account (Atlas) or local MongoDB Compass installed.

2. Navigate to Backend
Open your terminal in the project root and move into the backend folder:

->cd backend
4. Install Dependencies
Install the required packages such as express, dotenv, cors, and mongoose:

->npm install
4. Environment Configuration
Create a file named .env inside the backend folder and add your credentials:

Plaintext
PORT=5000
MONGO_URI=your_mongodb_connection_string
WEATHER_API_KEY=your_openweather_api_key
Note: Ensure your .gitignore includes backend/.env to keep your keys secure.

5. Run the Server
Start the server using Node.js:

Bash
node server.js
The server should now be running at http://localhost:5000.
