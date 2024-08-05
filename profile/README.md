# DAO of the Ring 💍

DAO of the Ring is a tool for Decentralized Autonomous Organizations (DAOs) that innovatively uses ring signatures to ensure privacy. This unique approach enables the toolkit to provide privacy to DAO members through token-gated authentication based on ring signatures.  

## Key Features

- **Privacy-Preserving Authentication:** DAO of the Ring leverages ring signatures to enable token-gated authentication, allowing members to interact with the DAO without revealing their individual identities.
- **Secure Voting System:** The project also innovates by incorporating ring signatures into the DAO's voting and proposal system, enhancing the privacy and security of the decision-making process.
-  **Decentralized Governance:** DAO of the Ring is designed to empower DAO members with a decentralized governance model, where decisions are made collectively and transparently.
-  **Metamask Snap Integration:** DAO of the Ring leverages [Cypher Lab's (it's us btw !) Metamask Snap](https://snaps.metamask.io/snap/npm/cypher-laboratory/alicesring-snap/) extension to seamlessly integrate the ring signature process into the user experience, providing a familiar and secure way for members to authenticate and vote within the DAO.

-  ## Ring Signatures 
Ring signatures are a type of digital signature that provide anonymity and privacy for the signer. The signer creates a signature using their own private key, but their identity is hidden within a "ring" of multiple public keys.

Key features of ring signatures:

- **Anonymity**: The signer's identity is obfuscated within the ring of public keys.
- **Unforgeability**: Only a member of the ring can create a valid signature.
- **Efficiency**: Ring signatures can be generated and verified efficiently.

Ring signatures have applications in areas like confidential transactions, whistleblowing, and e-voting.

For this project, we utilize [Cypher Lab's (it's us btw !) Metamask Snap](https://snaps.metamask.io/snap/npm/cypher-laboratory/alicesring-snap/) based on [Alice's Ring LSAG TS library](https://github.com/Cypher-Laboratory/Alice-s-Ring-LSAG-TS), a TypeScript implementation of the ring signature algorithm. 

## Project Structure :

The project is composed of several key components that work together to provide a secure and privacy-preserving governance solution for decentralized autonomous organizations. 
- [**Metamask Snap**](https://snaps.metamask.io/snap/npm/cypher-laboratory/alicesring-snap/) :The Metamask Snap (made by us !) is a crucial part of the Ring DAO system, as it allows users to create ring signatures seamlessly while maintaining the safety and user experience provided by the Metamask wallet. This integration enables DAO members to authenticate and interact with the DAO without revealing their individual identities.
- [**WebApp**](https://github.com/PimpMyRing/webapp) : The Ring DAO web application, built using VITE & React, provides a user-friendly interface for DAO members to interact with each other and the DAO's governance processes. The web application leverages the ring signature functionality to anonymize the users' identities, ensuring that their participation in the DAO is kept private.
- [**Backend**](https://github.com/PimpMyRing/backend) : The backend component, built using Express, serves as the intermediary between the web application and DB. 
The primary goal of the backend is to serve the frontend with the necessary dataset for constructing the ring signature. It also displays dynamic information such as proposals (stored on chain alongside with the votes) and live discussions.
- [**Smart-Contract**](https://github.com/PimpMyRing/Governance-contracts) : The Ring DAO smart contracts are deployed on Optimism and Base, enabling DAO members to vote anonymously using ring signatures. This approach ensures that the DAO's decision-making process is transparent and secure, while preserving the privacy of the individual members.

## DEMO :

To use the demo version of Ring DAO you can interact with our app : [COMING SOON]()  
You NEED to install Metamask in order to use our homemade SNAP, see [MetaMask](https://snaps.metamask.io/snap/npm/cypher-laboratory/alicesring-snap/)  
Nb: Do not import any of your main account, this is for test purpose only.

## Deployed and verified Smart Contracts
### SBT

| CHAIN     | SMART CONTRACT ADDRESS     |
|-----------|-----------------------------|
| Optimism MAINNET  |                 |
| Optimism TESTNET   | 0x4735435e8d4e9D03b3BcD1299D7102fAb0194bb7                |
| Base MAINNET   |                  |
| Base TESTNET   |                 |

### LSAG verifier

| CHAIN     | SMART CONTRACT ADDRESS     |
|-----------|-----------------------------|
| Optimism MAINNET  |                 |
| Optimism TESTNET   |                 |
| Base MAINNET   |                  |
| Base TESTNET   |                 |

### DAOofTheRing

| CHAIN     | SMART CONTRACT ADDRESS     |
|-----------|-----------------------------|
| Optimism MAINNET  |                 |
| Optimism TESTNET   |                 |
| Base MAINNET   |                  |
| Base TESTNET   |                 |

