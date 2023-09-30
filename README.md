# NFT Minting and Whitelisting Dapp

This is a decentralized application (Dapp) that allows you to create, mint, and whitelist non-fungible tokens (NFTs) on the Ethereum blockchain. NFTs are unique digital assets that can represent anything from art, music, games, collectibles, and more. This Dapp was built alongside the sophomore track of LearnWeb3Dao. With this Dapp, you can:

- Create your own NFTs with custom metadata and images
- Mint your NFTs to the blockchain and receive an ERC-721 token
- Whitelist your NFTs to restrict who can buy or sell them
- Transfer your NFTs to other users or marketplaces
## To try it out, visit: https://bcc-dapp.vercel.app/
## How it works

This Dapp uses the following technologies and tools:

- React: A JavaScript library for building user interfaces
- Next.js: A framework for building fast and scalable web applications with React
- Ethers.js: A JavaScript library for interacting with the Ethereum blockchain
- Solidity: A programming language for writing smart contracts
- Hardhat: A development environment for compiling, testing, and deploying smart contracts
- OpenZeppelin: A library of secure and reusable smart contract components

The Dapp consists of two main components:

- A smart contract written in Solidity that implements the ERC-721 standard for NFTs and adds a whitelist functionality
- A web interface written in React and Next.js that allows users to interact with the smart contract.

## How to use it

To use this Dapp, you need to have the following prerequisites:

- Node.js: A JavaScript runtime environment that allows you to run code outside of a browser
- npm: A package manager that allows you to install and manage dependencies for your projects
- MetaMask: A browser extension that allows you to access your Ethereum wallet and interact with Dapps

To run this Dapp locally, follow these steps:

1. Clone this repository to your local machine using `git clone https://github.com/yourusername/nft-dapp.git`
2. Navigate to the project directory using `cd nft-dapp`
3. Install the dependencies using `npm install`
4. Compile the smart contract using `npx hardhat compile`
5. Deploy the smart contract to a local network using `npx hardhat node`
6. Copy the contract address from the terminal output and paste it in the `contractAddress` variable in `app/config.js`
7. Copy the contract ABI from `artifacts/contracts/NFT.sol/NFT.json` and paste it in the `contractABI` variable in `app/config.js`
8. Start the web server using `npm run dev`
9. Open your browser and go to `http://localhost:3000`
10. Connect your MetaMask wallet to the local network by selecting `Localhost 8545` from the network dropdown menu
11. Create, mint, whitelist, and transfer your NFTs using the web interface

## License

This Dapp is licensed under the MIT License.
