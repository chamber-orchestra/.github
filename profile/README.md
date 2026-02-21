# Chamber Orchestra

A curated collection of lightweight, focused Symfony 8 bundles for PHP 8.5+ and Doctrine ORM 3. Each package solves one problem well and composes cleanly with the others — built for PostgreSQL-backed APIs and modern PHP applications.

## Packages

| Package | Description |
|---------|-------------|
| [**doctrine-extensions-bundle**](https://github.com/chamber-orchestra/doctrine-extensions-bundle) | UUID primary keys, soft-delete filter, boolean toggle, microsecond versioning, repository base classes with query caching, decimal DBAL type, and `random()` DQL function for PostgreSQL |
| [**doctrine-sort-bundle**](https://github.com/chamber-orchestra/doctrine-sort-bundle) | Automatic sort order management on flush — grouped ordering by parent or category, drag-and-drop repositioning, second-level cache eviction, and PHP attribute configuration |
| [**doctrine-slug-bundle**](https://github.com/chamber-orchestra/doctrine-slug-bundle) | SEO-friendly URL slug generation for Doctrine entities — declarative `#[Slug]` attribute, automatic collision resolution with numeric suffixes, and update-on-change support |
| [**doctrine-clock-bundle**](https://github.com/chamber-orchestra/doctrine-clock-bundle) | Automatic `created_at` / `updated_at` timestamps for Doctrine entities using Symfony Clock — `#[CreateTimestamp]` and `#[UpdateTimestamp]` attributes with microsecond precision support |
| [**metadata-bundle**](https://github.com/chamber-orchestra/metadata-bundle) | Attribute-driven entity metadata infrastructure — PSR-6 caching with in-memory layer, recursive embeddable resolution, autoconfigured mapping drivers, and multi-EntityManager support |
| [**form-bundle**](https://github.com/chamber-orchestra/form-bundle) | JSON-first REST API form handling — controller traits, query and mutation form types, data transformers, Doctrine uniqueness validation, and RFC 9457 Problem Details error responses |
| [**view-bundle**](https://github.com/chamber-orchestra/view-bundle) | Type-safe JSON API response layer — reflection-based property binding, collection mapping, null stripping, build-time metadata cache warming, and zero-downtime deployment support |
| [**image-bundle**](https://github.com/chamber-orchestra/image-bundle) | On-demand image resizing and format conversion with filesystem caching — filter pipelines, WebP/AVIF post-processors, HMAC-signed runtime URLs, and Twig template integration |
| [**pagination-bundle**](https://github.com/chamber-orchestra/pagination-bundle) | Offset and cursor-based (keyset) pagination for Doctrine ORM — array, repository, and QueryBuilder support, ULID cursor resolution, numbered page ranges, and Twig templates |
| [**meta-bundle**](https://github.com/chamber-orchestra/meta-bundle) | SEO metadata trait for Doctrine entities — meta title, description, keywords, Open Graph image, and robots directives (`index`/`noindex`) stored as entity columns with template-ready output |
| [**breadcrumbs**](https://github.com/chamber-orchestra/breadcrumbs) | Lightweight breadcrumb navigation builder — iterable collection with ArrayAccess, route-aware link rendering, request-based extraction, and native Twig template compatibility |

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
