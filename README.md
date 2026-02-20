# contract36.sol
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.0;

// Web3 ownership smart contract
contract Contract36 {
    address public owner;

    constructor() {
        owner = msg.sender;
    }
}
