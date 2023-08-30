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