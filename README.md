# Product API

## Setup Instructions

1. Clone the repository:
    ```bash
    git clone <repository_url>
    cd product-api
    ```

2. Install dependencies:
    ```bash
    npm install
    ```

3. Create a `.env` file in the root directory and set the `MONGO_URI` and `PORT` variables:
    ```env
    MONGO_URI=mongodb://localhost:27017/product-api
    PORT=3333
    ```

4. Start the server:
    ```bash
    node app.js
    ```

5. The API will be running on `http://localhost:3333`.

## API Endpoints

- `POST /http://localhost:3333/products`: Create a new product.
- `GET /http://localhost:3333/products`: Fetch all products.
- `PUT /http://localhost:3333/products/:id`: Update a product by ID.
- `DELETE /http://localhost:3333/products/:id`: Delete a product by ID.
