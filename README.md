# laravel-angular-integration
Laravel 8+Angular 11 Template for Development and Deployment

> A Laravel-Laravel starter project template.

## Features

- Laravel 8
- Angular 11
- Possible to use Laravel view && Angular View

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

Still on the Development, authentication, api crud example will be implemented soon