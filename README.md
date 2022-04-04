
# Warehouse Management System

This Warehouse Management System is built using the Laravel framework and provides a basic foundation for managing products in an inventory.

## Features

- User authentication with username and password
- View, add, edit, and delete products
- Basic styling using Bootstrap

## Prerequisites

Before you begin, ensure you have met the following requirements:

- PHP >= 7.4
- Composer installed
- Node.js and NPM installed (optional for styling)

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/md-shadhin-mia/ware-stock-central.git
   ```

2. Navigate to the project folder:

   ```bash
   cd ware-stock-central
   ```

3. Install PHP dependencies:

   ```bash
   composer install
   ```

4. Install NPM dependencies and build assets (optional for styling):

   ```bash
   npm install && npm run dev
   ```

5. Copy the `.env.example` file to `.env` and configure your database connection.

6. Generate the application key:

   ```bash
   php artisan key:generate
   ```

7. Run migrations:

   ```bash
   php artisan migrate
   ```

8. Serve the application:

   ```bash
   php artisan serve
   ```

Visit [http://127.0.0.1:8000](http://127.0.0.1:8000) in your browser.

## Usage

- Access the application and register a new user or use the default seeded user.
- Log in with your credentials.
- Navigate to the "Product List" to manage your inventory.

## Customization

Feel free to customize and extend the application based on your specific needs. Some areas you might want to consider:

- Adding more fields to the product model (e.g., category, description).
- Enhancing the user interface with additional styling and JavaScript interactions.
- Implementing additional features such as sales tracking, reporting, etc.

## Contributing

Contributions are welcome! Fork the repository, create a branch, make your changes, and submit a pull request.