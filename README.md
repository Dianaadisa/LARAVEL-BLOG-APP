Laravel Blog App

A multi-user blog application I built while learning Laravel. It allows users to register, log in, create posts (called "chirps"), edit them, and delete them — with proper authentication and authorization to make sure users can only manage their own content.

 Features

* User registration and login
* Authentication with Laravel Auth and "Remember Me" option
* Create, edit and delete chirps
* Users can only edit or delete their own posts
* Protected routes using middleware
* Responsive UI with TailwindCSS and DaisyUI
* Session handling and CSRF protection
* Flash messages and validation errors

 Technologies Used

* PHP
* Laravel
* Blade Templates
* MySQL
* TailwindCSS
* DaisyUI

 Installation

Clone the repository:

bash
git clone https://github.com/Dianaadisa/LARAVEL-BLOG-APP.git


Move into the project folder:

bash
cd LARAVEL-BLOG-APP


Install dependencies:

bash
composer install
npm install


Create environment file:

bash
cp .env.example .env


Generate application key:

bash
php artisan key:generate


Run migrations:

bash
php artisan migrate


Start the development servers:

bash
php artisan serve
npm run dev


Visit:

plaintext
http://127.0.0.1:8000


 Authentication

Users can register, log in and log out securely. Routes are protected using middleware and Laravel Policies ensure users can only edit or delete their own chirps.

Things I'd Like to Add

* Comments and reactions
* Image uploads
* User profiles
* REST API with Laravel Sanctum
* Admin dashboard

 Author

Built by [Diana Adisa](https://github.com/Dianaadisa) as part of my learning journey with [Laravel](https://laravel.com)

