# PLANTSY APP

##  Features
View Plants: Displays a list of plants retrieved from the server.
Add New Plant: Users can add new plants to the list via a form.
Mark as Sold Out: Users can mark plants as sold out.
Persistent Data: The plant list is fetched from an API and updates to the list are reflected in the state.

## Installation
To get started, clone the repository and install the required dependencies.
Step 1: Clone the repository
Step 2: Install Dependencies
This project requires Node.js and npm (or yarn).
Step 3: Start the App
Ensure that the local API server (mock server) is running, as the app interacts with it. If you're using the mock server from json-server.

## API
This app interacts with a local mock API running on http://localhost:6001/plants.

Available Endpoints:
GET /plants: Fetches all plants in the store.
POST /plants: Adds a new plant to the store.
DELETE /plants/:id: Deletes a plant by its ID.
PATCH /plants/:id: Marks a plant as sold out by updating its status.

## Usage
Once the app is running, you will be able to:

View a list of plants with details like their name, price, and availability.
Add new plants: Use the form to add new plants, providing their name, image URL, and price.
Mark plants as "sold out": Clicking the "Sold Out" button will mark the plant as sold out, updating its status..

## Key UI Features
Plant List: A list of plants is displayed with options to mark as "sold out" or delete.
Add New Plant Form: A form to add new plants, including name, image URL, and price.

## Dependencies
The project uses the following libraries:

React: A JavaScript library for building user interfaces.
json-server (for mock API): A simple REST API for testing and prototyping.
useState & useEffect (React hooks): Used to manage the state of the app and perform side effects like fetching data.
Fetch API: For making network requests to the backend API.

## License

Copyright (c) 2024 Sarah Muthoni

This project is open source and available under the MIT License.

