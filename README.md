Graphiql for laravel
====================

This package provides an easy way to include the [graphiql ui](https://github.com/graphql/graphiql) with your laravel project.

Installation
============

Open your `config/app.php` and add this line in `providers` section
```php
    Graphiql\GraphiqlServiceProvider::class
```

Then run `artisan graphiql:publish` to publish everything

