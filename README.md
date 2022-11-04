# hardhat-funding-smart-contract

This is a simple funding contract where users can fund the contract and the contract has the ability to track the funders. Along with that only owner at any time can withdraw the funds if there will be any!

### Interact with Smart Contract on Goerli Etherscan

[link](https://goerli.etherscan.io/address/0xb3d1F06Ea6a85E1Fd9Ef29768c31022d8127e9D1)

Make sure to go to Contract tab (green checkmark)

### Requirements

In order to run it, you need to create a `.env` file at the root level and inside it you need to add these things;  

1. QuickNode RPC URL
```env
QUICKNODE_GOERLI_RPC_URL=https://convincing-green-knowledge.ethereum-goerli.discover.quiknode.pro/API-KEY-HERE/
```
2. Wallet Private Key (Metamask)
```env
PRIVATE_KEY=PRIVATE-KEY-HERE
```
3. Coin Marketcap API Key
```env
COINMARKETCAP_API_KEY=https://eth-mainnet.g.alchemy.com/v2/API-KEY-HERE
```
4. Etherscan API Key
```env
ETHERSCAN_API_KEY=API-KEY-HERE
```

### Install dependencies
```bash
npm install --force
```

### Compile Smart Contract

```bash
npx hardhat compile
```

### Deploy Smart Contract - locally hardhat

```bash
npx hardhat deploy
```


### Test Smart Contract - locally hardhat

```bash
npx hardhat test
```


### Deploy Smart Contract - Testnet Goerli

```bash
npx hardhat deploy --network goerli
```
