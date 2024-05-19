## Decentralized Micro-Funding with MicroSprint

### Inspiration
The idea behind MicroSprint emerged from a desire to bridge the gap between blockchain technology and real-world applications, while also exploring the functionalities of Substrate/Polkadot and Chainlink. Inspired by platforms like Kiva, which connect lenders with small borrowers, MicroSprint aims to leverage blockchain to facilitate micro-funding for community projects.

### What it Does
MicroSprint brings real-world loans onto the blockchain, allowing users to view and contribute to various projects. Through the issuance of a new token called MicroSprint token (MSPT) and the integration of Chainlink oracles for price feeds, users can lend MSPT to projects of their choice. Once the loan amount in MSPT reaches the target, it is converted to USD to fund the project. Meanwhile, an equivalent amount of MSPT is staked or pooled, allowing users to earn rewards over time. Borrowers repay their loans in MSPT, with lenders receiving repayments along with a portion of the staked assets and rewards.

### How We Built It
The project involved several key components:
- Development of a Substrate blockchain for MicroSprint
- Integration of a custom Chainlink External Adapter to retrieve aggregated asset prices
- Implementation of pallets for managing price feeds, loans, and lenders within the MicroSprint blockchain
- Creation of a user interface for interacting with the MicroSprint blockchain

### Challenges We Ran Into
The project presented various challenges, including:
- Coding in Solidity, Rust, and Go for the first time
- Navigating the complexities of Chainlink and Substrate integration
- Updating the Chainlink/Substrate bridge to align with the latest Substrate versions
- Ensuring timely development while learning new languages and technologies

### Accomplishments That We're Proud Of
Despite the challenges, we successfully developed a functional proof of concept for MicroSprint. We're particularly proud of:
- Bringing real-world loans onto the blockchain and enabling user contributions
- Leveraging Chainlink oracles for accurate price feeds and loan management
- Deploying the MicroSprint blockchain and associated components online for testing and demonstration

### What We Learned
The project provided valuable learning opportunities, including:
- Gaining proficiency in Solidity, Rust, and Go
- Understanding the workings of Chainlink and Substrate
- Implementing price feed management and loan processing within a blockchain environment
- Deploying and testing blockchain applications in a real-world setting

### What's Next for MicroSprint
While MicroSprint is currently a proof of concept, there are several potential avenues for future development, including:
- Contacting Kiva to explore collaboration opportunities
- Exploring additional features and functionalities within the Substrate ecosystem, such as the Democracy pallet
- Investigating how DeFi can enhance the micro-funding process within MicroSprint
- Engaging with the blockchain community to gather feedback and ideas for further improvement

### Built With
- ExternalAdapter
- Go
- JavaScript
- Kubernetes
- React
- Rust
- Substrate

