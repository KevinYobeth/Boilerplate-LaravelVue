<p align="center">
  <a href="https://laravel.com" target="_blank">
    <img height="200" src="https://raw.githubusercontent.com/laravel/art/master/laravel-logo.png">
  </a>
  <a href="https://vuejs.com" target="_blank">
    <img height="200" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/vue/vue.png">
  </a>
</p>

# About this boilerplate

This is a boilerplate for Laravel 8 + Vue JS 3, with additional Vue-Router for Single Page Application and Tailwind CSS installed. I created this boilerplate since it took ages to find the tutorial for combining Laravel 8 with Vue JS 3 since it is considered new to the community. Keep in mind that this boilerplate does not include authentication.

# Installation

## Clone Code & Installing Dependencies

### Clone Code From Repository

```
git clone https://github.com/KevinYobeth/Boilerplate-LaravelVue/
```

### Installing Dependencies

```
composer install
npm install
```

## Setting Up Project

### Configure

1. Copy `.env.example` to `.env` and edit database credentials
1. Run `php artisan key:generate` to generate key

### Migrate Database

```
php artisan migrate:fresh
```

### Running Server

```
php artisan serve
npm run watch
```

# License

You can basically do anything with this repository,
