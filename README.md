# Average.sol
Contract deployed via Web3 Average.sol
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract Average {
    function avg(uint a, uint b) public pure returns (uint) {
        return (a + b) / 2;
    }
}
