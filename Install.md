composer require laravel/sail --dev
php artisan sail:install
./vendor/bin/sail down
./vendor/bin/sail up -d
./vendor/bin/sail artisan:migrate
./vendor/bin/sail artisan project:init
npm install
npm run build
