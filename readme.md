# Lavalite

![Build Status](https://travis-ci.org/LavaLite/cms.svg?branch=5.7)
![StyleCI](https://github.styleci.io/repos/18992087/shield?branch=5.7)
![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)

This is an open source of Content Management System developed with [Laravel](http://laravel.com/) framework.

![Screen](https://raw.githubusercontent.com/LavaLite/docs/master/images/lavalite.png "Dashboards")

## Documentation
Visit [Documentation](http://lavalite.org/docs) section in the website

## System Requirements & Installation
Visit [Installation](http://lavalite.org/docs/master/installation) section in the documentation for the details


## Demo
Content Management System [https://lavalite.org/demo.html](https://lavalite.org/demo.html)

Products [https://lavalite.org/products.html](https://lavalite.org/products)


## License

The Lavalite CMS is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT).

## Run

Install vendor and gen key:

```bash
docker-compose exec app composer update
docker-compose exec app php artisan key:generate
```

Run migrate and seeder:

```bash
docker-compose exec app php artisan migrate
docker-compose exec app php artisan db:seed
```

Access to `localhost:8005/admin` and enter username/email is `admin@lavalite.org` and password is `admin@lavalite` to login to admin dashboard.