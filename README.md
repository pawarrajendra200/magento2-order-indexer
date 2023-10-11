# Overview
## Purpose of module

TechRaj\OrderIndexer module is responsible for create a order indexer in system,
TechRaj\OrderIndexer module is watch sales_order DB table and get newly created/updated row date and store it into sales_order_flat table
## Deployment
## System requirements

## Install
### Add repository
Repositry : composer config repositories.rajtech-order-indexer git https://github.com/pawarrajendra200/magento2-order-indexer.git
### Install the Extension using Composer
composer require tech-raj/order-indexer
### Enable the Extension

php bin/magento module:enable TechRaj_OrderIndexer

### Last execute magento commanads
1) php bin/magento setup:upgrade
2) php bin/magento setup:di:compile
3) php bin/magento setup:static-content:deploy
4) php bin/magento setup:cache:flush
