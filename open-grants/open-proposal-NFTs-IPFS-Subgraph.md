To submit a proposal, please create a PR adding a file to this folder filling out this template. Please title your file `open-proposal-title.md`, replacing `title` with the name of your project.

# Open Grant Proposal: NFTs IPFS Subgraph

**Name of Project:** NFTs IPFS Subgraph

**Proposer:** Kredeum Team (https://github.com/Kredeum) 

**Do you agree to open source all work you do on behalf of this RFP and dual-license under MIT and APACHE2 licenses?:** Yes

# Project Description

The goal of the “NFTs IPFS subgraph” project is to realize “NFT subgraph with IPFS metadata”

Enhance existing EIP721 subgraph (from wighawag, link below) with IPFS metadata to improve display performance of NFT wallets.
https://thegraph.com/hosted-service/subgraph/wighawag/eip721-subgraph

With only one request needed to get all NFTs and their metadata, instead of one request per NFT, saving time, network bandwidth and server resources.

## Value

Kredeum team wants to develop a subgraph that everyone can use and benefit from.

By indexing IPFS metadata when present, NFT wallets and dapps will be able to display NFTs quicker. This subgraph will be primarily used in our Kredeum NFTs dapp, a decentralized NFT platform.

The IPFS subgraph will be deployed on most popular EVM compatible blockchains.

Taking into account that not all NFTs have their metadata on IPFS, some on centralized networks, some on other technologies (like ArWeave) the project will be extended in a second phase for this purpose (and should change its “IPFS only” name !).


## Deliverables

Please describe in details what your final deliverable for this project will be. Include a specification of the project and what functionality the software will deliver when it is finished.

## Development Roadmap

Phase 1 : November 2021 : Starting from previous work on this IPFS subgraph, study and solve all technical problems  identified, deployment on testnet

Phase 2 : December 2021 : Deploy on The Graph mainnet for the Matic network followed by deployment on other targeted networks

Phase 3 : January 2022 : Study integration of NFT metadata coming from ArWeave (and potentially other technologies, Swarm ?...) 
 
Namely, we are targeting Ethereum, Arbitrum, Optimism, Polygon, Celo, Fantom, IoTex and Avalanche blockchains.


## Total Budget Requested

We estimate the work up to 15 days needed for study, develop and deploy these IPFS subgraphs, for a budget of 13.5 K$

The work will be led by our Blockchain Architect.

## Maintenance and Upgrade Plans

Specify your team's long-term plans to maintain this software and upgrade it over time.

# Team

## Team Members

- Alain Papazoglou, BlockChain architect with 20+ years of experience in SaaS development. He founded three startups.
- Yoann Lesouef, Project manager, working as a project manager for 15 years for multinational companies 
- Alexandre Rouillet, UX and UI designer, has 12 collaborators in marketing and communication companies.
- Baptiste Julien, FrontEnd developer, with 20 years of experience and founded three startups.
- Alexandre Papazoglou, Founder @Hxrobot, and crypto trader
- Kevin Boulanger, Business Developer, has ten years in finance and wealth management. 

## Team Website

www.kredeum.com

## Relevant Experience

A first try has been developed during ETHGlobal Web3 Hackathon with the “NFT import” project. The resulting subgraph on the mumbai testnet can be queried on the link below :

https://thegraph.com/hosted-service/subgraph/zapaz/eip721-mumbai?query=metadata

This can be a good technical demonstration of the project : how to extract metadata from IPFS and index them on The Graph.

Deployment of this subgraph on other networks failed due to various problems that have to be solved in this project.

   

Kredeum already allows the possibility for everyone, to easily create, mint, and sell NFTs in a few clicks, and for the moment, two solutions we developed are now live : 
-Our Kredreum WordPress Plugin gives the opportunity to 64M wordpress website editors to mint and sell existing media already uploaded on their website. 
-Our interactive NFT decentralized wallet, offering the opportunity to create multi-collection through smart contracts.

1st prize with polygon during GR9 and IPFS Prize ” Framework Support '' with Protocol Labs, we want to implement IPFS to our development to make life even easier!

## Team code repositories

Please provide links to your team's prior code repos for similar or related projects.

# Additional Information

Please include any additional information that you think would be useful in helping us to evaluate your proposal.
