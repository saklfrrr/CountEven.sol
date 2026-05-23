# CountEven.sol
CountEven.sol
pragma solidity ^0.8.20;
contract CountEven {
    function count(uint[] memory arr) public pure returns(uint) {
        uint c;
        for(uint i=0;i<arr.length;i++){
            if(arr[i] % 2 == 0) c++;
        }
        return c;
    }
}
