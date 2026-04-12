# Project Overview

`EAD-CCF-commercial` is the commercial exposure-at-default and credit-conversion-factor engine in the public credit-risk stack.

## Portfolio role

It converts facility limits, drawn balances, and utilisation assumptions into funded and unfunded exposure views for downstream loss, stress, pricing, and capital analysis.

## Upstream inputs

- facility and limit inputs staged under `data/`
- product utilisation and CCF assumptions maintained in-repo

## Downstream consumers

- `expected-loss-engine-commercial`
- `stress-testing-commercial`
- `RAROC-pricing-and-return-hurdle`
- `RWA-capital-commercial`
