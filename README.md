# OpenMapConnect

OpenMapConnect is an open-source project designed to democratize the e-commerce space within the ONDC network. It provides a cost-effective and scalable solution for integrating open-source maps into Buyer and Seller Apps, enabling a variety of functionalities crucial for e-commerce operations.

## Features

- Interactive creation and editing of polygons with support for multiple representations (GPS coordinates, Google S2 cells, Uber H3 cells, etc.).
- Generation of motorable paths between two points using routing algorithms based on OpenStreetMap data.
- Reverse geocoding to convert addresses to points on the map using services like Nominatim.
- Motorable distance calculation considering various modes of transportation.
- API support for mapping points to polygons or paths interactively.

## Technology Stack

- **Frontend:** ReactJS, React-Leaflet
- **Backend:** Django
- **Maps:** OpenStreetMap, Mapbox

## How to Run

### Prerequisites

- Node.js and npm installed for the ReactJS frontend.
- Python and pip installed for the Django backend.

### Frontend (ReactJS)

1. Navigate to the `frontend` directory.
   ```bash
   cd frontend
2. Install dependencies.
    ```bash
    npm install
3. Start the React development server.
    ```bash
    npm start




