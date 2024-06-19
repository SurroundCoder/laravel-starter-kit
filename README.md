# Laravel Starter Kit

This repository provides a starter kit for Laravel 11, pre-configured with the AdminLTE template to help you get started faster with building your Laravel applications.

## Features

- Laravel 11
- AdminLTE integrated for a clean and responsive admin interface

## Requirements

- PHP 8.1 or higher
- Composer
- Node.js and npm (for asset compilation)

## Installation

Follow these steps to get started with the Laravel Starter Kit:

1. **Clone the repository:**

    ```sh
    git clone https://github.com/SurroundCoder/laravel-starter-kit.git
    cd laravel-starter-kit
    ```

2. **Install Composer dependencies:**

    ```sh
    composer install
    ```

3. **Copy the `.env.dist` file to `.env` and set your environment variables:**

    ```sh
    cp .env.dist .env
    php artisan key:generate
    ```

4. **Set up the database:**

    Configure your database settings in the `.env` file and run the migrations:

    ```sh
    php artisan migrate
    ```

6. **Serve the application:**

    ```sh
    php artisan serve
    ```

7. **Access the application:**

    Open your browser and go to `http://localhost:8000`