# Benchmarks for Laravel

> This is currently experimental. Proceed with caution.

After some recent work, I realised that the process of benchmarking and contributing to Laravel could be made easier. This project aims to do that, by providing repeatable benchmark scenarios for Laravel, and tools with which to build and share benchmarks and benchmark results.

To get started:

```bash
git clone git@github.com:benchmarks-for-laravel/application.git benchmarks-for-laravel-application
git clone git@github.com:benchmarks-for-laravel/toolbox.git benchmarks-for-laravel-toolbox
git clone git@github.com:benchmarks-for-laravel/views.git  benchmarks-for-laravel-views
cd benchmarks-for-laravel-application
composer install
php artisan benchmarks-for-laravel:run-benchmark
```

![Demo](https://github.com/benchmarks-for-laravel/application/blob/cdc03baaef0f123439ae16153b8681c19488d52b/demo.gif)
