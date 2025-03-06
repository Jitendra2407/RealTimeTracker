# Real-Time Location Tracker

A real-time location tracking app using **Node.js**, **Express**, **Socket.io**, and **Leaflet.js** to track and update user locations on a map.

## Features
- **Live Location Tracking** via `navigator.geolocation.watchPosition()`.
- **Real-time Updates** using **Socket.io**.
- **Interactive Map** with **Leaflet.js** and **OpenStreetMap**.
- **Auto Removal** of disconnected users' markers.

## Installation
1. Clone the repo:
   ```sh
   git clone https://github.com/Jitendra2407/RealTimeTracker.git
   cd RealTimeTracker

2. Install dependencies:
   ```sh
   npm install

3. Start the server:
   ```sh
   nodemon app.js

4. Open http://localhost:8080 in your browser.

## How It Works

1. Browser requests location access.

2. Sends coordinates to the server via Socket.io.

3. Server broadcasts location to all users.

4. Map updates with user positions.

5. Markers are removed on user disconnect.

## Author

Jitendra Kumar Thakur

