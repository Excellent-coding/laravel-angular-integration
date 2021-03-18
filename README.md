# laravel-angular-integration
Laravel 8+Angular 11 Template for Development and Deployment

## Features

- Laravel 8
- Angular 11

## Installation
- git clone or download, run `composer install`
- run `php artisan key:generate`
- put your info in .env file
- run `npm install`

## Usage

#### Development

```bash
# run angular
npm start

# angular build && integrate into laravel
npm run build

#angular create new component, new service, new module...
npm run create g c home
npm run create g s api
```

Or you can work on the angular directory
cd resources/ng
And this is angular environment, so all angular command works here

#### Production

```bash
npm run build:prod
```

