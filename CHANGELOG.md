# Rinvex Bookings Change Log

All notable changes to this project will be documented in this file.

This project adheres to [Semantic Versioning](CONTRIBUTING.md).


## [v0.0.4] - 2018-09-29
- Abandon the package in favor to rinvex/laravel-bookings

## [v0.0.3] - 2018-09-22
- Update travis php versions
- Define polymorphic relationship parameters explicitly
- Rename booking polymorphic relation "user" to "customer"
- Fix fully qualified booking unit methods
- Move Bookable abstract model from the module cortex/bookings
- Fix few readme typos
- Tweak few things
- Change bookable price to base cost and unit cost
- Refactor bookable fields
- Refactor rates, availabilities and add bookable addons
- Enforce naming conventions consistency
- Delete bookings on bookable resource or resource owner deletion
- Refactor bookings!
- Tweak validation rules
- Apply few tweaks
- Drop StyleCI multi-language support (paid feature now!)
- Update composer dependencies
- Prepare and tweak testing configuration
- Drop service addons for now
- Rename cancelled_at to canceled_at
- Add actual_paid field to bookings
- Update bookable rates and availability database structure
- Fix wrong range values
- Refactor and simplify booking price calculation
- Refactor booking attributes
- Update StyleCI options
- Add quantity field, rename actual_paid to total_paid and "use" unit
- Fix wrong db table name
- Update PHPUnit options
- Rename model activation and deactivation methods

## [v0.0.2] - 2018-02-18
- Update supplementary files
- Update composer depedencies
- Major refactor for simplicity & flexibility
- Radical refactor for better pricing features & enforced consistency
- Rewrite price calculation, relationships, booking functionality & enforce consistency
- Make "between" scopes inclusive
- Add start/end between scope
- Rename `between` scope to `range` and include full day events in query results
- Require booking start & end dates
- Add Rollback Console Command
- Add PHPUnitPrettyResultPrinter
- Use Carbon global helper
- Typehint method returns
- Drop useless model contracts (models already swappable through IoC)
- Add Laravel v5.6 support
- Simplify IoC binding
- Fix wrong database table names
- Add force option to artisan commands
- Define abstract morphMany method on trait
- Rename BookingsCustomer trait to HasBookings
- Rename polymorphic relation customer to user
- Drop Laravel 5.5 support
- Convert unit column data type into string from character

## v0.0.1 - 2017-09-08
- Tag first release

[v0.0.4]: https://github.com/rinvex/bookings/compare/v0.0.3...v0.0.4
[v0.0.3]: https://github.com/rinvex/bookings/compare/v0.0.2...v0.0.3
[v0.0.2]: https://github.com/rinvex/bookings/compare/v0.0.1...v0.0.2
