Finally, you need to perform a set of Laravel-related commands in Terminal to install the project. These commands are typical to ANY Laravel project, and are not specific - we are trying to stick to standards.

1. Run cp .env.example .env command to copy example into real .env file, then edit it with DB credentials and other settings you want
2. Run composer install command
3. Run php artisan migrate --seed command. Seed is important, because it will create the first admin user for you.
4. Run php artisan key:generate command
5. If you have file/photo upload fields, run php artisan storage:link command
6. Register account
