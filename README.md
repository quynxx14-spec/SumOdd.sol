# SumOdd.sol
SumOdd.sol
pragma solidity ^0.8.20;
contract SumOdd {
    function sum(uint[] memory arr) public pure returns(uint) {
        uint s;
        for(uint i=0;i<arr.length;i++){
            if(arr[i] % 2 != 0) s += arr[i];
        }
        return s;
    }
}
