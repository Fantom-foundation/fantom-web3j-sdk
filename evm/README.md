# evm

This is an embedded standalone Ethereum EVM and ledger running
within a Java process, which can be used for unit and integration
testing your Web3j projects. 

Everything runs within the JVM process, including EVM bytecode, which
allows for easy debugging of Solidity smart contracts. There is no need to start up
external Geth / Opera nodes.

## Getting started

You may use [web3j-unit](https://github.com/web3j/web3j-unit)
project, allowing you to run unit and integration tests without the need
to start an Ethereum node.

A demo is available on the [example project](./evm-example).

One can do FTM transactions, contract deployment and simple contract interactions. 
Using the ConsoleDebugTracer, you can step through the EVM bytecode, inspect the stack and also see
where in the related solidity code we're currently at.
The demo also show to how get started with the `EmbeddedWeb3jService`.
