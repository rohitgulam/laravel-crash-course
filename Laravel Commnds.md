### Used to run migration. 
php artisan migrate


### Used to run seeder
php artisan db:seed

### Refresh database (remove seeds)
php artisan migrate:refresh

### Refresh database then run seeder
php artisan migrate:refresh --seed

### Create a model
php artisan make:model Listing // name at the end

### Create a factory
php artisan make:factory ListingFactory // name at the end 