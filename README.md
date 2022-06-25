1.
Run cp .env.example .env command to copy example into real .env file, then edit it with DB credentials and other settings you want
2.
Run composer install command
3.
Run php artisan migrate --seed command. Seed is important, because it will create the first admin user for you.
4.
Run php artisan key:generate command
5.
If you have file/photo upload fields, run php artisan storage:link command
6.
And that's it, go to your domain and login with these credentials: admin@admin.com - password
