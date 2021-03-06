## v160910.71271

- Adding `src/includes/os-utils.php`.
- Adding `src/includes/php-utils.php`.
- Adding `src/includes/versions.php`.
- Adding `___wp_php_rv_get_php_version()`.
- Minor enhancements in `wp_php_rv_notice()`.
- Minor enhancements in `___wp_php_rv_notice_brand_name()`.
- Removing very old (already-deprecated) function `wp_php_rv_custom_notice()` entirely. You should be using `wp_php_rv_notice()` instead please.
- Remove unused filter `wp_php_rv_notice_refs_before_markup`.
- Remove unused filter `wp_php_rv_notice_refs`.
- New filter: `wp_php_rv_notice_markup`.

## v160824.6416

- Bug fix. Array not initialized properly. See: #12

## v160712.42603

- **Bug fix:** Required PHP extension checks failing.
- **New Feature:** Now possible to require specific PHP functions too; e.g., `eval()`.
- Updating to latest phing build system.
- Updating dotfiles.

## v160531.14034

- Adding phing build files.

## v160524

- Adding support for an array of compatible operating systems.
- Adding support for a minimum version of WordPress.
- Adding support for a maximum version of WordPress.

## v160504

- Adding support for required bits via `$GLOBALS['wp_php_rv']['bits'] = 64;`

![2016-05-04_23-42-50](https://cloud.githubusercontent.com/assets/1563559/15038648/fb5fb04e-1251-11e6-96d6-af1a563413f1.png)

## v160503

- Enhancing display of notice.
- Reorganizing functions into multiple files.
- Backward compatibility was preserved in all cases.

![](https://github.com/websharks/wp-php-rv/raw/000000-dev/assets/screenshot.png)

## v160420

- Adding `composer.json` and enhancing Composer integration.
- General cleanup. No significant changes.

## v15xxxx

- Initial release.
