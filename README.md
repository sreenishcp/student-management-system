make sure you already have xampp or wampp installed.

First, install Composer in your system.
Clone this repository to your local machine or just download the zip from the above green button.
Then run 'composer install' command inside your project directory.

  
rename .env.example to .env and add your database credentials.

generate application key.

    php artisan key:generate
    
Create tables.

    php artisan migrate
Seed data into teachers table.

    php artisan db:seed
 
Start the development server.

    php artisan serve
