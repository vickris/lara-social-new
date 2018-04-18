## Installation instructions
1. Clone the repo via this url `git@github.com:vickris/lara-social-new.git`
2. Get inside the project folder `cd lara-social-new`
3. Create a `.env` file by running the following command `cp .env.example .env`
4. Install various packages and dependencies: `composer install`. **Note:** you have to be in side your Laravel development environment for this to work. For those using vagrant, make sure you `ssh` into Vagrant before running `composer install`
5. Run migrations then seed the database:
    ```bash
    php artisan migrate
    ```
6. Generate an encryption key for the app: `php artisan key:generate`.
7. You are now good to go.
