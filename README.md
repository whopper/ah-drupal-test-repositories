# CDE Composer Example

This is an example of a composer project dev branch. It does not have it's
build committed (vendor'd). It uses the Drupal repository composer plugins to
manage drupal specific dependencies.

Adding a Drupal project looks something like:

```
$ composer require drupal/memcache:*@dev
```

Which will install the modules to `docroot/modules/contrib/memcache` as
configured in composer.json.
