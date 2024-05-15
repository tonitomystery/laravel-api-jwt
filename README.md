# Example commands

php artisan make:model Flight --m

[ok] php artisan make:model Photo -mc --api

php artisan make:controller PhotoController --api

php artisan make:model Task -mcrR --api


# MIGRATION
php artisan migrate
php artisan migrate:rollback --step=1



php artisan make:request StoreStudyRequest
php artisan make:request StoreInstitutionRequest
php artisan make:request StoreInstanceRequest


php artisan make:model ShardPartition -mc --api

# SEEDER
php artisan db:seed --class=DatabaseSeeder
php artisan make:seeder StudiesTableSeeder


# RESOURCES
php artisan make:resource InstitutionResource


# MIDDLEWARE
php artisan make:middleware ForceJsonResponse


# POLICY
php artisan make:policy RolePolicy --model=Role

https://github.com/emad-zaamout/laravel-docker-aws-deployment-course-start


php artisan l5-swagger:generate


http://localhost/dicom-lara11/public/api/documentation#/




php artisan make:model Institution -mc --api



php artisan make:middleware ApiKey








php artisan make:request LicenseRegisterRequest





php artisan make:controller WorkController --api