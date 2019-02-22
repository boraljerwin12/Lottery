# Lottery

   1. Simple Lottery
 
 The bets made by the participants will be converted into a random hash and the play is only 1 time so it will only have a 1 winner. 1 transaction per 1 player and they don't need to bet a number or combinations of number just to be in a bet.
  
   •In Ethereum

Every ticket is worth 0.01 ether and after the contract is deployed, there is a certain amount of time programmed for it to close too. Once closed, any transactions will never be counted or accepted. 5 minutes after closing, the contract deployer can pick the winner in the system from all the participants randomly and the price depends to how many players are present there.
 
   •In Hyperledger
   
 It is also the same that there'll going to have a time duration for executing the program but the difference is that, the participants will have a chaincode for them in order to play. The thing here is that Hyperledger is a private blockchain so you should have to be in a certain group in hyperledger, we can say that only a specific area are able to do things inside of a certain program.
 And all of the other things are the same with ethereum such as how to play, the program running and buying tickets.
 
 
   2. Recurring Lottery
 
 Recuring Lottery is a continuous lottery game. One game after another when having a winner in that certain game and everyone can repeatedly enter this lottery either you won last round or you lose. It will continue not unless the program deployer stops it.
 
   •In Ethereum
   
 The game is divided into 2 processes, 1 is about the lottery deployer and the other is for the players. The deployer's process starts after starting the program. The game will have a specific durations of games depends to how many games the deployers will give. Then there will be a duration for the next round because of checking the winner and it will be notified in deployer's side. The deployer have a choice either to delete or keep the data on that certain game.
 
   •In Hyperledger
 
 There are 3 diagrams of Recurring Lottery in Hyperledger: Deployer, Ordere and the User. Deployer will deploy the chaincode and it will wait for the approval of the orderer so that the chaincode shall be endorsed. Then the deployer will be enrolled as an admin to start the game. They can also specify time duration of the game and draw the winner and they have an access to the outcome of games and can delete a game round.
 
 Meanwhile in the User diagram, all players will receive a web app to start betting in the game by enrolling to be able to start. They need to buy tickets in order to join a game and place their own bets. They can check their balance and can decide for their own whether to continue playing after winning or withdrawing the amount from winning.
 
 
   3. RNG Lottery
   
 RNG Lottery uses commit-reveal sequences for creating random numbers and every user shall submit commitment hash when buying. The commitment hash is a combination of user's address and other numbers which is only related to the user and they need to commit it in order to be a part of the game.
 
   •In Ethereum
 
 Users must register their IP Address and other random numbers that'll be converted into a hash wherein hash will be the gateway to the game. Users will buy tickets using hash and they need to reveal their numbers or else they can't participate to the game during the reveal duration. Then the admin will draw winner randomly to have a winner.
 
   •In Hyperledger
 
 Just like the same in Ethereum, ticket duration upon in buying and deploying chaincode. Duration will be based on reaching certain block for current game measurements. The only difference is that all of the users know each other except for their private hash number, when the block reach the reveal duration, all of them must reveal their secret numbers or they won't be able to participate. Then the game will be the same to other platform.
 
 
   4. Powerball Lottery
   
 Users will pick six numbers per ticket just like how a normal lottery runs but the difference is that, the first five need to be in the range of 1-69 and the last number which is a special powerball number ranges from 1 to 26 that offers extra rewards. Game is drawed every 3-4 days and the winning tickets consisting of five standard and 1 special powerball number is picked. The prizes are paid based to the number of winning numbers as you picked.
 
   •In Ethereum
 
 User msut first check the maximum number of the powerball before buying a ticket. After buying a ticket worth 0.02 ether, the account will draw from numbers 1-69 on first 5 and 1-26 on the last number. After drawing, users can check winning combinations and users can withdraw the jackpot prize that depends to the winning numbers matched to the user's picked numbers.
 
   •In Hyperledger
 
 It is also the same in Ethereum but the difference is that there are additional patterns in technical areas. First, the deployer must deploy the chaincode in order to have a Powerball game then deploy itself to be an admin. Then it must approve the deployed chaincode and in User's part. They need to register to enter the game. Then the game is also the same as in Ethereum.
 
 
 
   Reference
   
 Ethereum reference: Iyer, K. & Dannen, C. (2018). Building Games with Ethereum Smart Contracts (pp. 171-209). Brooklyn, New York: Apress
