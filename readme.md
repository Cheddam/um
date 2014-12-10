# um
### user manager

um is a simplistic take on a PHP framework. It provides only a handful of features out of the box:

- User authentication / management
- Basic permission system
- Single, customisable template
- Router to enable all of the above

Functionality is expected to be added through modules that extend um's base. They should follow module guidelines:

- All requests must be received and delivered in JSON
- Permissions must be namespaced
- Code must abide by PSR-1, PSR-2 and PSR-4

The anticipated target/result of the structure and guidelines of um is a fast and simple single page web app that can do practically anything. It is possible to circumvent the guidelines and build a traditional website with um, but at that point you're probably better off with a bigger, badder framework like [Laravel](http://laravel.com).

## Why even

I am building this to make it straight-forward for me to tinker with API models, [Redis](http://redis.io) [Angular](http://angularjs.org), and [Foundation for Apps](http://foundation.zurb.com/apps), among other tools and patterns.

## When even

I plan to have an initial release up soon&trade;. I will flesh out the documentation (read: actually document the thing) during development.