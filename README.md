# ETH-AVAX-EVM-COUESE1

# SmartContract
SmartContract is a Solidity smart contract that demonstrates the usage of the require, assert, and revert functions. It allows you to manipulate and control a value stored in the contract.

## Prerequisites
Solidity 0.8.0 or higher

## Getting Started
The SmartContract provides the following functions:

### addValue(uint _value) public
This function demonstrates the usage of the assert() statement.
Adds the parameter _value to the existing value and updates it. 
It uses the assert function to ensure that the resulting newValue is greater than the original value. 
If the assertion fails, indicating an invalid state, the transaction is reverted.
### subtractValue(uint _value) public
This function showcases the revert() statement. 
Subtracts the parameter _value from the existing value and updates it.
It checks if newValue (the result of the subtraction) is less than the original value.
If it is, the value is updated. If the condition fails, indicating that the value would become negative, the transaction is reverted with an error message.
Otherwise, it performs the division operation and returns the result.
### setValue(uint _value) public
This function demonstrates the require() statement. 
Sets the value of value by passing a parameter _value.
It checks if _value is greater than zero using the require function.
If the condition is not met, the transaction reverts with an error message.

## License
This project is licensed under the MIT . 

