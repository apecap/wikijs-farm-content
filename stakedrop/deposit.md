---
title: Harvest Deposit Stakedrop
description: deposit assets into Harvest yield farming strategies, receive FARM
published: true
date: 2020-09-18T04:28:37.608Z
tags: 
editor: markdown
dateCreated: 2020-09-08T03:09:48.188Z
---

> Use the [harvest.finance](https://harvest.finance) site to stake assets. Sending tokens directly to contracts will result in loss of funds! Verify all [token addresses](https://github.com/harvest-finance/harvest) to avoid trading fake tokens.
{.is-warning}

Harvest Finance works by directing assets deposited by users into the yield farming strategies that are currently offering the highest rewards.

To bootstrap deposits into Harvest, holders of Harvest deposit tokens (`fASSETs`) can stake these `fASSETs` to receive a stakedrop of `$FARM` tokens.

> Participants receive their share of revenue from Harvest yield farming in adition to the `$FARM` stakedrop.
{.is-success}


| Dates  | Eligible Assets | Rewards |
|--------|-----------------|---------|
| Week 1, Sept 1-8  | USDC, USDT, DAI | ~12,000 `$FARM` split evenly between the eligible assets|     
| Week 2, Sept 8-15 | USDC, USDT, DAI | ~11,000 `$FARM` split evenly between the eligible assets|     
| Week 3, Sept 15-22 | USDC, USDT, DAI | ~5,000 `$FARM` split evenly between the eligible assets|  

# How To Participate

### 1. Acquire fASSETs

The simplest option is to deposit eligible assets on [harvest.finance](https://harvest.finance). This is the best option for holders who want to acquire >$1000. Deposit transactions cost around 450,000 gas, so it makes sense to leave funds deposited for several weeks. For smaller purchases of amounts <$1000, it's typically more economical to buy `fASSETS` on Uniswap. Selling `fASSETs` on Uniswap is also an inexpensive way for smaller holders to exit Harvest without paying transaction fees to withdraw.


| Deposit    | Receive      | Uniswap Purchase Link |
|:----------:|:------------:|-------------|
| `USDC`     | `fUSDC`   		|[buy fUSDC](https://app.uniswap.org/#/swap?outputCurrency=0xc3f7ffb5d5869b3ade9448d094d81b0521e8326f)|
| `USDT`     | `fUSDT`   		|[buy fUSDT](https://app.uniswap.org/#/swap?outputCurrency=0xc7ee21406bb581e741fbb8b21f213188433d9f2f)|
| `DAI`			 | `fDAI`				|[buy fDAI](http://uniswap.exchange/swap?outputCurrency=0xe85c8581e60d7cd32bbfd86303d2a4fa6a951dac)|
| `WBTC`	   | `fWBTC`	  	|[buy fWBTC](https://app.uniswap.org/#/swap?outputCurrency=0xc07eb91961662d275e2d285bdc21885a4db136b0)
| `renBTC`   |`frenBTC`   	|[buy frenBTC](https://app.uniswap.org/#/swap?outputCurrency=0xfbe122d0ba3c75e1f7c80bd27613c9f35b81feec)
|`CrvRenWBTC`|`fcrvRenWBTC`	|[buy fcrvRenWBTC](https://app.uniswap.org/#/swap?outputCurrency=0x192e9d29d43db385063799bc239e772c3b6888f3)
| `WETH`  	 |`fWETH`				|[buy fWETH](https://app.uniswap.org/#/swap?outputCurrency=0x8e298734681adbfc41ee5d17ff8b0d6d803e7098)

Over time, yield farming will cause these fASSETs will grow in value. Simply holding these fASSETs will not entitle you to the FARM stakedrop.

### 2. Deposit fASSETs on [harvest.finance/earn](https://harvest.finance/earn)

Deposit the `fASSETs` using the `EARN` tab. You will immediately begin receiving `$FARM` stakedrop rewards that can be claimed at any time.




# Technical Details

> Contract addresses are provided for technical information only; **do not interact directly with the contracts unless you know what you are doing!**
{.is-warning}


| Token | Address | Rewards Staking Pool |
|-------|---------|--------------|
| FARM  | [0xa0246c9032bc3a600820415ae600c6388619a14d][es-farm]  | [0xae024F29C26D6f71Ec71658B1980189956B0546D][es-pool-farm-week1] |
| fUSDC | [0xc3f7ffb5d5869b3ade9448d094d81b0521e8326f][es-fusdc] | [0xE1f9A3EE001a2EcC906E8de637DBf20BB2d44633][es-pool-fusdc-week1] |
| fUSDT | [0xc7ee21406bb581e741fbb8b21f213188433d9f2f][es-fusdt] | [0x5bd997039FFF16F653EF15D1428F2C791519f58d][es-pool-fusdt-week1] |
| fDAI  | [0xe85c8581e60d7cd32bbfd86303d2a4fa6a951dac][es-fdai]  | [0xF9E5f9024c2f3f2908A1d0e7272861a767C9484b][es-pool-fdai-week1] |
| fWBTC | [0xc07eb91961662d275e2d285bdc21885a4db136b0][es-fWBTC] | [0x6291eCe696CB6682a9bb1d42fca4160771b1D7CC][es-pool-fwbtc]|
| frenBTC| [0xCFE1103863F9e7Cf3452Ca8932Eef44d314bf9C5][es-frenbtc]| [0xCFE1103863F9e7Cf3452Ca8932Eef44d314bf9C5][es-pool-frenbtc]|
|fcrvRenWBTC|[0x192e9d29d43db385063799bc239e772c3b6888f3][es-fcrvrenwbtc]| [0x5365A2C47b90EE8C9317faC20edC3ce7037384FB][es-pool-fcrvrenwbtc]|
| fWETH	|[0x8e298734681adbfc41ee5d17ff8b0d6d803e7098][es-fweth] | [0xe11c81b924bb91b44bae19793539054b48158a9d][es-pool-fweth]|


[es-farm]: https://etherscan.io/token/0xa0246c9032bc3a600820415ae600c6388619a14d
[es-fusdc]: https://etherscan.io/token/0xc3f7ffb5d5869b3ade9448d094d81b0521e8326f
[es-fusdt]: https://etherscan.io/token/0xc7ee21406bb581e741fbb8b21f213188433d9f2f
[es-fdai]: https://etherscan.io/token/0xe85c8581e60d7cd32bbfd86303d2a4fa6a951dac
[es-fwbtc]: https://etherscan.io/token/0xc07eb91961662d275e2d285bdc21885a4db136b0
[es-frenbtc]: https://etherscan.io/address/0xCFE1103863F9e7Cf3452Ca8932Eef44d314bf9C5
[es-fcrvrenwbtc]: https://etherscan.io/token/0x192e9d29d43db385063799bc239e772c3b6888f3
[es-fweth]: https://etherscan.io/token/0x8e298734681adbfc41ee5d17ff8b0d6d803e7098


[es-fdai-contract]: https://etherscan.io/address/0xe85c8581e60d7cd32bbfd86303d2a4fa6a951dac#readContract
[es-fusdt-contract]: https://etherscan.io/address/0xc7ee21406bb581e741fbb8b21f213188433d9f2f#readContract
[es-fusdc-contract]: https://etherscan.io/address/0xc3f7ffb5d5869b3ade9448d094d81b0521e8326f#readContract

[es-pool-farm-week1]: https://etherscan.io/address/0xae024F29C26D6f71Ec71658B1980189956B0546D#readContract
[es-pool-fdai-week1]: https://etherscan.io/address/0xF9E5f9024c2f3f2908A1d0e7272861a767C9484b#readContract
[es-pool-fusdc-week1]: https://etherscan.io/address/0xE1f9A3EE001a2EcC906E8de637DBf20BB2d44633#readContract
[es-pool-fusdt-week1]: https://etherscan.io/address/0x5bd997039FFF16F653EF15D1428F2C791519f58d#readContract
[es-pool-fwbtc]: https://etherscan.io/address/0x6291eCe696CB6682a9bb1d42fca4160771b1D7CC#readContract
[es-pool-frenbtc]: https://etherscan.io/address/0xCFE1103863F9e7Cf3452Ca8932Eef44d314bf9C5#readContract
[es-pool-fcrvrenwbtc]: https://etherscan.io/address/0x5365A2C47b90EE8C9317faC20edC3ce7037384FB#readContract
[es-pool-fweth]: https://etherscan.io/address/0xe11c81b924bb91b44bae19793539054b48158a9d#readContract

[es-withdraw-buffer]: https://etherscan.io/tx/0x70fddec35fcf1f89fbfff90972be0e04ce0ae8c34abfaf2900e5210fdf86303e
[es-withdraw-nobuffer]: https://etherscan.io/tx/0x959045e3c8fb26a9eeab00e5ebe11fe62012cc7148f4d025c4c7f75ec0bed0bb
[uni-fusdc]: https://app.uniswap.org/#/swap?outputCurrency=0xc3f7ffb5d5869b3ade9448d094d81b0521e8326f












