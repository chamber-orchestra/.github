# Chamber Orchestra

A curated collection of lightweight, focused Symfony 8 bundles for PHP 8.5+. Each package solves one problem well and composes cleanly with the others.

## Packages

| Package | Description |
|---------|-------------|
| [**doctrine-extensions-bundle**](https://github.com/chamber-orchestra/doctrine-extensions-bundle) | Entity traits, soft-delete filter, repository base classes, decimal DBAL type, `random()` DQL function for PostgreSQL |
| [**doctrine-sort-bundle**](https://github.com/chamber-orchestra/doctrine-sort-bundle) | Automatic sort order management with grouped ordering, second-level cache support, and PHP attribute configuration |
| [**doctrine-slug-bundle**](https://github.com/chamber-orchestra/doctrine-slug-bundle) | Unique, URL-friendly slug generation for Doctrine entities with collision resolution |
| [**doctrine-clock-bundle**](https://github.com/chamber-orchestra/doctrine-clock-bundle) | Clock integration for Doctrine ORM |
| [**metadata-bundle**](https://github.com/chamber-orchestra/metadata-bundle) | Attribute-driven entity metadata with cacheable mapping, embedded entity support, and autoconfigured drivers |
| [**form-bundle**](https://github.com/chamber-orchestra/form-bundle) | JSON-first API form handling — controller traits, API form types, data transformers, and RFC 9457 error responses |
| [**view-bundle**](https://github.com/chamber-orchestra/view-bundle) | Typed view layer for JSON API responses — property binding, collection mapping, null stripping, and build-time cache warming |
| [**image-bundle**](https://github.com/chamber-orchestra/image-bundle) | Image handling for Symfony applications |
| [**pagination-bundle**](https://github.com/chamber-orchestra/pagination-bundle) | Pagination for Symfony applications |
| [**meta-bundle**](https://github.com/chamber-orchestra/meta-bundle) | HTML meta tag management for Symfony |
| [**breadcrumbs**](https://github.com/chamber-orchestra/breadcrumbs) | Iterable breadcrumb collection implementing ArrayAccess, IteratorAggregate, and Countable |

## Stack

- **PHP** ^8.5
- **Symfony** ^8.0
- **Doctrine ORM** 3
- **PHPStan** level max
- **Code style** PER-CS + Symfony (PHP-CS-Fixer)

## Installation

All packages are available on [Packagist](https://packagist.org/?query=chamber-orchestra):

```bash
composer require chamber-orchestra/<package-name>
```

## License

All packages are released under the [MIT License](https://opensource.org/licenses/MIT).
