# Hyperloop Option Market

Hyperloop's internal option liquidity pool for non-liquidative lending.

## Overview

Hyperloop pairs collateral-backed loans with put options designed to protect lender principal at maturity without interim liquidation of borrower collateral. Hyperloop Option Market is intended to supply this protection from an internal pool of option writers.

## Planned scope

- Pool capital from option writers to underwrite collateral-backed put options.
- Match each option's underlying asset, notional, strike and maturity to the corresponding loan's protection requirements.
- Attribute option coverage to loans through Hyperloop Awakening's Put Attribution Token (PAT) layer.
- Collect option premiums and manage underwriting capacity, collateral and maturity settlement.
- Complement external option venues, including maturities and strikes where external liquidity is unavailable.

Protection depends on adequate collateral, enforceable option coverage and successful settlement. Pool collateralization and risk limits will be defined during implementation.

## Status

Early-stage design. This repository currently contains the project overview; pool contracts and integrations are not yet implemented here.

## Links

- [Hyperloop Finance](https://hyperloop-fi.xyz)
- [Hyperloop Awakening](https://github.com/hyperloop-finance/awakening-core)
