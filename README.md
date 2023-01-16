# IDMC

Repository for IDMC(internal displacement monitoring centre)

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)

# Installation
*  Clone or download the git repo.
*  The project uses packages from composer and also eslint as devDependency from yarn/npm. Make sure to install composer and yarn/npm in your system and execute the command below to install required dependencies
```
cd project_dir
composer install
```
# Usage
## Composer

With `composer require ...` you can download new dependencies to your
installation.

```
cd some-dir
composer require drupal/devel:~1.0
```
## Drush
- Runserver (PHP’s built-in http server for development): `drush runserver`
- Clear cache: `drush cc`
- Clear all cache: `drush cache-rebuid`
- Shows list of available modules & themes `drush pml`
- Run any pending database updates `drush updb`
- Enable a module: `drush pm:enable {name_of_module}`
- Disable a module: `drush pm:uninstall {name_of_module}`
- Check Drupal Composer packages for security updates: `drush pm:security`
- Check watchdog (logged events): `drush ws`

