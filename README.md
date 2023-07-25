# Martian-Token-Crowdsale
![alt=""](Images/application-image.png)
## KaseiCoin and KaseiCoinCrowdsale Contracts
___
### KaseiCoin Contract
The KaseiCoin contract is an ERC-20 compliant token contract developed using the Ethereum blockchain and OpenZeppelin library. This contract provides the basic functionality of a standard ERC-20 token, allowing users to transfer tokens, check balances, and approve token transfers.

### Features:
* ERC-20 Standard: The contract follows the ERC-20 token standard, making it compatible with various wallets and exchanges that support ERC-20 tokens.
* Token Minting: The contract inherits from the ERC20Mintable contract, which allows designated addresses to mint new tokens.
* Detailed Information: The contract inherits from the ERC20Detailed contract, enabling the specification of token name, symbol, and decimals during deployment.
### KaseiCoinCrowdsale Contract
The KaseiCoinCrowdsale contract is used to facilitate the crowdsale of the KaseiCoin token. It allows users to purchase KaseiCoin tokens at a predetermined rate by sending Ether to the contract. The contract utilizes the OpenZeppelin Crowdsale and 'MintedCrowdsale' contracts to manage the token sale process.

### Features:
* Crowdsale Functionality: The contract inherits from the Crowdsale contract, enabling a seamless process for participants to purchase tokens during the crowdsale.
* Minted Tokens: The contract uses the MintedCrowdsale contract, which mints new tokens upon purchase, ensuring a controlled token supply during the sale.
* Adjustable Rate: The crowdsale rate can be set during deployment to determine the number of tokens a user receives per Ether sent.
* Token Wallet: Ether raised during the crowdsale is sent to a designated wallet address for safekeeping.
### How to Use
1. Deploy KaseiCoin Contract: Deploy the KaseiCoin contract to create the KaseiCoin token. Set the token's name, symbol, and decimals during deployment.

2. Deploy KaseiCoinCrowdsale Contract: Deploy the KaseiCoinCrowdsale contract, passing the desired crowdsale rate, a wallet address to receive Ether, and the address of the KaseiCoin contract.

3. Conduct Crowdsale: Participants can purchase KaseiCoin tokens by sending Ether to the KaseiCoinCrowdsale contract. Tokens will be minted and allocated to the sender's address upon purchase.

4. Manage Token Supply: The KaseiCoin contract allows authorized addresses to mint new tokens. Ensure proper management of the token supply during and after the crowdsale.
![alt=""](Images/KaseiCoin.png)
![alt=""](Images/Crowdsale.png)
![alt=""](Images/Deployer.png)
![alt=""](Images/use1.png)
