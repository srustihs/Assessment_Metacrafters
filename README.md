# Assessment_Metacrafters
MyToken

This Solidity program is a basic implementation of a custom token on the Ethereum blockchain. The purpose of this program is to demonstrate the syntax and functionality of Solidity by providing a simple example of how to create a token with minting and burning capabilities.

Description

This program defines a contract called "MyToken" which has the following public variables:

"tokenName": a string representing the name of the token (in this example, "Srusti")
"tokenAbbry": a string representing the abbreviation of the token (in this example, "MTA")
"totalSuply": a uint representing the total supply of the token (initialized to 0)
The contract also has a mapping variable called "balances" which maps addresses to uints, representing the balance of each address in the token.

The program defines two functions:

"mint": a function that takes two parameters (an address and a value) and mints new tokens, increasing the total supply and the balance of the specified address.
"burn": a function that takes two parameters (an address and a value) and burns tokens, reducing the total supply and the balance of the specified address.
The "burn" function includes a conditional statement to ensure that the balance of the specified address is greater than or equal to the amount of tokens that are being burned.

Getting Started

To run this program, you can use Remix, an online Solidity IDE. To get started, go to the Remix website at https://remix.ethereum.org/.

Once you are on the Remix website, create a new file by clicking on the "+" icon in the left-hand sidebar. Save the file with a .sol extension (e.g., MyToken.sol). Copy and paste the code into the file.

To compile the code, click on the "Solidity Compiler" tab in the left-hand sidebar. Make sure the "Compiler" option is set to "0.8.18" (or another compatible version), and then click on the "Compile MyToken.sol" button.

Once the code is compiled, you can deploy the contract by clicking on the "Deploy & Run Transactions" tab in the left-hand sidebar. Select the "MyToken" contract from the dropdown menu, and then click on the "Deploy" button.

Once the contract is deployed, you can interact with it by calling the "mint" and "burn" functions, passing in the appropriate parameters.

Authors

This program was written by an anonymous author.

License

This project is licensed under the MIT License - see the LICENSE.md file for details.
