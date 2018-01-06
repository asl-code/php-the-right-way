---
anchor: components
isChild: true
---

## Components {#components}

As mentioned above "Components" are another approach to the common goal of creating, distributing and implementing shared code. Various
component repositories exist, the main two of which are:

* [Packagist](/#composer_and_packagist)
* [PEAR](/#pear)

Both of these repositories have command line tools associated with them to help the installation and upgrade processes, and have been
explained in more detail in the [Dependency Management][dm] section.

There are also component-based frameworks, which allow you to use their components with minimal (or no) requirements. For example, you
can use the [FuelPHP Validation package][fuelval], without needing to use the FuelPHP framework itself. These projects are essentially
just another repository for reusable components:

  [dm]: /#dependency_management
  [fuelval]: https://github.com/fuelphp/validation

* [Aura](http://auraphp.github.com/)
* [FuelPHP](https://github.com/fuelphp)
* [Symfony Components](http://symfony.com/doc/current/components/index.html)
* [The League of Extraordinary Packages](http://thephpleague.com/)
* Laravel's Illuminate Components
    * [Eloquent ORM](https://github.com/illuminate/database)
    * [Queue](https://github.com/illuminate/queue)

_Laravel's [Illuminate components](https://github.com/illuminate) will become better decoupled from the Laravel framework.
For now, only the components best decoupled from the Laravel framework are listed above._
