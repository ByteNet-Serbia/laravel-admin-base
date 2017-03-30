# Change Log

All Notable changes to `bytenet\laravel-admin-base` project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/) and this project adheres to [Semantic Versioning](http://semver.org/).

## [Unreleased]
### Added
### Changed
### Deprecated
### Removed
### Fixed
### Security

## [0.1.2] - 2017-03-31
### Added
- Changed functionalities for Laravel 5.3
- AdminLTE support
- Make proper migrate files
- some files makeup (Code Sniffer etc.)
- src\app\Http\Controllers\Auth\ForgotPasswordController.php
- src\app\Http\Controllers\Auth\LoginController.php
- src\app\Http\Controllers\Auth\RegisterController.php
- src\app\Http\Middleware\ByteNetAuthenticate.php
- src\app\Http\Notifications\ResetPasswordNotification.php
- src\database\migrations\2016_12_21_235914_alter_users_table.php
- src\database\migrations\2016_12_22_001533_alter_password_reset_table.php
- src/database/seeds/UsersTableSeeder.php
- src\resources\lang\es\base.php
- src\resources\lang\sr_Latn_RS\base.php
- src\resources\view\inc\sidebar_control.blade.php
- src\routes\web.php

### Changed
- CHANGELOG.md
- composer.json
- LICENSE.md
- README.md
- src\app\Http\Controllers\AdminController.php
- src\BaseServiceProvider.php
- src\config\bytenet\base.php
- src\resources\lang\en\base.php
- src\resources\lang\fr\base.php
- src\resources\lang\it\base.php
- src\resources\lang\ro\base.php
- src\resources\view\auth\login.blade.php
- src\resources\view\auth\passwords\email.blade.php
- src\resources\view\auth\passwords\reset.blade.php
- src\resources\view\auth\register.blade.php
- src\resources\view\dashboard.blade.php
- src\resources\view\inc\alerts.blade.php
- src\resources\view\inc\menu.blade.php
- src\resources\view\inc\sidebar.blade.php
- src\resources\view\layout.blade.php
- tests\.env
- tests\app.php
- tests\bootstrap.php
- tests\ByteNet\LaravelAdminBase\BaseTest.php
- tests\ByteNet\LaravelAdminBase\Test\ConfigTest.php
- tests\database.php

### Removed
- .editorconfig
- .gitignore
- .travis.yml
- phpunit.xml
- src\app\Http\Controllers\Auth\AuthController.php
- src\app\Http\Controllers\Auth\PasswordController.php
- src\app\Http\Middleware\AuthenticateByteNet.php
- src\resources\view\auth\emails\password.blade.php

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
