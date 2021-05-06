# Blockchain-based-Bidding-system
A smart contract based Open Auction(both Simple and Blind Auctions) using Ethereum Blockchain
● We create smart contract for both Simple auction and Blind auction in Solidity
● A Solidity contract can act as an agreement between a buyer and a seller when selling an item remotely in E-Auction.
● We use web based Remix tool for compiling solidity smart contract.
● We can take inputs from the UI required for invoking the smart contract and then call the corresponding function
● The UI is created using HTML and CSS
● We start the Ganache-cli in local machine and connect to the global blockchain by selecting listening port 8545 in
Web 3 provider the Environment of Remix
● Exceptions are thrown when any of the following happens
  ○  If the bid is less than or equal to highest bid
  ○ If the bid is placed after bidding period is over
  ○ When the ENDAUCTION button is pressed before bidding period is over
  ○ ENDAUCTION is pressed more than once after bidding
● Once the bidding period is over and ENDAUCTION button is pressed then the highest bid is sent to the beneficiary
