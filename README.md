# learning-blockchain-resources

Free course on fundamentals of blockchain and bitcoin: https://www.coursera.org/learn/cryptocurrency


# Ethereum

Building Dapps with Solidity, starting courses: https://www.zastrin.com/#course-3

Beginner tutorials on Solidity: https://karl.tech/learning-solidity-part-1-deploy-a-contract/


# Building Dapps

Environment:
- *testrpc* (running a local test blockchain).
- *Nodejs* (library for running javascript server-side).
- *Web3* (javascript library for interacting with the blockchain)
- *Solidity* (programming language used for building smart contracts)

## Running the test network
First, we run testrpc in the console in order to start up the test blockchain.

`testrpc`

The blockchain instance will be running and a number of accounts and private keys will be generated. 

## Compiling

We can compile our Solidity code by using *solc*. Start NodeJs by inputting `node` in the command line and then:

`code = fs.readFileSync('<path-to-file>').toString();`.

This reads the file and outputs a string representation of its contents. Now compile the code using solc:

`solc = require('solc');`

`compiledCode = solc.compile(code)`.





