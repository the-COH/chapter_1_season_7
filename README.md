## CanFundMe Submission

 # Links

 * REPO: [github](https://github.com/mugrebot/CanFundMe)

 * Website: [TestNet App](https://canfundmecanto.vercel.app)


## 🏗 BUILT ON Scaffold-ETH 2

# CanFundMe
CanFundMe is a decentralized crowdfunding platform built on Ethereum, designed to support projects and ideas with a simple, yet effective, funding mechanism. CanFundMe integrates Gitcoin and IPFS to support user profiles, organic growth, and reduce Sybil attacks. With a focus on user-friendly experience and enhanced security, CanFundMe aims to revolutionize the crowdfunding space.

# Features
- CanFundMeFactory contract deploys individual CanFundMe campaigns
- EIPPY and PROFILE verifier contracts utilize EIP712 typed data standards for increased security
- Gitcoin integration rewards projects with a Gitcoin score higher than 10, reducing platform fees to 0%
- IPFS integration allows customizable profiles with an IPFS hash pointing to a JSON object containing profile pictures and project descriptions
- Signatures and typed data attest to project ownership and the validity of information provided

# Smart Contracts
- CanFundMeFactory: The factory contract that deploys CanFundMe campaigns
- EIPPY: A verifier contract using the EIP712 typed data standards
- PROFILE: A verifier contract using the EIP712 typed data standards for user profiles
- CanFundMe: The main crowdfunding contract that enables users to create and participate in crowdfunding campaigns

# CanFundMe Campaigns
- Accept CANTO or NOTE 
- Allow creators to withdraw after their threshold is met.
- Allow funders to withdraw their contributions in the case that the threshold is not met within the time limit

# Gitcoin Passport flow
- submit passport
- check passport score
- sign the score
- verify score on canfundmefactory to receive 0% platform fees
- campaigns starter after verifying must be updated!
- uses Eippy.sol to verify/recover signatures

# IPFS Profile flow
- Choose a file, write a text description for your profile page
- Upload it to IPFS using their API
- Receive/Sign CID
- Add to profile contravt which verifies that the signer = owner of the can fundme campaign
- uses Profile.sol to verify/recover signatures

⚙️ Deployed using Vercel
⚙️ Built using NextJS, RainbowKit, Hardhat, Wagmi, and Typescript.

# Notes
-Front end information can be found in packages/nextjs such as pages/hooks/components/styling
-Smart contract information such as contract code/abis/deployment info can be found in packages/hardhat

## Requirements

Before you begin, you need to install the following tools:

- [Node (v18 LTS)](https://nodejs.org/en/download/)
- Yarn ([v1](https://classic.yarnpkg.com/en/docs/install/) or [v2+](https://yarnpkg.com/getting-started/install))
- [Git](https://git-scm.com/downloads)

## Quickstart

To get started with Scaffold-ETH 2, follow the steps below:

- yarn install
- yarn chain
- yarn deploy
- yarn start
