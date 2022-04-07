Smart contract & scripts. Made using the [buildspace tutorial](https://buildspace.so/)

# Setting up
(might need to do terminal commands, then clone repo)
1. Terminal commands:
```shell
npm init -y
npm install --save-dev hardhat
npx hardhat
npm install --save-dev @nomiclabs/hardhat-waffle ethereum-waffle chai @nomiclabs/hardhat-ethers ethers
```
2. Delete files `contracts/Greeter.sol`, `scripts/sample-script.js`, `.gitignore`, `README.md`, `package.json`, `package-lock.json`, `test/sample-test.js`
3. Clone this repo
4. Create `hardhat.config.js` with account details

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
