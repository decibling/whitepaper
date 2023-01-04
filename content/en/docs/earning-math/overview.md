---
title: Overview
draft: false
weight: 610
lastmod: 2023-01-04T08:59:22.333Z
---
collector pays 50

  artist income 10%
  artist dcba pool 2.5%
  collector dcba pool 2.5%

  =>> artist = 43.75 (-gas fee)
      dcba = 1.25
      income = 5

      mail collector = 2.5
----

collector 2 pays 100

  collector 1 income 10%
  collector 2 dcba pool 2.5%

  =>> collector 1 = 90 (-gas fee)
      income = 10

      mail priv to collector 2 = 2.5

  ---

dcb pool
2% return
(5% fee)

total staked pool = X (FROY)
cycle = C = 5 (days)
fees = 5% = F
return = 2% = R
return per cycle RPC = X * (R * (1-(F/100))/100) / (365 / C)

example
X = 1,000,000
C = 5
F = 5
R = 2
RPC = X * (R * (1-F)/100) / (365 / C) = 1000000 * (2 * (1-(5/100))/100) / (365 / 5) = 260.2739726 FROY
if stakers K = 1000 then return per user is 260.2739726 / 1000 = 0.2602739726
