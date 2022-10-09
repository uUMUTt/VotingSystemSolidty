# Voting System -Solidity
With the voting system, yes-no votes can be made on the blockchain. Voters are added to the list by the Ethereum address deploying the smart contract. A voter can only vote once. There are 3 stages in a vote : Created, Voting, Ended. These stages are stored with an enum veriable. After a vote is over, it is not possible to vote again on the same address contract. The contract starts with an address deploying it in the constructor, and ends when the offical address ends voting with the endVote() function. There are 4 main functions on the smart contract :

1.) addVoter(address _voterAddress, string memory _voterName) 

2.) doVote(bool _choice) 

3.) startVote()

4.) endVote()
