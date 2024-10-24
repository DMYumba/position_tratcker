# position_tratcker

## Overview
This app tracks a user's location (latitude and longitude) using the browser's Geolocation API and stores the data in a Laravel-based backend every 20 seconds.

## Technology Stack
- Laravel 10 (Backend)
- React (Frontend)

## Setup Instructions

1. Clone the repository.
2. Install Laravel dependencies:

## Composer install


3. Create a database position_tracker
4. Import import database file position_tracker.sql 

5. Install React dependencies:
npm install

6. Set up .env for Laravel, including database connection.
7. Run migrations:
php artisan migrate

8. Start the backend server:
php artisan serve

9. Start the frontend React server:
npm start

## API Endpoints
- POST /position - Receives latitude and longitude and stores the position in the database.
