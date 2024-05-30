HOW TO LAUNCH?
(Basic understanding of php and object oreiented programming is needed)
(There is also an alternative installation procedure after thr first one)

Make sure you have the composer dependency installed.
Install nodejs including npm.
You can also install a version control system like git.

Copy all the files inside a folder and launch the folder using your IDE
Open your terminal and run "npm install"
You can launch your npm in production mode (npm run build) or development mode (npm run dev).

Run the command "php artisan serve" in your terminal to start the server
Navigate on your browser using localhost:8000/register to create a new account

Confirm your e-mail address using the instructions in your laravel.log file (found in project folder)

VOILA, START WORKING ON SOME NEW NOTES!!

Feel free to ask me some questions or query if there is an error.


Alternative Installation 


Installation
Clone the project
Navigate to the project's root directory using terminal
Create .env file - cp .env.example .env
Execute composer install
Execute npm install
Set application key - php artisan key:generate --ansi
Execute migrations and seed data - php artisan migrate --seed
Start vite server - npm run dev
Start Artisan server - php artisan serve
