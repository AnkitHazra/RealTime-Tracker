# Real-Time Location Tracker

## Description
**Real-Time Location Tracker** is a web application that tracks and displays the real-time locations of multiple users on an interactive map. It leverages modern web technologies to enable seamless, real-time communication and geolocation tracking.

## Features
- **Real-Time Location Updates:** Tracks and broadcasts user locations in real-time using WebSocket.
- **Interactive Map:** Uses Leaflet.js to display user markers on a shared map.
- **Dynamic Marker Management:** Adds markers for new users and removes them when users disconnect.
- **Responsive Design:** Works across multiple devices and browser tabs.

## Technologies Used
- **Frontend:** Leaflet.js for interactive mapping.
- **Backend:** Node.js with Express and Socket.IO for server-side logic and real-time communication.
- **Geolocation API:** Fetches user coordinates dynamically.

## How It Works
1. Users' locations are fetched using the Geolocation API.
2. Locations are sent to the server via WebSocket.
3. The server broadcasts updates to all connected clients.
4. The map dynamically displays all users’ locations in real-time.


