# Change log

All notable changes to this project will be documented in this file.

## v1.2.2 - (2021-06-01)

### Fixed

- Migrate to database command removed.
- Publishable asset `assets` avatar config issue.
- Pusher encryption key option removed.
- Settings button on click not working issue.

## v1.2.1 - (2021-05-30)

### Fixed

- Publishable asset `assets`.

## v1.2.0 - (2021-05-30)

### FIxed

- Security issues.
- UI/UX issues.
- Route [home] not defiend.
- `$msg->attachment` issue #9.
- Delete conversation issue #89.

### Added

- Console commands.
- `Models` added to assets to be published.
- Laravel 8+ support.

### Changed

- Project structure.
- composer updated `pusher/pusher-php-server` to v^7.0.
- Models & Migrations' tables names changed (added `ch` prefix to avoid duplication) solves issue #68.
  - Models changed to (`ChMessage`, `ChFavorite`)
  - Migrations' tables names (`ch_messages`, `ch_favorites`)
- Configuration file `config/chatify.php`.

## v1.0.1 - (2020-09-30)

### FIxed

- Security issues.

### Added

- Routes' controllers namespace included in the configuration.

## v1.0.0 - (2019-12-30)

- First release
