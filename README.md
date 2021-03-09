# Multiple Layered Navigation for Magento 2

This extension gives you an ability to choose a few options of one filterable attribute

New beta features in 0.1.0 release (disabled in admin panel by default):

- Ajax page update
- Seo friendly URLs
- Price slider

## Installation:

First add repository to composer configuration:
```bash
composer config repositories.stevecordle-multiple-layered-navigation vcs git@github.com:stevecordle/magento2-multiple-layered-navigation.git
```

Require new package with composer:
```bash
composer require stevecordle/multiple-layered-navigation
```

Enable module
```bash
php bin/magento module:enable Niks_LayeredNavigation
```

Upgrade setup:
```bash
php bin/magento setup:upgrade
```
