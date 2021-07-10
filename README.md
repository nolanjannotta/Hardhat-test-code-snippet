# VS-Code-Hardhat-test-code-snippet

This code snippet works in VS Code and produces boilerplate smart contract smoke test.

Includes:
1. 5 total wallets imported, 1st is deployer
2. expect, should from chai
3. chai-as-promised
4. tests if address is proper
5. tests if from equals deployer
6. more to be added


TO USE:
1. be in VS Code
2. command + shift + P
3. type 'snippet'
4. Preferences: Configure User Snippet
5. scroll to find javescript
6. paste code under example snippet in javascript.json file
7. if example is snippet is uncommented, add "," at the "}" after "description"
8. change "prefix" to your choice. this is what you type in your empty file to paste the snippet -- default: testboi


troubleshoot:
1. npm install --save-dev @nomiclabs/hardhat-waffle ethereum-waffle chai @nomiclabs/hardhat-ethers ethers
2. npm install chai-as-promised
3. be sure to add constructor arguments if any
 
