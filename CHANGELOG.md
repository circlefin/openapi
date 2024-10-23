# Changelog

## [2.13.0](https://github.com/circlefin/openapi-internal/compare/v2.12.0...v2.13.0) (2024-10-23)


### Features

* support CUBIX account type 

## [2.12.0](https://github.com/circlefin/openapi-internal/compare/v2.11.1...v2.12.0) (2024-09-23)


### Features

* Bank 2919 Add /v1/fees/redemption/net/dailyReports to payment docs 

## [2.11.1](https://github.com/circlefin/openapi-internal/compare/v2.11.0...v2.11.1) (2024-09-03)


### Bug Fixes

* use dind spot runner for sync public repo 

## [2.11.0](https://github.com/circlefin/openapi-internal/compare/v2.10.0...v2.11.0) (2024-09-03)


### Features

* [BANK-1913] Add transferTypesInfo to GET wire account and GET cbit account endpoints 
* Add PIX endpoints and update for FX 


### Bug Fixes

* Add missing build permissions 


### Miscellaneous Chores

* **deps:** update actions/checkout action to v4 
* **deps:** update actions/setup-node action to v4 
* **deps:** update circlefin/circle-runner-setup-action action to v5.1.10 
* **deps:** update crazy-max/ghaction-import-gpg action to v6 
* **deps:** update peter-evans/create-pull-request action to v6 
* revert permissions additions in release workflow 
* use default changelog types 


### Continuous Integration

* bump runner action setup version 
* fix AWS secrets names 
* fix runner image 
* refactor to circle runner job setup 
* specify node version 
* switch to shared workflows 
* update AWS secrets path to /ops/ pref 
* use default iam role in runner setup 

## [2.10.0](https://github.com/circlefin/openapi-internal/compare/v2.9.0...v2.10.0) (2024-04-25)


### New Features

* [BANK-2073] Add v1/exchange/quotes to payments docs 
* use circlefin/github-actions-cache@v1 

## [2.9.0](https://github.com/circlefin/openapi-internal/compare/v2.8.0...v2.9.0) (2024-03-28)


### New Features

* add status property to GET /recipient API endpoint 

## [2.8.0](https://github.com/circlefin/openapi-internal/compare/v2.7.1...v2.8.0) (2024-03-11)


### New Features

* add business address recipient delete API 

## [2.7.1](https://github.com/circlefin/openapi-internal/compare/v2.7.0...v2.7.1) (2024-02-22)


### Fixes

* add CELO Chain option 

## [2.7.0](https://github.com/circlefin/openapi-internal/compare/v2.6.2...v2.7.0) (2024-02-16)


### New Features

* remove MATIC Chain option 

## [2.6.2](https://github.com/circlefin/openapi-internal/compare/v2.6.1...v2.6.2) (2023-11-20)


### Fixes

* Add addressTag to crypto refund destination 

## [2.6.1](https://github.com/circlefin/openapi-internal/compare/v2.6.0...v2.6.1) (2023-10-16)


### Fixes

* docs updates for Circle Mint Singapore launch, travel rule 

## [2.6.0](https://github.com/circlefin/openapi-internal/compare/v2.5.0...v2.6.0) (2023-10-10)


### New Features

* add POLY Chain option 

## [2.5.0](https://github.com/circlefin/openapi-internal/compare/v2.4.0...v2.5.0) (2023-09-19)

### New Features

* add PAH to Chain.yaml 

## [2.4.0](https://github.com/circlefin/openapi-internal/compare/v2.3.0...v2.4.0) (2023-09-14)


### New Features

* add NEAR to Chain.yaml 

## [2.3.0](https://github.com/circlefin/openapi-internal/compare/v2.2.0...v2.3.0) (2023-09-12)


### New Features

* add NOBLE to Chain.yaml 

## [2.2.0](https://github.com/circlefin/openapi-internal/compare/v2.1.0...v2.2.0) (2023-09-05)


### New Features

* Enable ARB, OP and BASE chains 

## [2.1.0](https://github.com/circlefin/openapi-internal/compare/v2.0.1...v2.1.0) (2023-07-17)


### New Features

* [BANK-713] Add billing details to Update a card page 

## [2.0.1](https://github.com/circlefin/openapi-internal/compare/v2.0.0...v2.0.1) (2023-07-10)


### Fixes

* remove misplaced required idempotency key fields 

## [2.0.0](https://github.com/circlefin/openapi-internal/compare/v1.8.0...v2.0.0) (2023-04-25)


### ⚠ BREAKING CHANGES

* Remove references to banking 3rd party Payment/Payout APIs 

### Fixes

* Remove references to banking 3rd party Payment/Payout APIs 

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
