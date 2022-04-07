Smart contract & scripts. Made using the [buildspace tutorial](https://buildspace.so/)

# Setting up
(might need to do terminal commands, then clone repo)
1. clone repo
2. terminal commands
```shell
npm init -y
npm install --save-dev hardhat
npx hardhat
npm install --save-dev @nomiclabs/hardhat-waffle ethereum-waffle chai @nomiclabs/hardhat-ethers ethers
```

# Running
```shell
npx hardhat run scripts/run.js
```

# Hardhat Commands
```shell
npx hardhat accounts
npx hardhat compile
npx hardhat clean
npx hardhat test
npx hardhat node
node scripts/sample-script.js
npx hardhat help
```
