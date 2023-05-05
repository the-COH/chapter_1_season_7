# Background
Canto contract owners can claim a small share of gas fees spent when executing their contracts as part of Canto’s Contract Secured Revenue (CSR). 


These funds are mostly tangential to the business models of these contracts and are not typically necessary for their success. 

# Problem
Canto doesn't yet have a circular public goods funding ecosystem

# Solution
csrDAO aims to bootstrap Canto's public goods ecosystem by enabling contract owners to redirect their CSR towards funding public goods.

# How it works
We have 3 contracts
- `csrDAOTreasury.sol` - The contract which holds user funds, and users to stake or donate CSR
- `csrDAOToken.sol` - The CSR token contract that is minted to users every time they maek a donation
- `csrDAOGovernor.sol` - The contract that allows users to create and vote on proposals to fund public goods

The frontend is built using React and uses Thirdweb tooling for smart contract interactions. 

