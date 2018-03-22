## Installation instructions
1. Clone the repo via this url `git@github.com:vickris/lara-social-new.git`
2. Get inside the project folder `cd lara-social-new`
3. Create a `.env` file by running the following command `cp .env.example .env`
4. Install various packages and dependencies: `composer install`
5. Run migrations then seed the database:
    ```bash
    php artisan migrate
    ```
6. Generate an encryption key for the app: `php artisan key:generate`.
