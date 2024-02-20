Welcome to Block Chain Repo


* We send the transaction to one particular node 
* Node has entire copy of block chain
* Node pr kuch calculations hona start hojati hai, jisey mining kehty hai


* Block chain Basics Now 

Hash -------> Finger print data 

Block
Nonce
Data
Hash
Mine --------> Mine krny pr humy wo Satisfied green signal ka Nonce number dega

Blockchain ------------> Chain Of Blocks   
Distributive Blockchain ------------> Chain k peers bnaanty hai hum, agr data aik jaga change hoga to peers ( Copies ) s identify hojayega hash s 

* TOKENS
* We don't remember the bank account money, only the money that is used for transactions
* COIN BASED TRANSACTIONS


* Hum aik hash dhoond rahy hoty hai basically jismy leading zeros ho ( Looks for value of hash )

* Block Time -----> Amount of time that takes to convert into the hash to the target nonce value from zero is called the block time

* Etherium Networks -----> Target Block Time = 15 seconds

* --------------- SMART CONTRACTS --------------------

* An account controlled by code (developers)

* External Accounts -------> Koi bh bnasakta hai jese hum n bnaya?

* Solidity Compilor ---------------------> 1) Byte code ready for deployment 2) ABI

* ABI ------> Application Binary Interface ------->

* Inside Contract ------> We define instance variables and its going to exist for the life of the contract

public variable ( Everyone ) -----> Who has access to see the content of this variable

Storage Variables -----------------> It will be automatically stored in the contract with the blockchain

* Constructor Functions -----------> If the function has the same name as the contract
* Constructor Functions called one time automatically when the contract is created
* Public -----> Any one can use this function
* Private ----> Only contract can use this function
* View || constant ----> if it can access data but not modify it
* Payable (Important)
* Return is only going to be used when the function marked as view or constant means it doesnt modify the value
