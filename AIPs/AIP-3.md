---
AIP: 3
Title: AERGO Swap Service Fee Mechanism Update
Author: Hunyoung Park (@ashen1dev)
Status: Stage I
Category: argus
Created: 2020-08-13
---

# AERGO Swap Service Fee Mechanism Update

## Change Swap Service Fee Mechanism

Current Swap Service fee systems were being offered at low fixed costs. However, due to the recent huge increase in Ethereum network fees, we are forced to change the swap service fee.

Basically, we will match the Ethereum gas price of the swap service with the average gas price of the Ethereum network.
Fees will be calculated based on Ethereum's price and Aergo's price.

### Swap Fee = Total ETH transfer fee / Aergo price

Note that for Native -> ETH, 1 TX occurs.
For ETH -> Native, two settlement TXs will be generated and the fee may be doubled.

### What to do
Phase 1
- Update ETH gas price as average gas price of ETH network
- Update Swap Service Fee
- Show the deduction amount of Token on website.

Phase 2
- Update settlement mechanism for low fee.
- Update Fee in real time.

## License
Copyright and related rights waived via [CC0](https://creativecommons.org/publicdomain/zero/1.0/).
