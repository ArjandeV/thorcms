Thor CMS
======
**QUICKSTART APPLICATION**

Thor CMS is a multipurpose Laravel 4 CMS platform and CRUD generator
for everyone and any kind of project, 
built with multilingual support from the core.

## Requirements
* PHP 5.4+
* Database connection (by default a sqlite file is used)

## Setup

Install the project using composer:

    composer create-project thor/thorcms your-project-name --prefer-dist --stability=dev

... or download or clone the source code and run `composer install` in the project folder

## Getting started

1. Run the `php artisan thor:setup` command (add `-n` for avoiding questions)
2. Go to the `/admin` URL and login with `developer` / `developer` or  `admin` / `admin`
