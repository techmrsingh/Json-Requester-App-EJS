# JSON Requester App

A simple web application that allows users to craft JSON requests and view responses.

## Features

- Dummy Values Dropdown: Provides predefined JSON payloads.
- Version Dropdown: Allows users to select different versions of the payload.
- HTTP Method Selector: Enables users to choose different HTTP methods (GET, POST, PUT, DELETE, PATCH).
- Endpoint URL Input: Users can specify the API endpoint they wish to send the request to.
- Environment Selector: Choose between different environments like Production, Staging, and Development. Each environment has a specific endpoint URL.
- Headers Textarea: Users can define headers for their request in a `key:value` format.
- JSON Request Textarea: Displays the selected payload and allows for manual editing.
- Send Request Button: Sends the crafted request to the specified endpoint.
- JSON Response Textarea: Displays the response from the server.

## Setup

1. **Prerequisites**:
   - Ensure you have [Node.js](https://nodejs.org/) installed.

2. **Installation**:
   ```bash
   git clone https://github.com/your-username/json-requester-app.git
   cd json-requester-app
   npm install

## Running the Application:

bash
Copy code
node server.js
Navigate to http://localhost:3000 in your web browser.

##  Dependencies
Express: For serving the application.
EJS: As the templating engine.
Axios: For making HTTP requests.
Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

##  License
MIT