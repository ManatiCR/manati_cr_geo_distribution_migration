# manati_cr_geo_distribution_migration
Provides the Costa Rican Geographic dristribution for drupal 8

## Dependencies
migrate_source_csv: "^3.4"
drupal/migrate_plus: "^5.1"
drupal/migrate_tools: "^5.0"
drupal/config_devel: "^1.8"

## How to install
If you clone this repo you need to insall all dependencies with composer.
But the project has a Packagist [Package](https://packagist.org/packages/manaticr/manati-cr-geo-distribution-migration)
Just need run this command </br>
`composer require manaticr/manati-cr-geo-distribution-migration`

## How to use 

### Import provincies
`drush migrate:import provincias_cr`

### Import provincies
`drush migrate:import cantones_cr`

### Import provincies
`drush migrate:import distritos_cr`

## Remove the module
When you import al taxonomy terms you should uninstall the module, just run </br>
`composer remove manaticr/manati-cr-geo-distribution-migration`

If you install the module with git clone, you need uninstall all dependencies modules. 
