pragma solidity ^0.8.10;

contract Wallet {
    address payable public owner;

    constructor() {
        owner = payable(msg.sender);
    }

    receive() external payable {}

    function getBalance() external view returns (uint) {
        return address(this).balance;
    }
}
