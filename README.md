# Voting System Solidity
With the voting system, yes-no votes can be made on the blockchain. Voters are added to the list by the Ethereum address deploying the smart contract. A voter can only vote once. There are 3 stages in a vote : Created, Voting, Ended. These stages are stored with an enum veriable. After a vote is over, it is not possible to vote again on the same address contract. There are 4 main functions on the smart contract :

1.) addVoter()

2.) doVote()

3.) startVote()

4.) endVote()
