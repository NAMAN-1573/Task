Vehicle Movement on Google Maps
Overview
This project demonstrates a web application that displays multiple vehicles moving in real-time on a Google Map. Each vehicle's current location, route, and live movement are shown on the map, with different colors for each vehicle.

Features
Display vehicles on a Google Map using custom icons.
Show real-time vehicle movement from source to destination.
Draw the route taken by each vehicle.
Use different colors for different vehicles.
Smooth, continuous movement of vehicles along their routes.
Technologies Used
React.js
Google Maps JavaScript API
React Icons
Node.js (for the backend API)
Getting Started
Prerequisites
Make sure you have the following installed on your machine:

Node.js (v12 or higher)
npm or yarn
Installation
Clone the repository:

sh
Copy code
git clone https://github.com/your-username/vehicle-movement-map.git
cd vehicle-movement-map
Install dependencies for the frontend:

sh
Copy code
cd frontend
npm install
Install dependencies for the backend:

sh
Copy code
cd backend
npm install
Google Maps API Key
You need a Google Maps API key to use the Google Maps JavaScript API.

Go to the Google Cloud Console.
Create a new project or select an existing one.
Go to the APIs & Services > Credentials page.
Click Create credentials > API key.
Restrict your API key as needed.
Replace YOUR_GOOGLE_MAPS_API_KEY in src/components/VehicleMap.js with your actual API key.

Running the Application
Start the backend server:

sh
Copy code
cd backend
node server.js
Start the frontend development server:

sh
Copy code
cd frontend
npm start
Open your browser and go to http://localhost:3000.
