git clone https://github.com/Jayjace/laravelAndReactTableLeaveRequest.git
cd .\laravelAndReactTableLeaveRequest\
composer install 
cp .env.example .env 
go to .env file and put in your server username and password
php artisan key:generate 
php artisan migrate
php artisan db:seed
php artisan serve
cd .\react-datanova-requests\
npm install (if needed and must have node installed)
npm install
npm run start
