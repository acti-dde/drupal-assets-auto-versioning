# Usage

```
composer require acti-dde/drupal-assets-auto-versioning
```

In your `module_or_theme.info.yml`, add :

```
dependencies:
  - acti_assets_auto_versioning:acti_assets_auto_versioning
```

Then, in your `module_or_theme.libraries.yml` :

```
my-library:
  version: AUTO
  css: ...
  js: ...
```