# Task List Application

A simple and efficient task management application built with Laravel and Docker.

## Features

-   Create, read, update, and delete tasks
-   Docker-based development environment
-   MySQL database integration
-   Adminer for database management

## Prerequisites

-   Docker and Docker Compose
-   PHP 8.1 or higher
-   Composer
-   Node.js and NPM

## Installation

1. Clone the repository:

```bash
git clone [https://github.com/PositivWarrior/task-list]
cd task-list
```

2. Copy the environment file:

```bash
cp .env.example .env
```

3. Install PHP dependencies:

```bash
composer install
```

4. Install JavaScript dependencies:

```bash
npm install
```

5. Generate application key:

```bash
php artisan key:generate
```

6. Start the Docker containers:

```bash
docker-compose up -d
```

7. Run database migrations:

```bash
php artisan migrate
```

8. Start the development server:

```bash
php artisan serve
```

9. In a separate terminal, start the Vite development server:

```bash
npm run dev
```

## Accessing the Application

-   Main application: http://localhost:8000
-   Adminer (Database management): http://localhost:8080
    -   System: MySQL
    -   Server: mysql
    -   Username: root
    -   Password: root
    -   Database: laravel

## Development

The application uses the following technologies:

-   Laravel 10.x
-   MySQL/MariaDB
-   Docker
-   Vite for asset compilation

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
