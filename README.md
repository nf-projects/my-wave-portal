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
3. Delete the `contracts` and `scripts` folders
4. Clone this repo
5. Create `hardhat.config.js` with account details

# Running
```shell
npx hardhat run scripts/run.js
```

# Re-Deploying
1. `npx hardhat run scripts/deploy.js --network rinkeby`
2. Change contractAddress in App.js to be the new contract address from the command above
3. Get the updated abi file from `artifacts` and paste it into the React App

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
