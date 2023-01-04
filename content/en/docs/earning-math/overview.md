---
title: Overview
draft: false
weight: 610
lastmod: 2023-01-04T09:32:26.996Z
---
## Biddings
Default settings
* Default income: 10%
* Artist DCBA pool: 2.5%
* Collector DCBA pool: 2.5%

First sale:
* Artist listed with 1,000 FROY
* Collector won at 10,000 FROY

Settle bid on first sale:
* Artist receives 100% - (10% + 2.5%) = 87.5% = 10,000 * 87.5% = 8,750 FROY
* DCBA pool receives 2.5% = 250 FROY
* Platform fees (for default income) 10% = 1000 FROY

Second sale:
* Collector A listed with 15,000 FROY
* Collector B won at 100,000 FROY

Settle bid on second sale:
* Artist receives 100% - (10%) = 90% = 100,000 * 90% = 90,000 FROY
* Platform fees (for default income) 10% = 10,000 FROY

## Staking
### Default pool
Default settings:
* 2% return for stakers = R
* 5% platform fees = F
* 365 days in a year = Y
* Pay cycle: 5 days

The shortened formula for every day is: R / (100 * Y) = 2 / (100 * 365) = 5.47945E-05 = K

Let the staked amount is 100,000 FROY

The total profit would be: P = 100,000 * K * 5 = 27.39726027
* Estimated profit will be received: P * 0.95 = 26.02739726 FROY
* Estimated Platform fee = P * 0.05 = 1.369863014 FROY
> The profit will be calculated correctly when you submit on our smart contracts.

### Artist pool
(Coming soon)