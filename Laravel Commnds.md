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

### Create a controller
php artisan make:controller ListingController


## Naming Conventions
### Common Resource Routes:
- index - Show all listings
- show - Show single listing
- create - Show form to create new listing
- store - Store new listing 
- edit - Show form to edit listing
- update - Update listing
- destroy - Delete listing

## Publish packages so you can edit them
php artisan vendor:publish

## Create a link between public images and stored images so they can be accessed
php artisan storage:link