# Laravel Filament Modular

## Introduction

The Filament module package is a Laravel package that integrates with the popular nwidart/laravel-modules package to provide seamless integration with Filament, a modern and elegant admin panel for Laravel applications.

Filament module package simplifies the process of integrating Filament into your Laravel application by providing a set of pre-built modules that can be easily installed and configured.

## Installation

Require this package with composer.

```shell
composer require realmrhex/filament-modular
```

Laravel uses Package Auto-Discovery, so doesn't require you to manually add the ServiceProvider.

#### Copy the package config to your local config with the publish command:

```shell
php artisan vendor:publish --provider="RealMrHex\FilamentModular\FilamentModularServiceProvider"
```
