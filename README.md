# Project: Create a Token
This project's goal is to help you get a better concept of how to create and burn a token and how it operates. You can learn how to write codes to burn and transact tokens by studying this example.
## Description
A token called Token.sol has a contract that explains how to mint, burn, and transact with tokens. If you have 1000 tokens, for instance, you can burn half of them to make 500 tokens, and you cannot burn them again if the token you burn is higher than the 500 tokens you already have and has not altered if you burn them in that manner. The main takeaway from this is that you can create, transfer, and monitor tokens as they are processed on this project.
## Getting Started
What are the conditions that must be met for this to function? A Ethereum environment is the first requirements that you need. The Remix-Ethereum IDE is the ethereum environment that we will be using, which can be accessed by desktop computers or web browsers.
### Installing
*We must create a specific environment before using Ethereum and anything else you choose that supports Ethereum, including various IDEs like Metamask, Remix, Geth, and so on. As soon as you've made your decision, you must open the Token.sol file and run it on the IDE you've chosen.
### Executing Program
*Open the Remix-Ethereum IDE.

*If you don't have the auto compiler set, click on the Solidity Compiler icon on the left side of the screen. This will compile the Solidity code.

*Once the code is successfully compiled, proceed to the next step

*Look for the Deploy and Run transaction icon, located underneath the Solidity Compiler section. Click on it. This will open the Deploy and Run Transactions panel.

*In the Deploy and Run Transactions panel, you will find the deployed contract named 'MyToken'. Below the contract name, you will see two functions listed: 'mint' and 'burn'.

*To mint tokens to your address, locate the 'mint' function and provide the required parameters. Enter the desired '_address' (your address) and '_value' (the number of tokens you want to mint). Click on the 'mint' button to execute the function.

*The transaction will be processed, and if successful, the total supply of tokens will increase, and the balance of your address will be updated accordingly.

*To burn tokens from your address, locate the 'burn' function and provide the required parameters. Enter the '_address' (your address) and the '_value' (the number of tokens you want to burn). Click on the 'burn' button to execute the function.

*The transaction will be processed, and if your address has a sufficient balance of tokens, the total supply will decrease, and the balance of your address will be updated accordingly.

*You can repeat the steps to mint or burn more tokens as needed.

Remember to review the details of the functions and provide the correct parameters to ensure successful execution.
## Authors
·Liana Claire N. Peñones
·Liana Claire Peñones (https://www.facebook.com/michaaaaaaaaan)
