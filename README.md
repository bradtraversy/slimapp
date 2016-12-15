# SlimApp RESTful API

This is a RESTful api built with the SlimPHP framework and uses MySQL for storage.

### Version
1.0.0

### Usage


### Installation

Create database or import from _sql/slimapp.sql

Edit db/config params

Install SlimPHP and dependencies

```sh
$ composer
```
### API Endpints
```sh
$ GET /api/customers
$ GET /api/customer/{id}
$ POST /api/customer/add
$ PUT /api/customer/update/{id}
$ DELETE /api/customer/delete/{id}
```
