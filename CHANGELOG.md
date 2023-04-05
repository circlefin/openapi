# Changelog

## [1.8.0](https://github.com/circlefin/openapi-internal/compare/v1.7.3...v1.8.0) (2023-04-05)


### New Features

* add CBIT business account endpoints 

## [1.7.3](https://github.com/circlefin/openapi-internal/compare/v1.7.2...v1.7.3) (2023-03-21)


### Fixes

* add reason to payment intent timeline 

## [1.7.2](https://github.com/circlefin/openapi-internal/compare/v1.7.1...v1.7.2) (2023-03-21)


### Fixes

* payment intents endpoints schemas 

## [1.7.1](https://github.com/circlefin/openapi-internal/compare/v1.7.0...v1.7.1) (2023-03-07)


### Fixes

* remove discriminators 

## [1.7.0](https://github.com/circlefin/openapi-internal/compare/v1.6.0...v1.7.0) (2023-03-02)


### New Features

* add POST /payments/crypto and GET /payments/presign for the gas-less project 

## [1.6.0](https://github.com/circlefin/openapi-internal/compare/v1.5.0...v1.6.0) (2023-02-14)


### New Features

* add network fees to crypto payments and payouts 


### Fixes

* add addressTag to CryptoPayment.yml 
* optional merchant wallet id in payment intent req / resp 
* update crypto payment response with from addresses 

## [1.5.0](https://github.com/circlefin/openapi-internal/compare/v1.4.0...v1.5.0) (2023-01-23)


### New Features

* add list checkout sessions endpoint 

## [1.4.0](https://github.com/circlefin/openapi-internal/compare/v1.3.1...v1.4.0) (2023-01-23)


### New Features

* add continuous payment intent request and responses 


### Fixes

* revert Payment Intent schema names 

## [1.3.1](https://github.com/circlefin/openapi-internal/compare/v1.3.0...v1.3.1) (2022-12-06)


### Fixes

* remove beta tags from sepa apis 

## [1.3.0](https://github.com/circlefin/openapi-internal/compare/v1.2.1...v1.3.0) (2022-12-05)


### New Features

* add checkout sessions endpoints 


### Fixes

* add updateDate for checkout session 
* summary and operation id for crypto refund api 

## [1.2.1](https://github.com/circlefin/openapi-internal/compare/v1.2.0...v1.2.1) (2022-11-28)


### Fixes

* remove identities from crypto refund creation request 

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
