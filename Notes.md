# realestate
//create project
1. composer create-project laravel/laravel realestate 
  
2. install breed
3. update users migration file

//create a seeder
4. php artisan make:seeder UsersTableSeeder 

5. update seeder file 

6.update UserFactory.php

7.update DatabaseSeeder.php

//drop old database if have migrated,and rebuild database with seeder
8.php artisan migrate:fresh --seed

//make contorller
9.php artisan make:controller AdminController

10.update the app/Http/Controllers/Auth/AuthenticatedSessionController.php
trying to do the multi authentication.

// now need to protect the url by creating a new middleware
11.php artisan make:middleware Role

12. also register the new middleware in kernel.php.

13. update web.php with middleware