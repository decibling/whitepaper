---
title: Compounding interest
draft: false
weight: 615
lastmod: 2023-05-18T08:54:53.926Z
---

In Decibling pools, both types, including default Decibling pool and Artist pools would receive compounding interest per second.

As an example: if you want to accrue interest at a nominal rate, i.e. of 5.0% per year, compounded continuously (equivalent to an Effective Annual Rate of 5.127%). This is approximately equal to 5.0% per year compounded every second (to about 8 decimal places).

The payout would be transferred when you use the **Claim** or **Unstake**.
* If you use **Claim**: the payout would be sent directly to your staked wallet address.
* If you use **Unstake**: the payout would be sent directly with your unstaked amount. If you still have staked amount on the pool, it would start a new cycle of compounding interest from the time you unstaked.

## Approximation

The standard formula for the future value of an asset with discretely compounded interest is:

> FV = P(1 + i/n) ** (n * t)

where:

- FV = the Future value of the asset
- P = The principal, or present value
- i = the nominal interest rate per period (where period is typically 1 year, but we ultimately make it 1 second)
- n = The number of compounding periods within each interest period.

As we increase the number of compounding periods, the effective interest rate (the actual increase in value over the interest period) increases and nearly reaches infinity. Taking the limit of the above equation as n approaches infinity gives us the equation for continuously compounded interest:

> FV = P * e ** (r * t)

In Decibling, this is typically the way that we want to calculate interest, because the lifetimes of interest accruing positions can be highly variable and it is important to track small amounts of interest (1 second).