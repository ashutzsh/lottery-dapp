We are going to create a lottery decentralised application. 
We are going to create the frontend using React.js, smart contract using Solidity, 
and connect the frontend and the smart contract using web3.js library.

We are going to deploy the smart contract over the Goerli testnet. To make a communication
with the Goerli testnet, we are going to use Alchemy. Alchemy will act as bridge between our 
smart contract and the Goerli testnet so that we can talk to the Goerli testnet. 
(There are other uses of Alchemy as well)

LOTTERY ALGORITHM:
We are going to create a smart contract and this smart contract will be handled by the manager. In order for particants to take part in the lottery, they need to pay a certain amount of fees in ethers. 
The manager of the contract will then call the function pickWinner().
To call pickWinner() there should be atleast 4 particants. 
All the ethers of the smart contract will be transferred to the winner of the lottery.