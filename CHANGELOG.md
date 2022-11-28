# Changelog

## [1.2.0](https://github.com/circlefin/openapi-internal/compare/v1.1.1...v1.2.0) (2022-11-28)


### New Features

* add crypto refund endpoint 


### Fixes

* add fromAmount to fiat payments 

## [1.1.1](https://github.com/circlefin/openapi-internal/compare/v1.1.0...v1.1.1) (2022-11-22)


### Bug Fixes

* create payment intent was using the wrong schema 

## [1.1.0](https://github.com/circlefin/openapi-internal/compare/v1.0.3...v1.1.0) (2022-11-17)


### New Features

* add address book endpoints 
* add exchange rates endpoint 
* add google pay and apple payment tokens 
* crypto payouts refactor 
* refactor crypto and fiat payout models 


### Fixes

* add chargeback status to GET chargebacks API response 
* add fundingType field to get cards endpoint 
* add openapi tag descriptions 
* add signet as a destination type for payouts 
* add signet as business destination req type 
* add toAmount to fiat payouts 
* fix incorrect list all payouts source param description 
* model name typos and duplicates 
* move payment intents into payments doc 
* move transfers endpt out of payments and payouts 
* rm crypto payments doc 
* rm instances of readOnly 
* rm on-chain payments and payouts 

## [1.0.3](https://github.com/circlefin/openapi-internal/compare/v1.0.2...v1.0.3) (2022-09-26)


### Bug Fixes

* clean name conventions opsIds + res titles 

## [1.0.2](https://github.com/circlefin/openapi-internal/compare/v1.0.1...v1.0.2) (2022-09-22)


### Bug Fixes

* explicitly define combined OpenAPI file 
* rename operationIds mock endpoints 

## 1.0.1 (2022-09-09)


### Bug Fixes

* include all usdc supported chains 
