# Getting started with Laravel Mix for frontend development

Laravel Mix is a tool for compiling and optimizing assets in a Laravel app. It's similar to a build tool like gulp, Grunt and such like. it's specific to Laravel but can also be used externally as an npm package. Laravel Mix covered 80% of Webpack's use case to make compiling assets easier. In a nutshell, Laravel Mix compiles, minifies and stores your assets in your application's public folder for easy reference.

[View tutorial](#)

## Getting Started


Clone the project repository by running the command below if you use SSH

```
git clone git@github.com:samuelayo/laravel_mix_starter.git
```

If you use https, use this instead

```
git clone https://github.com/samuelayo/laravel_mix_starter.git
```

Change directory into the newly cloned project and install dependencies

```
cd laravel_mix_starter
composer install
npm install
```

Build the app

```
npm run build
```

Serve the laravel app

```
php artisan serve
```


## Built With

* [Laravel](https://laravel.com/) - The PHP Framework For Web Artisans.

