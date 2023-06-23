from https://university.alchemy.com/course/ethereum/md/614ba41acd2a86000413f77a

install :
- git clone https://github.com/clementcadbury/alchemy_6_erc20deploy.git .
- npm init -y
- npm i dotenv
- npm i --save-dev hardhat
- npm i --save-dev @nomicfoundation/hardhat-toolbox
- npx hardhat
- npm install @openzeppelin/contracts

commandes :
- npx hardhat compile
- npx npkill
- npx hardhat run scripts/deploy.js --network sepolia

deployed at https://sepolia.etherscan.io/address/0x1aDfD5b00DAbC50F9002D5625069F53A69d3Cf35