# E-Commerce

This is a backend for an e-commerce site using Express.js and Sequelize. The app connects to a PostgreSQL database and provides API routes for managing categories, products, and tags.

## Getting Started

### Setup

1. Clone the repository.
2. Install the required dependencies:

   ```bash
   npm install
    ```
3. Create an .env file in the root directory with the following information:
    ```bash
    DB_NAME=your_db_name
    DB_USER=your_postgres_username
    DB_PASSWORD=your_postgres_password
    ```
### Database
1. Create the development database schema by running the following command:

    ```bash
    npm run schema
    ```

2. Seed the database with test data:
    ```bash
    npm run seed
    ```

### Running the Application
To start the server and sync Sequelize models with the PostgreSQL database, run:

```bash
npm start
```

### Testing API Routes
Use Insomnia to test the API routes.

GET routes: Fetch data for categories, products, or tags in a formatted JSON response.
POST, PUT, DELETE routes: Manage the database by creating, updating, or deleting entries through these routes.