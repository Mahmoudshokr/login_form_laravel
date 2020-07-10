1. Clone GitHub repo for this project locally
If the project is hosted on github, we can use git on your local computer to clone it from github onto your local computer.


2. cd into your project


3. Install Composer Dependencies
composer install

4. Install NPM Dependencies
npm install

5. Create a copy of your .env file
cp .env.example .env
This will create a copy of the .env.example file in your project and name the copy simply .env.

6. Generate an app encryption key
php artisan key:generate
7.
Create an empty database for our application

8. In the .env file, add database information to allow Laravel to connect to the database

9. Migrate the database
Once your credentials are in the .env file, now you can migrate your database.

php artisan migrate
