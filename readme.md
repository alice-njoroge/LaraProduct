# LaraProducts
This is a simple project on laravel 5.5.  
The projects is a simple crud apps dealing with stock product management 

## How to run the project
1. Clone the project
2. `cd` into the project
3. run `composer install`
4. copy the environment variables if does not exists, `cp .env.example .env`
5. Create a mysql database and update `.env` accordingly
6. Migrate the database `php artisan migrate`  
7. Run the project  `php artisan serve`