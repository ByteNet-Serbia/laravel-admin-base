# Change Log

All Notable changes to `bytenet\laravel-admin-base` project will be documented in this file.


The format is based on [Keep a Changelog](http://keepachangelog.com/) and this project adheres to [Semantic Versioning](http://semver.org/).

## [0.1.2] - 2017-03-31
### Added
- Changed functionalities for Laravel 5.3
- AdminLTE support
- Make proper migrate files
- some files makeup (Code Sniffer etc.)
- .editorconfig
- .gitignore
- .travis.yml
- phpunit.xml
- src\app\Http\Controllers\Auth\AuthController.php
- src\app\Http\Controllers\Auth\ForgotPasswordController.php
- src\app\Http\Controllers\Auth\LoginController.php
- src\app\Http\Controllers\Auth\PasswordController.php
- src\app\Http\Controllers\Auth\RegisterController.php
- src\app\Http\Middleware\AuthenticateByteNet.php
- src\app\Http\Middleware\ByteNetAuthenticate.php
- src\app\Http\Notifications\ResetPasswordNotification.php


- src/BaseServiceProvider.php

- src/database/seeds/UsersTableSeeder.php

### Changed
- CHANGELOG.md
- composer.json
- LICENSE.md
- README.md
- src\app\Http\Controllers\AdminController.php

### Fixed
- Some cosmetic changes

## [0.1.1] - 2016-08-30
### Added
- Laravel workbench for Travis CI

## [0.1.0] - 2016-08-19
### Added
- Changed password functionalities

## 0.0.1 - 2016-08-19
### Added
- Moved all test controllers, views, config file, lang file for Laravel authentication into the package. Loading the package will allow the user to make use of Backpack authentication, instead of Laravel's default.

[0.1.2]: https://github.com/ByteNet-Serbia/laravel-admin-base/compare/v0.1.1...v0.1.2
[0.1.1]: https://github.com/ByteNet-Serbia/laravel-admin-base/compare/v0.1.0...v0.1.1
[0.1.0]: https://github.com/ByteNet-Serbia/laravel-admin-base/compare/v0.0.1...v0.1.0
