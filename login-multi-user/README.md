This repository contains a Laravel project that can be used as a starting point for web development. Below are the instructions to get started.

Getting Started
Prerequisites
PHP >= 7.4
Composer
Installation

## Clone the repository or download the source code as a ZIP file:

* `git clone https://github.com/ricotaffarel/laravel.git`.

## Install dependencies:
`composer install`.

## Create a copy of the .env.example file and rename it to .env:
`cp .env.example .env`.

## Edit the .env file with your database credentials:
* `DB_DATABASE=your_database_name`.
* `DB_USERNAME=your_database_username`.
* `DB_PASSWORD=your_database_password`.

## Generate a new application key:
`php artisan key:generate`.

## Run database migrations:
`php artisan migrate`.

## Run database seeders:
`php artisan db:seed`.

## Start the development server:
`php artisan serve`.