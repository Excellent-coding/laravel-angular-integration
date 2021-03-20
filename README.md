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

```bash
cd resources/ng
```

And this is angular environment, so all angular command works here

#### Production

```bash
npm run build:prod
```

## Issues

#### Angular environments

This is built for the localhost:4200(angular), localhost:8000(laravel)

If your laravel url is different(such as localhost), then change the environment.ts api url 

#### Build

If there are some files on the assets in angular directory, then please copy them and paste to pubilc/assets folder

#### OS issue

If you are using the windows system for the development, please edit the package.json like this.

@powershell
```bash
"build": "cd resources/ng && ng build --deploy-url /ng/ && @powershell cp ../../public/ng/index.html ../views/app.blade.php",
"build:prod": "cd resources/ng && ng build --prod --deploy-url /ng/ && @powershell copy ../../public/ng/index.html ../views/app.blade.php"
```

### Still on the Development, authentication, api crud example will be implemented soon