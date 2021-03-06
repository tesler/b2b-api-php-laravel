# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog] and this project adheres to [Semantic Versioning].

## v2.5.1

### Changed

- Maximal `phpunit` version now is `7.4.x`. Reason - since `7.5.0` frameworks contains assertions like `assertIsString`, `assertIsArray` and others, already declared in class `AbstractUnitTestCase`

## v2.5.0

### Changed

- Maximal PHP version now is undefined
- Maximal Laravel version now is `5.7.*`
- CI changed to [Travis CI][travis]
- [CodeCov][codecov] integrated

[travis]:https://travis-ci.org/
[codecov]:https://codecov.io/

## v2.4.0

### Fixed

- Return type of `webhook` option has type object [#6]

[#6]: https://github.com/avto-dev/b2b-api-php-laravel/issues/6

## v2.3.0

### Added

- Config settings for manage web-hooks

## v2.2.0

### Added

- `is_force` flag to `makeReport` method [#2]

### Changed

- Issues & PR templates
- Update requirement avto-dev/b2b-api-php to version `2.3.0`

[#2]: https://github.com/avto-dev/b2b-api-php-laravel/issues/2

## v2.1.0

### Changed

- CI config updated
- Required minimal PHPUnit version now `5.7.10`
- Required minimal Laravel version now `5.4.3`
- Disabled HTML coverage report (CI errors)
- Unimportant PHPDoc blocks removed

[Keep a Changelog]: http://keepachangelog.com/en/1.0.0/
[Semantic Versioning]: http://semver.org/spec/v2.0.0.html
