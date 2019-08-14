## School Management System
This is school management system web application and it's open source.

## Installation Process
- Clone the repo.
- copy the .env.example file to .env `@php -r \"file_exists('.env') || copy('.env.example', '.env');`
- Generate a new key `@php artisan key:generate --ansi`
- Connect to a database by edit the .env file
- Create the table and user `@php artisan migrate --seed`



## External Packages

- 

## Security Vulnerabilities

If you discover a security vulnerability within Laravel, please send an e-mail to Rakesh Mistri via [rakeshmistry3899@gmail.com](mailto:taylor@laravel.com). All security vulnerabilities will be promptly addressed.

## License

The Laravel framework is open-source software licensed under the [MIT license](https://opensource.org/licenses/MIT).
