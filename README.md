Create Your Own BEP-20 Token
BEP-20 has emerged as technical standard used for all smart contracts on the Binance Chain for token implementation. Plenty of well-known digital currencies use the BEP-20 standard, including BUSD, Trust Wallet Token (TWT), Pancake Swap (CAKE), and Mobox (Mbox).

Prerequisite
To create your own BEP-20 standard token, you need to install/Access:

MetaMask
ChainIDE
If you don't know how to set up development environment, you can follow our guidelines to install MetaMask and create your projects by clicking here

What is BEP-20?
BEP-20 is a token standard on BNB Smart Chain (BSC) that extends ERC-20, the most common Ethereum token standard. You can think of it as a blueprint for tokens that defines how they can be spent, who can spend them, and other rules for their usage. Due to its similarity to BNB Beacon Chain’s BEP-2 and Ethereum’s ERC-20, it’s compatible with both.

Optional functions for ERC-20:
name

symbols

decimals

Mandatory functions for the BEP-20 Token:
Total supply — the amount of tokens that exist at the moment

Balance of — shows the balance for the address

Transfer — sends a certain amount of tokens to the address

Transfer from — used for exchanging tokens among users who have these tokens

Approve — verifies that your the wallet address is eligible to send tokens to another user

Allowance — shows whether or not a user has a balance sufficient to send tokens to someone else

These 6 functions are recognized and identified by other smart contracts. In a nutshell, the ERC20 token plays well with other smart contracts, and that’s why it is so popular.

Mandatory Functions for ERC-20 Token

Extra Function for Airdrop:
An extra function with name Airdrop has been included in the ERC-20 token that is used to get tokens every time you execute it, a specific amount of token will be added to the owner's account and to the total supply.

Regarding Interface with .html extension. Don't forget to change the ABI code of the smart contract in html file with your smart contract ABI code, and change the contract address with your contract address that you will get after deploying your smart contract on the blockchain. The ABI code can be gotten from the compile panel, after successful compilation under the compile button you can see an option for ABI and BYTE CODE, you can copy the ABI code by clicking on the icon in front of ABI.

image-20221108173144183

Once you have successful compiled the smart contract, now you can deploy it to a blockchain,. After the successful deployment, a contract address will be assigned to a smart contract, by using the smart contract and ABI code, you can interact with your smart contract. Figures below show different methods to get an information about the deployed smart contract. 1st Figure shows the contract information from IDE output panel and the second figure shows the contract information. You can use get contract information by following any of these methods.

image-20221108173716727

Once you have the contract address and the ABI, you can code using web3, a combination of HTML,CSS, and JavaScript to interact with your deployed smart contract. We provide an example for you but need to change ABI and address to your own ERC20 token.



ChainIDE supports the HTML, .sol, .md, and all other file formats that are needed to create your dapps.

Once you click on the output view, you can see an interface according to your HTML file, and you can interact through this with your deployed smart contract.



As we can see the output of the airdrop.html file. In this file we interact with ERC-20 standard token. An extra function for getting airdrop coins is added to the ERC-20 token, and it will increase the token(you'll get tokens) each time you execute your Get Airdop function.



