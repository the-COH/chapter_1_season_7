# CanFundMe Submission

 ## Links

 * REPO: [github](https://github.com/mugrebot/CanFundMe)

 * Website: [TestNet App](https://canfundmecanto.vercel.app)


# Smart Contracts
- CanFundMeFactory: The factory contract that deploys CanFundMe campaigns
- EIPPY: A verifier contract using the EIP712 typed data standards
- PROFILE: A verifier contract using the EIP712 typed data standards for user profiles
- CanFundMe: The main crowdfunding contract that enables users to create and participate in crowdfunding campaigns


# Features
- CanFundMeFactory contract deploys individual CanFundMe campaigns
- EIPPY and PROFILE verifier contracts utilize EIP712 typed data standards for attesting to gitcoin scores/ipfs cids
- Gitcoin integration rewards projects with a Gitcoin score higher than 10, reducing platform fees to 0%
- IPFS integration allows customizable profiles with an IPFS hash pointing to a JSON object containing profile pictures and project descriptions
- Signatures and typed data attest to project ownership and the validity of information provided