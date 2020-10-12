## Laravel Starter (Current: Laravel 6.*) ([Demo](http://134.209.123.206/))

[![Latest Stable Version](https://poser.pugx.org/rappasoft/laravel-boilerplate/v/stable)](https://packagist.org/packages/rappasoft/laravel-boilerplate)
[![Latest Unstable Version](https://poser.pugx.org/rappasoft/laravel-boilerplate/v/unstable)](https://packagist.org/packages/rappasoft/laravel-boilerplate) 
<br/>
[![StyleCI](https://styleci.io/repos/30171828/shield?style=plastic)](https://github.styleci.io/repos/30171828)
<br/>
![GitHub contributors](https://img.shields.io/github/contributors/rappasoft/laravel-boilerplate.svg)
![GitHub stars](https://img.shields.io/github/stars/rappasoft/laravel-boilerplate.svg?style=social)

### Introduction

Laravel Starter provides you with a massive head start on any size web application. It comes with a full featured access control system out of the box with an easy to learn API and is built on a Bootstrap foundation with a front and backend architecture. We have put a lot of work into it and we hope it serves you well and saves you time!

MIT: [http://anthony.mit-license.org](http://anthony.mit-license.org)

### Setup
Clone the repo and follow below steps.
1. Run `composer install`
2. Copy `.env.example` to `.env` Example for linux users : `cp .env.example .env`
3. Set valid database credentials of env variables `DB_DATABASE`, `DB_USERNAME`, and `DB_PASSWORD`
4. Run `php artisan key:generate` to generate application key
5. Run `php artisan migrate`
6. Run `php artisan passport:install`
7. Run `php artisan db:seed` to seed your database
7. Run `npm i` (Recommended node version `>= V10.0`)
8. Run `npm run dev` or `npm run prod` as per your environment

Thats it... Run the command `php artisan serve` and cheers, you are good to go with your new **Laravel Starter** application.

The application uses [GrumPHP](https://github.com/phpro/grumphp) for the git pre-commit hook and [PHPCSFixer](https://github.com/FriendsOfPHP/PHP-CS-Fixer) for the code standards. You can also bypass the `GrumPHP` pre-commit hook by hitting `git commit -n` or `git commit --no-verify`

### Demo Credentials

Make sure you have run the command `php artisan db:seed --class UserTableSeeder` before you use these credentials.

**User:** admin@admin.com\
**Password:** 1234

**User:** executive@executive.com\
**Password:** 1234

**User:** user@user.com\
**Password:** 1234