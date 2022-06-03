A Decentralized Portfolio

In this stack I leverage a deployed Solidity smart contracts ABI to deploy a simple portfolio website that uses the onlyOwner modifier as a permission to add to the site.  If the actor's address does not match the original owner of the contract the portfolio is strictly view olny. All content is stored via IPFS and queryed via a subgraph deployed on the graph network using graphql.

This Project was built using Hardhat and Next.js

Try running "npm run dev" in terminal for a dev enviroment || "npm run build && npm start " for a production build and deployment.




