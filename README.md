# Basic Sample Hardhat Project

This project demonstrates a basic Hardhat use case. It comes with a sample contract, a test for that contract, a sample script that deploys that contract, and an example of a task implementation, which simply lists the available accounts.

Try running some of the following tasks:

```shell
npx hardhat accounts
npx hardhat compile
npx hardhat clean
npx hardhat test
npx hardhat node
node scripts/sample-script.js
npx hardhat help
```
# hardhat-ganache-console-practice

## How to start
- Clone the apps
- npm install 
- ```npx hardhat compile```
- ```npx hardhat run scripts/yourscriptname.js --network ganache```

## How to interact locally with console and see changes
- Clone the apps
- npm install 
- ```npx hardhat compile```
- ```npx hardhat console --network ganache```
- ```const Greeter = await hre.ethers.getContractFactory("Greeter")```
- ```greeter = await Greeter.deploy("Hello, Hardhat!")```
- ```await greeter.greet()```
- ```await greeter.setGreeting('Hi,Piash!')```
