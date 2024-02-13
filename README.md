# Project Title

OWNERSHIP CONTRACT

## Description

This Solidity code defines a smart contract called `OwnershipContract` that facilitates ownership management. Upon deployment, the contract's constructor sets the deploying address as the owner. The contract provides three functions: `onlyOwner`, `onwerHere`, and `Owner`, each validating the caller's identity against the contract's owner address using different mechanisms. The `onlyOwner` and `onwerHere` functions utilize `require` and `revert` statements, respectively, to restrict access to only the contract owner, while the `Owner` function employs an `assert` statement for validation. This contract ensures that only the designated owner can execute certain functions, enhancing security and control over contract operations.

## Getting Started

### Installing

* Go to this github repository which is made public for easy access and you can find ethAvax.sol file. Compile and deploy that code snippet to remix.etherium.org.
* There isn't need for making any changes for the code snippet.

### Executing program

ethAvax.sol: This is a simple contract that was programmed just to check that whether the owner of the contract is the same as one using the contract or not. For this, we used three error methods- require(), revert(), and assert() and all these three functions are performing the same job.
