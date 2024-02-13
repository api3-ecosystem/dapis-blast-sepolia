## API3 dAPIs on Blast L2

This repository contains the proxy contract addresses for the API3 dAPIs available on Blast L2 Testnet. The dAPIs are deployed on-chain and the proxy contracts are used to read the latest data feed values.

## Proxy Contract Addresses

| Assets | Deviation threshold | Proxy contracts | Sponsor wallets |
|--------|---------------------|-----------------|-----------------|
| ETH/USD | 1% | 0x19bbC5D6FF83f9C89a436E0Ad1b53dc1433a983A | 0xC680BcDA3b122837A0D49ba23f607b412Cd90906 |
| BTC/USD | 1% | 0x8c1E34256BCf8311d81F58C63bB750Be5e74673C | 0x82D117e7AdEd3fC8A9266252899B21C843dDC4B2 |
| AAPL/USD | 1% | 0xF3c1EC2F91EfeA49Cad6b962B17B0BE8936219D6 | 0x91E8A2033f1ce7f0138f88e01EFEAA14776387FD |
| AAVE/USD | 1% | 0x7ce468F74C47898448A0F08Eb1ca4e43c4A8204a | 0x17EeAbF49bE81B763F88877E508584cf0A5a5eD6 |
| ADA/USD | 1% | 0x3D6d740CFBDD6C2Ee2E7632A82A6b23cE45c3b49 | 0x793Fe5f0bF4D4E4C3f05909622F1A950ae951D60 |
| AMZN/USD | 1% | 0x3c139Ef455F668B8D9924829B2da3d53546bA33f | 0xd74eDF7043472830d93145Bd0087059c6AB317F3 |
| API3/USD | 1% | 0xfdf70547F91889d2Ec7B2157CF69b894bF10E702 | 0xBA1817Ceb62A8dcC9d42a166b9F7CAB204656c72 |
| ARB/USD | 1% | 0xF0f86E1e59Cd6349Ab4C7b202e03395AB88b3Be7 | 0x751114392B3Da45f24755aCd51a6E794E5Af029a |
| DAI/USD | 1% | 0xD3881a38236C186F017e9d3003F84aE6CFba5a72 | 0xF8CbF618Bc8ff4BF78bEb744ba33380C362227Db |
| DOGE/USD | 1% | 0xb30A18CE3CeF3BDB70DAcADE8b2A38C8b378d40d | 0x8B67b0728380fF6931cc7D4aa8ab2844A6f0B82F |
| EUR/USD | 1% | 0x67829aF44f8f65DaF7dfca67d026248f903Ee407 | 0xcdFf7651081394D54E207507647ecCcD947e6194 |
| FTM/USD | 1% | 0x60e35Baf9Ce9C51f138d5E28CBC97668A618621F | 0xc159a792f5039255534750E85F1a029c9a313da5 |
| GBP/USD | 1% | 0x9593255efD34E0FB899ca010d74c994FB16DD6Bb | 0x4E5b812B0Ef66006C027196c11Ee448b4AE7381e |

Make sure to use the correct proxy contract address for the data feed you want to read. Also, fund the sponsor wallets with the required amount of gas so it keeps the data feeds updated.

## Usage

The proxy contracts are used to read the latest data feed values. The proxy contracts are deployed on-chain and the addresses are available in this repository for now. The proxy contracts are used to read the latest data feed values.

[Check out this guide on how to read a data feed on Blast L2 Testnet](https://docs.api3.org/guides/dapis/read-a-dapi/)