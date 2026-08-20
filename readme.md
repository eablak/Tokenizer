# Tokenizer

We want to build BEP-20 token on the Binance (BNB) Smart Chain. 

- First thing we need is good reliable wallet for your cyripto. That's why we will use [Metamask](https://metamask.io/tr). So i download it for my chrome and i will continue to use it as a extension. create your wallet.
- Open [Remix Ide](https://remix.ethereum.org/#optimize=false&runs=200&evmVersion=null&version=soljson-v0.8.7+commit.e28d00a7.js&lang=en). In this ide we will develop our smart contract and test it.
- For smart contract we can use [OpenZeppelin](https://www.openzeppelin.com/). Openzeppelin is industry standards. They have contracts that have been audited and battle tested. So i will use these contracts for deploying my own smart contracts. They basically provide the scaffolding you need to get started. [wizard](https://wizard.openzeppelin.com/) image00 is default version.
- We are deploying BEP-20 token it's not ERC-20 token but it's based of ERC-20 token. So we can use ERC-20 token contract to deploy our token.
- So i give my token name, symbol and premint -> 01_image. And after it i click the "open in remix" tab
- Paste your wallet address in remix and our contract is ready to test in remix. Click "deploy & run" tab.
03_image -> deploy