# Move Indexer

- **Team Name:**  move-index

### Overview

In the realm of Web3 indexing, the Move Indexer is an innovative Rest/GraphQL service meticulously designed to simplify interactions with assets on Move-based blockchain protocols. This service has been purpose-built to function as a robust data layer for various assets, including smart contracts, within decentralized applications (dApps). It leverages the user-friendly features of GraphQL and REST API to streamline this process.

Presently, developers encounter significant hurdles when dealing with assets interactions on Move based blockchains due to the intricacies and time-consuming nature of querying. The Move Indexer steps in to alleviate these challenges by offering an intuitive GraphQL interface, thereby significantly reducing the time and effort required to access and query these assets.

The Move Indexer offers several key advantages, including its primary focus on ease of use, remarkable versatility catering to a wide range of use cases, and a strong commitment to bridging the gap between developers and blockchain utilization and documentation. It achieves this while adhering to the principles of decentralization and open-source development, which underscores its dedication to safeguarding user privacy by abstaining from data collection.

By effectively reducing the time and complexity associated with querying assets and presenting a more user-friendly interface, the Move Indexer aspires to promote the growth and evolution of the Web 3.0 ecosystem within the realm of Move-based blockchain technology.


### Project Details


1. **Project Overview:**
   The Move Indexer is an advanced infrastructure tool designed to address developers' challenges when querying data on the blockchain. It offers a more efficient and user-friendly way to interact with data using GraphQL.

2. **Getting Started:**
   To get started, make sure you have the necessary tools and dependencies in place. You'll need TypeScript, the Squid framework (ArrowSquid), and a Postgres database. Additionally, ensure you have a .env file with the required environment variables.

3. **Project Structure:**
   The project has a well-organized structure, including the following directories:

   - **Generated Model/Server Definitions:** These contain the definitions for the data models and server endpoints.

   - **Server Extensions:** This directory may include custom server extensions or middleware.

   - **Data Type Definitions:** Here, you'll find the definitions for various data types used in the project.

   - **Mapping Modules:** Mapping modules are crucial for data processing, ensuring that data is structured and presented correctly.

4. **SDK Integration:**
   The Move Indexer team has also developed a TypeScript-based SDK that can be easily imported into your project. This SDK simplifies interactions with various data sources, making it accessible for developers of all levels. You can find the SDK documentation and integration instructions in the project resources.

5. **Use Cases:**
   Consider the potential use cases for the Move Indexer. For instance, you can create innovative applications that manipulate and query data, utilizing the capabilities of the Move Indexer. This tool opens up a wide range of opportunities for developers to explore.

6. **GraphQL Interface:**
   The Move Indexer primarily provides a GraphQL interface for querying data. Developers can leverage this interface to interact with various data sources. You can refer to the GraphQL documentation for specific queries and mutations.

7. **Deployment:**
   When your project is ready, make sure to configure it using the environment variables in the .env file. Deployment can be tailored to your specific requirements and hosting platform.

8. **Contributions and Enhancements:**
   As the Move Indexer is open-source, you're encouraged to contribute to its development and enhancement. The community welcomes suggestions, bug fixes, and feature additions to make the tool even more powerful and user-friendly for data-related applications.

9. **Conclusion:**
   By using the Move Indexer, developers can streamline the querying and manipulation of data on the blockchain. This not only saves time but also makes it easier to build innovative and user-friendly decentralized applications within the Web 3.0 ecosystem. The Move Indexer is a valuable resource that simplifies and accelerates the development of blockchain-based applications, providing efficient access to a wide range of data sources.

#### Architecture 🏗

1. **Architecture Overview:**
   The architecture of this Web3 data indexer is designed with a focus on simplicity and efficiency, ensuring a seamless interaction with various data sources within the Web3 ecosystem.

2. **Language and Reliability:**
   At the core of this architecture is TypeScript, a statically typed superset of JavaScript. TypeScript ensures codebase robustness and reliability, allowing early error detection during development and the creation of maintainable code.

3. **Data Processing Framework:**
   Data processing is handled by leveraging the ArrowSquid framework. ArrowSquid is a powerful tool that efficiently processes and indexes blockchain data. It provides a range of utilities for defining and running data processing tasks, simplifying the handling of complex data processing requirements.

4. **Database System:**
   This architecture interacts with a Postgres database, a powerful open-source object-relational database system. Postgres extends the SQL language and provides robustness, scalability, and high-performance capabilities for handling large volumes of data.

5. **Data Flow:**
   The architectural flow involves several layers:
   - Data is obtained from various sources, including SubSquid archives (pre-indexed storage) and RPC nodes for real-time data.
   - When new data events are obtained, they are automatically processed by defined handlers. Data is then stored in the Postgres database, providing a structured and scalable storage solution.

6. **Data Access and Querying:**
   To expose the data to clients, a GraphQL interface is provided. GraphQL is a powerful query language for APIs and a runtime for executing those queries with existing data. It allows clients to request precisely the data they need, optimizing performance and enhancing developer tools.

7. **Project Structure:**
   The project's structure is organized into several key directories:
   - `src/generated`: Contains model and server definitions generated by code generation tools.
   - `src/server-extension`: Includes modules with custom type-graphql-based resolvers.
   - `src/types`: Houses data type definitions for chain events and extrinsics, generated by typegen.
   - `src/mappings`: Contains the mapping module for data processing.
   - `lib`: Stores compiled JavaScript files, mirroring the structure of the `src` directory.

8. **Environment Configuration:**
   The project configures environment variables defined in a `.env` file or supplied via the shell. This approach allows for flexible and dynamic configuration management without codebase alterations.

9. **Client-First SDK (Uniquery):**
   As a second state-of-the-art component, the architecture includes a client-first SDK named Uniquery. Client applications can effortlessly integrate this SDK by importing the Uniquery package via ESM/CJS (JavaScript targets). The SDK offers a query builder implementation that simplifies data retrieval, such as `client.getCollectionById(id)`. Additionally, to accommodate developers familiar with REST API, a similar fetch strategy is implemented, enabling direct data retrieval from SubSquid without third-party involvement. The REST endpoint can be accessed using syntax like `$fetch(/collectionById/${id})`.

This architecture is designed to create an efficient and user-friendly framework for managing and querying data within the Web3 ecosystem, ensuring robustness, reliability, and scalability.
![]()

#### Technology Stack 💻

- TypeScript
- Node.js
- Docker
- Postgres
- GraphQL
  

### Ecosystem Fit

The Web3 data architecture described here is a significant asset to the broader Web3 and data ecosystem. It addresses a variety of challenges that developers frequently encounter when working with blockchain data and data sources, making it an indispensable resource for various projects and applications within the ecosystem.

**Key Aspects of Ecosystem Fit:**

1. **Comprehensive Data Solution:**
   This Web3 data architecture fills a critical gap within the Web3 and data ecosystem by offering a comprehensive and versatile data solution. It simplifies the data handling and retrieval process, catering to a broad range of use cases.

2. **User-Friendly Interface:**
   One of the standout features of this architecture is its user-friendly GraphQL interface. This interface enhances the ease of interaction with data sources and empowers developers to make precise data queries efficiently.

3. **TypeScript-Based SDK:**
   The inclusion of a TypeScript-based SDK further strengthens its compatibility and appeal within the ecosystem. TypeScript adds robustness and reliability to the codebase, ensuring that developers can work with confidence.

4. **Scaffold Template for Rapid Development:**
   Developers can leverage the sub-scaffold UI template to expedite the project setup and development process. This template serves as a valuable resource for those looking to create innovative and user-friendly Web3 applications without getting bogged down in the initial setup.

5. **Target Audience and Value Proposition:**
   The target audience for this architecture includes a wide spectrum of Web3 projects and blockchain developers, ranging from newcomers to seasoned professionals. It offers significant value to these developers, enabling them to create more efficient and user-friendly Web3 applications. This architecture positions itself as a valuable resource for projects like [Move](https://Move.xyz/).

6. **Integration with AssetHub:**
   The architecture plays a vital role in the [Move](https://Move.xyz/) NFT marketplace, demonstrating its practical utility in real-world applications. Developers can learn from the examples of effective GraphQL queries and data retrieval using Uniquery.

7. **Competitive Advantage:**
   Within the competitive landscape of the Web3 and data ecosystem, this architecture distinguishes itself by focusing on NFT-oriented data solutions and providing a user-friendly interface. The inclusion of the sub-scaffold UI template further enhances its competitive edge, as it offers a ready-made foundation for new projects. The architecture's utilization by projects like [Subsocial]() and Move showcases its real-world effectiveness and positions it as a unique and valuable asset within the ecosystem.

8. **Commitment to the Common Good:**
   The architecture emphasizes its commitment to the Common Good by simplifying the development process and enhancing the efficiency of Web3 applications. This commitment aligns with the broader ethos of supporting open-source and community-driven solutions in the Web3 ecosystem.

In summary, this Web3 data architecture serves as a pivotal and distinctive resource in the Web3 and data ecosystem. Its user-friendly approach, TypeScript integration, versatile template, and real-world applications make it a valuable asset for a wide range of developers and projects, ultimately contributing to the growth and innovation of the Web3 ecosystem.

## Team :busts_in_silhouette:

### Team members (In order of joining time)

- Harish- Project Lead
- Evolution - Developer

### Contact 📞

- **Contact Name:**  Harish Kopanathi
- **Contact Email:**  kopanathiharris@gmail.com

### Legal Structure

- **Registered Address:**  
- **Registered Legal Entity:**  


### Team's experience

**Harish** is the project manager . He has been instrumental in the growth and development, leading the team to create the best end-user experience on the Asset hub. Leadership and vision have been pivotal in transforming Move into a collaborative hub where creators, developers, and community members work collectively for decision-making.

**Evolution** is an open source developer

Harish and Evolution are strongly committed to the Move ecosystem and have demonstrated their ability to deliver high-quality, impactful projects. They bring a wealth of knowledge and experience to the Move Indexer project. Their work has earned Move the number one rank as a decentralized dapp in the Move ecosystem on [Github](). You can read more about their work and Move's contributions to the Move ecosystem on the [Move Wiki]().


### Team Code Repos


#### Team GitHub accounts 🧑‍💻



### Team LinkedIn Profiles 🧑‍🎓




## Development Status :open_book:



## Development Roadmap :nut_and_bolt:

### Overview

- **Estimated duration:**  3 months ⌛️
- **FTE:**  2 FTE
- **Costs:**  30,000 USD 💰


## Milestone 1 - Move Indexer Implementation first part
- **Estimated duration:**  3 months ⌛️
- **FTE:**  2 FTE
- **Costs:** 30,000 USD 💰


| Sequence | Deliverable                                         | Description                                                                                                   |
|----------|-----------------------------------------------------|---------------------------------------------------------------------------------------------------------------|
| 0a.   | Licensing                                             | MIT License will be applicable.                                                                               |
| 0b.   | Documentation                                       | Comprehensive inline code documentation and an explicit README file to guide the project setup and execution.|
| 0c.   | Test Guidelines                                      | Testing will cover major functionality with unit tests and provide a guide for executing these tests.|
| 0d.   | Docker Integration                                   | A Dockerfile will enable the project to run within a Docker container.                          |
| 1a.    | Backward Compatibility Maintenance             | Ensuring backward compatibility with current Uniques v1.                                                      |
| 1b.   | Collection Schema Development              | Development of a GraphQL schema entity that represents the collection.                                        |
| 1c.   | NFT Schema Development                       | Formulation and creation of a GraphQL schema entity representing Non-fungible tokens.                         |
| 2.    | Unique v1.1 Handlers                  | Implement a handlers to index buy, set_price events from the chain.                                               |
| 3.   | NFT Pallet Handlers                 | Handler created for indexing create, mint, buy, set_price, transfer, burn events from the chain.           |
| 4a.   | On-chain Attributes Schema Design      | Development and design of a GraphQL schema entity representing on-chain attributes.                           |
| 4b.   | On-chain Attributes Handlers        | Implementing a four handlers to index the creation and deletion of metadata set for collection and NFT from the chain. |
| 5a.   | Metadata Schema Development                | Creating and designing a GraphQL schema entity representing metadata.                                     |
| 5b.   | Metadata Handlers                   | Implementing a four handlers to index the creation and deletion of an attribute for collection and NFT from the chain.  |
| 5c.   | Metadata IPFS Integration Handler     | Design a handler to retrieve IPFS Metadata from the IPFS network.                                                 |
| 5d.   | Metadata IPFS Unification Handler     | Design and integrate the library to uniform IPFS metadata into one format (OpenSea,TZIP-16,ERC-5773, FXhash)    |
| 6a.   | NFT Royalties Schema Integration      | Design and include royalty support within the GraphQL schema.                                                  |
| 6b.   | NFT Royalties Addition Handler        | Implement a handler to add royalty into NFT.                                                 |
| 6c.   | NFT Royalties PAYOUT Handler           |Creation of handler to index royalty payout events from the chain.                                             |
| 7a.      | Fungible Assets Schema Creation      |Design and formulation of a GraphQL schema entity representing fungible assets.                                |
| 7b.      | Fungible Assets Force Creation        |Handlers will be developed to add system tokens like KSM/DOT into fungible assets.                             |
| 7c.      | Fungible Assets CREATE Event          |An event handler for indexing the creation of a fungible event from a chain, such as (RMRK/USDT) will be developed.|
| 7d.      | Metadata Support for Fungible Assets | Implement a handler to add metadata to a fungible asset event from the chain.                          |
| 7e.   | Fungible Asset Allowlist Setup        |Setting up allows list-based indexing of fungible assets.                                                       |
| 8a.  | Data Views Development                |Construction of data views for efficient access to indexed data.                                               |
| 8b.  | Implementing Metadata Caching Layer |Develop and retry IPFS metadata if un-indexed by Metadata IPFS Integration Handler.                                                               |
| 9.    | Transfer of Collection Ownership    |Incorporate functionality to transfer collection ownership.                                                    |
| 10a.    | Collection settings Schema Design    | Development and design of a GraphQL schema entity representing Collection settings     |
| 10b.    | Collection settings handler    | Implement a handler to add collection settings into data                                                  |


## Future Plans 🔭

The future plans are designed to ensure the continuous improvement and expansion of the system's capabilities, adapting to user feedback and technological advancements. Here are the key enhancements and upgrades we plan to implement:

1. **Data Explorer Development:**
   We aim to create a data explorer that will facilitate seamless navigation within the Web3 data ecosystem. This explorer will make it easier for users to discover and access various data sources and datasets.

2. **Collections Functionality:**
   To enhance data organization, we plan to introduce collections functionality. This feature will enable systematic categorization and organization of datasets, making it simpler for users to find and work with specific data sets.

3. **Visual Representation with View Modules:**
   Visual presentation of data is essential. We plan to create view modules that will visually present data details, making it more accessible and user-friendly for developers and data consumers.

4. **User Profiles:**
   To offer a more personalized experience, we intend to establish user profiles within the system. User profiles will enable personalized user interfaces, allowing users to tailor their data interactions and preferences.

5. **Individual NFT Elements:**
   We will incorporate constituent elements for individual NFT representation, ensuring that all relevant details and components of NFTs are easily accessible and usable.

6. **Action Components:**
   For increased functionality, we will implement action components, such as LIST, SEND, BUY, MINT, BURN, and Atomic Swap. These components will expand the range of actions that users can perform with their data.

7. **Statistical Representations and Analytics:**
   Comprehensive statistical representations and analytics mechanisms will be developed. These tools will provide insights and data-driven analyses, allowing users to make informed decisions.

8. **Rankings and Highlighting:**
   Rankings will be introduced to highlight top-performing users, collections, or items within the Web3 data ecosystem. This feature will recognize and promote excellence and valuable contributions.

9. **User Interface Personalization:**
   The user interface will be further personalized to enhance the user experience. Customization options will be made available to ensure that users can tailor their interactions with the system to their preferences.

10. **Maintenance and Compatibility:**
    We are committed to maintaining compatibility with runtime upgrades and changes in the Web3 ecosystem, particularly in the Kusama/Statemine ecosystem. This ensures that our system remains up-to-date and aligned with the latest technology.

11. **Regular Updates:**
    To keep up with evolving technologies and best practices, we will provide regular updates to the system. This includes staying in sync with Substrate and implementing continuous enhancements to the system.

12. **Parachain Runtime Upgrades:**
    We will manage upgrades to parachain runtime versions, including indexer enhancements and related costs. This ensures that our system remains at the forefront of technological advancements.

These future plans are designed to keep the Web3 data architecture at the cutting edge, providing users with a robust, user-friendly, and continuously improving data ecosystem. The ongoing development and expansion will align with user needs and technological advancements, fostering innovation and efficiency in the Web3 data space.



## Additional Information  ➕


The Move Indexer project continues our team's various projects and implementations in the Move ecosystem. We have already attracted interest from developers within the Move and Kusama ecosystems. Notably, we have in 2019 previously received a grant from the W3F for creating Vue.js UI utilities, components, and libraries, details of which can be found [here](https://github.com/w3f/General-Grants-Program/blob/master/grants/speculative/Vuejs_ui-components.md).

This previous grant allowed us to reimplement keyring into Vue.js & TypeScript, demonstrating our hands-on experience with the Move.js.org/common utilities. The result of this work can be seen in the [web-based Subkey](https://subkey.netlify.com/) tool.

We learned about the Grants Program through a personal recommendation. We believe that our project aligns well with the program's goals, and we are excited about the potential to further contribute to the Move ecosystem.
