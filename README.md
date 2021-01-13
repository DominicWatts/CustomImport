# Xigen Custom Import

![phpcs](https://github.com/DominicWatts/CustomImport/workflows/phpcs/badge.svg)

![PHPCompatibility](https://github.com/DominicWatts/CustomImport/workflows/PHPCompatibility/badge.svg)

![PHPStan](https://github.com/DominicWatts/CustomImport/workflows/PHPStan/badge.svg)

Quick custom import to take SKU and price - using built-in Magento 2 import logic 

Check `./supplied` data

## Install

`composer require dominicwatts/customimport`

`php bin/magento setup:upgrade`

## Usage instructions

System | Import

Entity Type: Xigen Price Import

Choose either Add / Update or Replace behavior - this is the same behavior. Delete has no affect.