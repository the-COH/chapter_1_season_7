# Retrophones - NFT permitted communication

## What is Retrophones?

Think of us as the Telegram for NFT’s -
RetroPhones will be the first encrypted NFT-to-NFT communication protocol enabling users to send encrypted messages
between NFT’s and the ability to broadcast data to all holders of an NFT collection.

At the same time we are creating a collection of NFT’s that will be the first to use this protocol. The NFT’s can be locked and
unlocked to receive parts of the message sending fees. The NFT’s will be a homage to mobile phones inspired by The Matrix.

Our target audience will be the creators and collectors looking to add significant value to an NFT that previously was
just an image - now with the ability to hold important data.

We have been working on creating an outstanding utility with a homage to mobile phones inspired by The Matrix

The solution is the ability to send and store valuable data attached to an NFT - an unalterable accounting system, an
indestructible record, a truly authentic method of encryption.

Canto is naturally transparent, easily accessible for builders and free from financial structures - The perfect platform
and community for RetroPhones to evolve with.

## What is Canto?

Canto is a decentralized, open-source, and community-driven project. It is a platform for building and running DAOs, and
it is a DAO itself. Canto is a community of builders, thinkers, and doers. We are a community of communities, and we are
building the future of DAOs.

## Current Status of the Project after the Hackathon

You can test on Canto Testnet:
* Minting: https://retrophones.io/mint
* Sending messages: https://www.retrophones.io/messaging/broadcast
* Receiving messages: https://www.retrophones.io/messaging/receive

### TLDR
We have a working prototype of the RetroPhones NFT’s and the ability to send encrypted messages between them. 

This works:
* Minting NFT’s from a frontend
* Sending unencrypted broadcast messages to all holders of an NFT collection
* Receive unencrypted messages from a holder of an NFT collection
* Creating NFT artwork from SVG layers and metadata randomly
* Locking phones to receive parts of the message sending fees.

This is still in progress:
* Sending encrypted messages between NFT’s
* Receiving encrypted messages between NFT’s
* Storing encrypted messages on-chain
* Lowering the size of each SVG layer (mainly the phones) to fit the 24kb limit
* Adding more Retrophone Models as SVG layers
* Adding other collections to the protocol to enable communication between different collections

### More Detailed

We have a working prototype of the RetroPhones NFT's and the ability to send encrypted messages between them. 
We can mint NFT's from a frontend and send unencrypted broadcast messages to all holders of an NFT collection. 
We can also receive unencrypted messages from a holder of an NFT collection, create NFT artwork from SVG layers and 
metadata randomly, and lock phones to receive parts of the message sending fees. 
We are still working on sending and receiving encrypted messages between NFT's, storing encrypted messages on-chain, 
lowering the size of each SVG layer to fit the 24kb limit, adding more Retrophone Models as SVG layers, adding other 
collections to the protocol to enable communication between different collections, and enhancing the frontend to be 
more user-friendly.

#### Open points / TODOs
* We need to create more tests for the contracts (or tests at all ;)
* There are some problems with the randomness of the phones. We need to dig deeper into this.
* We need to lower the size of the SVG layers to fit the 24kb limit
* We need to add more Retrophone Models as SVG layers
* We need to add other collections to the protocol to enable communication between different collections
* We need to implement the encryption logic for the messages
* We need to add a token gate for the messages to retrieve
* The frontend need to be enhanced and the process needs to be more user friendly
* The frontend needs to be connected to the encryption logic
* We need to add a way to send encrypted messages to a specific NFT (frontend)
* We need to add a way to receive encrypted messages from a specific NFT (frontend)
