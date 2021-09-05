# PHP Boilerplate

A boilerplate for help with new composer based PHP projects.

## Getting started

Using git
```bash
$ git clone git@github.com:paulovictordev/php-boilerplate.git new-project-php && cd $_ && rm -rf .git && git init
```

Then update composer
```bash
$ composer update
```

Replace the namespaces in the `autoload` and `autoload-dev` sections with your project's namespaces inside `composer.json`
and run:
```bash
$ composer dump-autoload
```

## Tools
