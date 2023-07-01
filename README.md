# ETH-AVAX-EVM-COUESE1

# STATEMENT Contract
This is a Solidity smart contract that demonstrates different statements using assert, revert, and require functions.

## License
This contract is using the MIT License.

## version 
Solidity ^0.8.17

## STATEMENT contract details
The statement contract provides the following functions:

### testAssert(uint num)
This function demonstrates the usage of the assert() statement.
It takes a parameter num and checks if it's not equal to zero using the assert() statement. 
If the condition evaluates to false, it indicates an internal error, and the transaction is reverted.
### split(uint _numerator, uint _denominator)
This function showcases the revert() statement. 
It takes two parameters _numerator and _denominator and checks if _numerator is greater than _denominator. 
If the condition evaluates to false, the function reverts and displays the error message "numerator should be greater than denominator". 
Otherwise, it performs the division operation and returns the result.
### multiply(uint a)
This function demonstrates the require() statement. 
It takes a parameter a and checks if it's greater than zero using the require() statement. 
If the condition evaluates to false, the function reverts and displays the error message "Value of a is zero, the result should not be zero". 
Otherwise, it multiplies a with the state variable b and returns the result.
## Usage
Make sure you have Solidity ^0.8.17 installed.

To use the Statement contract, follow these steps:
Deploy the contract on a compatible Ethereum development environment or network.
Call the testAssert() function, providing a non-zero value for the num parameter. If the provided value is zero, the transaction will revert.
Call the split() function, providing values for the _numerator and _denominator parameters. Ensure that the _numerator is greater than the _denominator to avoid reverting the transaction.
Call the multiply() function, providing a non-zero value for the a parameter. If the provided value is zero, the transaction will revert. The function will return the result of multiplying a with the value of the b state variable.
