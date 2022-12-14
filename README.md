# Opyn Crab Netting contest details

- 25,000 USDC main award pot
- Join [Sherlock Discord](https://discord.gg/MABEWyASkp)
- Submit findings using the issue page in your private contest repo (label issues as med or high)
- [Read for more details](https://docs.sherlock.xyz/audits/watsons)
- Starts November 23, 2022 15:00 UTC
- Ends November 30, 2022 15:00 UTC

# Resources

- [Crab Netting](https://opynopyn.notion.site/Crab-Netting-Blurb-d4ce8a3c75694c54af03b3997a70be0c)
- [Twitter](https://twitter.com/opyn_)
- [Website](https://www.opyn.co/)
- [Squeeth gitbook](https://opyn.gitbook.io/squeeth/resources/squeeth-faq)
    - Note the sections on:
        - Squeeth strategies FAQ 
	    - Squeeth Resources
	    - Auctions - Crab v2
- [Goerli deployment](https://goerli.etherscan.io/address/0xf3e40abf4c06b9454440cb93d42e60de5e67db2a)


# On-chain context

```
DEPLOYMENT: MAINNET
ERC20: Sqth, Crab, WETH, USDC
ERC721: uni-V3 if you lp for sqth-eth
ADMIN: restricted to specific actions
```


# Tests

- Install [forge](https://book.getfoundry.sh/getting-started/installation)
- open .env and add in your API KEY for your RPC_ENDPOINT
- `cd crab-netting`
- `forge test`

# Audit scope

The following contracts are in scope
1. CrabNetting.sol (its interfaces) and its dependencies CrabStrategyV2.sol, Controller.sol

You can find the dependencies inside this [repo](https://github.com/opynfinance/squeeth-monorepo/)

# About Opyn

Opyn builds DeFi-native derivatives and options infrastructure. Opyn built DeFi's first options protocol and has since grown into a flourishing product ecosystem and global community that has collectively traded more than $4 billion of notional volume across 45,000+ trades, and we're just getting started.

