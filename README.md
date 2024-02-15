## API3 dAPIs on Blast L2

This repository contains the proxy contract addresses for the API3 dAPIs available on Blast L2 Testnet. The dAPIs are deployed on-chain and the proxy contracts are used to read the latest data feed values.

## Proxy Contract Addresses

| Assets | Deviation threshold | Proxy contracts | Sponsor wallets |
|--------|---------------------|-----------------|-----------------|
| ETH/USD | 1% | 0x4EebA314445C64E83fc09E37FCD558BCee9093D3 | 0xC680BcDA3b122837A0D49ba23f607b412Cd90906 |
| BTC/USD | 1% | 0xd97c8EeE2Fe981c8270c25aD84Fc7CB460344282 | 0x82D117e7AdEd3fC8A9266252899B21C843dDC4B2 |
| AAPL/USD | 1% | 0xe265914fc8DF29ffD82bfD7F881c211236d1B0A6 | 0x91E8A2033f1ce7f0138f88e01EFEAA14776387FD |
| AAVE/USD | 1% | 0x889E61caB782C140dF97c4B4cbb1470571E66AdD | 0x17EeAbF49bE81B763F88877E508584cf0A5a5eD6 |
| ADA/USD | 1% | 0xCbAEf6277b3E813c4b3b36787F2E32F0149f1D7C | 0x793Fe5f0bF4D4E4C3f05909622F1A950ae951D60 |
| AMZN/USD | 1% | 0xAb09d275326e3e99de2cAfbab217709BD3F9B840 | 0xd74eDF7043472830d93145Bd0087059c6AB317F3 |
| API3/USD | 1% | 0x5FF10aC9dC26b192B5C989f6d06B56A63804AC01 | 0xBA1817Ceb62A8dcC9d42a166b9F7CAB204656c72 |
| ARB/USD | 1% | 0x66061957638Ec8A3ad8CB8757B80fFbF8Bf83544 | 0x751114392B3Da45f24755aCd51a6E794E5Af029a |
| DAI/USD | 1% | 0x97A7F7c204d4BF4eA9e32CF6d1B043fe19cB6120 | 0xF8CbF618Bc8ff4BF78bEb744ba33380C362227Db |
| DOGE/USD | 1% | 0x2aA24C493b553CEC8757410De621728B29cB68Ea | 0x8B67b0728380fF6931cc7D4aa8ab2844A6f0B82F |
| EUR/USD | 1% | 0x1E34c461551390dA08F760Cd61690B9Dca4fd959 | 0xcdFf7651081394D54E207507647ecCcD947e6194 |
| FTM/USD | 1% | 0x177Ef5e7CE7fC6fb84eb81fc6E5197C33A014D56 | 0xc159a792f5039255534750E85F1a029c9a313da5 |
| GBP/USD | 1% | 0x95A71FD37606780E8D799e2fAA487AD5bc2333D5 | 0x4E5b812B0Ef66006C027196c11Ee448b4AE7381e |
| USDC/USD | 1% | 0xfbddfE040Cd1e33DF21cf6d43f61Bb10A1823137 | 0x2b265b6D826E8d538C3721a1B364073CB3f75234 |
| USDT/USD | 1% | 0x90b9851ea772b04C868Ca9706eD2f8f5D81A887b | 0x8Fc8f8548C2ff2D7A8a92a30ACaB3cA6a6b9F868 |
| cbETH/ETH Exchange Rate | 1% | 0x79d9cfdae2F45eb804315830f57e4E6fcf25C897 | 0x98240f9589FaebDc29BCDBd9ADe71A89CD90AE0C |
| weETH/ETH Exchange Rate | 1% | 0xFF499281e60eB6fb0a60Dbf2d1FAAD1bC4FF2b3d | 0x412F6fa9D37960d85B29CF2F96c1772a488D4dE7 |

Make sure to use the correct proxy contract address for the data feed you want to read. Also, fund the sponsor wallets with the required amount of gas so it keeps the data feeds updated.

## Usage

The proxy contracts are used to read the latest data feed values. The proxy contracts are deployed on-chain and the addresses are available in this repository for now. The proxy contracts are used to read the latest data feed values.

[Check out this guide on how to read a data feed on Blast L2 Testnet](https://docs.api3.org/guides/dapis/read-a-dapi/)