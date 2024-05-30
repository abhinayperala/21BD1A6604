# Express.js Product API

This is an Express.js application that serves as an API for fetching products from a remote server. It allows retrieving products by category with pagination and searching for products by their IDs.

## Getting Started

To run the application locally, follow these steps:

1. Clone this repository to your local machine:

    ```bash
    git clone https://github.com/abhinayperala/21BD1A6604.git
    ```

2. Navigate to the project directory:

    ```bash
    cd express-product-api
    ```

3. Install the dependencies:

    ```bash
    npm install
    ```

4. Start the server:

    ```bash
    npm start
    ```

5. The server will start running on http://localhost:3000 by default.

## Authentication

Before using the API, you need to authenticate with the remote server to obtain an access token. The access token is required for fetching products. Authentication is performed automatically when the server starts.

#### Query Parameters

- `top` (optional): Number of products to retrieve (default is 10).
- `page` (optional): Page number for pagination (default is 1).
- `minPrice` (optional): Minimum price filter.
- `maxPrice` (optional): Maximum price filter.
- `sortBy` (optional): Field to sort by (default is "price").
- `sortOrder` (optional): Sort order, either "asc" or "desc" (default is "asc").
