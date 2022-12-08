Here is a basic outline of a two player NFT smart contract game that uses NFT pokemon that battle each other:

Create two separate ERC-721 contracts, one for each player, to manage their respective NFT pokemon.
Each player will have a unique wallet address and will be able to mint their own NFT pokemon to their contract.
The game will have a game contract that will manage the rules of the game and the battle between the two NFT pokemon.
When a player wants to initiate a battle, they will call a function on the game contract, passing in the IDs of the NFT pokemon they want to use for the battle.
The game contract will then determine the winner of the battle based on the characteristics of the NFT pokemon (e.g. their attack and defense values).
The game contract will then update the ownership of the NFT pokemon to reflect the winner of the battle.
The game contract will also handle any other necessary bookkeeping, such as updating a leaderboard to track the winners of battles.
Note: This is just a basic outline, and there are many ways to implement a NFT game. This is just one possible approach.
