# Hello Blockchain (GUI Based)
*Simple Blockchain Implementation to Print Hello Blockchain Using Truffle & Ganache.*

*It is a GUI based project.*

### Smart Contract
```
// SPDX-License-Identifier: MIT

pragma solidity ^0.6.11;

contract Hello{

  string greeting;

  constructor() public{
    greeting = "Hello Blockchain";
  }

  function getGreeting() public view returns(string memory){
    return greeting;
  }

  function setGreeting(string memory _greeting) public{
    greeting = _greeting;
  }
}
```

### Ganache Screeshots

*Post deploying the Smart Contract*
![](Output/deployed.png)

*Output with constructor set greeting*
![](Output/Hello_Blockchain.png)

*Output with setGreeting() set greeting*
![](Output/Hello_World.png)

*Transactions pre calling Smart Contract Functions*
![](Output/transactions.png)

*Transactions post calling Smart Contract Functions*
![](Output/Transactions_1.png)
