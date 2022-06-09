# Smart-Contract-With-Solidity
Here is a small smart contract using Solidity using a local text editor to a Rinkeby Test Network Creating our own BoilerPlate to run tests

## Files-


#### package.json

You can create the package.json file by selecting a folder in your system , navagating to that folder in the Command Prompt and write commands 
* npm init

* npm install solc@0.8.9 web3 mocha ganache-cli @truffle/hdwallet-provider
 
Make sure you have node.js installed in your system 
Update your test script in the package.json file to be "test": "mocha"



#### compile.js

This is a JavaScipt file which helps us in compiling the solidity file(Inbox.sol) and then bytecode and abi optained after compiling the 
solidity code to the files that needs it

#### MochaTesting.js

This is a sample code to run and check if mocha is working properly. You can copy the code to Inbox.test.js and see if it works.


#### Inbox.sol

Here is where the solidity code is written. We write our smart contract here that we want to be deployed.

#### Inbox.test.js

We check our solidity code here if every function is doing its job correctly or not. We make use of the local network Ganache for checking the codes.


#### Deploy.js

When we have checked our code and run tests in Inbox.test.js, its time to run it on an etherium network. Here I have used Rinkeby test network and Infura api as the provider.













