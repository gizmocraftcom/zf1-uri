# Changelog
## 2.0.0
Fork of `diablomedia/zendframework1-uri`, published as `gizmocraft/zendframework1-uri`.
### Breaking changes
- Requires PHP `>=8.5`. Tested on PHP 8.5 and 8.6.
- Package renamed from `diablomedia/zendframework1-uri` to `gizmocraft/zendframework1-uri`. It now requires `gizmocraft/zendframework1-exception` `^2.0.0`, `gizmocraft/zendframework1-config` `^3.0.0`, `gizmocraft/zendframework1-loader` `^2.0.0` and `gizmocraft/zendframework1-validate` `^2.0.0`.
### Other changes
- No public signature changes. `Zend_Uri` and `Zend_Uri_Http` needed no code changes for PHP 8.5 or 8.6.
- Dev dependencies upgraded (PHPUnit 13, PHPStan 2.3, php-cs-fixer 3.95, GrumPHP 2.27). Dropped `composer-require-checker`, which has no release for PHP 8.6.
- Tests migrated to PHPUnit 13 attributes (`#[Group]`, `#[DoesNotPerformAssertions]`).
- CI runs PHP 8.5 and 8.6.
