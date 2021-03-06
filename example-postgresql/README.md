# Compose Grand Tour - Node.js - PostgreSQL

This Compose Grand Tour application shows you how to connect to a PostgreSQL deployment using Node.js.

## Build notes

1. Install Node.js, using Homebrew:

    ```
    brew install node
    ```

2. Install Node.js modules specified in manifest.yml:

    ```
    npm install
    ```

## Run notes

Set the `COMPOSE_PostgreSQL_URL` environment variable to the Compose connection string for the PostgreSQL database. Remember to create a user for PostgreSQL and include that user's credentials in the URL.

To run the application:

1. `node server`
2. Open a browser tab and navigate to `http://localhost:8080`


