# Move Indexer

- **Team Name:**  TrackIt-Block

### Overview

In the realm of Web3 indexing, the Move Indexer is an innovative Rest/GraphQL service meticulously designed to simplify interactions with assets on Move-based blockchain protocols. This service has been purpose-built to function as a robust data layer for various assets, including smart contracts, within decentralized applications (dApps). It leverages the user-friendly features of GraphQL and REST API to streamline this process.

Presently, developers encounter significant hurdles when dealing with assets interactions on Move based blockchains due to the intricacies and time-consuming nature of querying. The Move Indexer steps in to alleviate these challenges by offering an intuitive GraphQL interface(as well as CLI), thereby significantly reducing the time and effort required to access and query these assets.

The Move Indexer offers several key advantages, including its primary focus on ease of use, remarkable versatility catering to a wide range of use cases, and a strong commitment to bridging the gap between developers and blockchain utilization and documentation. It achieves this while adhering to the principles of decentralization and open-source development, which underscores its dedication to safeguarding user privacy by abstaining from data collection.

By effectively reducing the time and complexity associated with querying assets and presenting a more user-friendly interface, the Move Indexer aspires to promote the growth and evolution of the Web 3.0 ecosystem within the realm of Move-based blockchain technology.


### Project Details


1. **Project Overview:**
   The Move Indexer is an advanced infrastructure tool designed to address developers' challenges when querying data on the blockchain. It offers a more efficient and user-friendly way to interact with data using GraphQL as well as CLI

2. **Project Structure:**
   The project has a well-organized structure, including the following directories:

   - **Generated Model/Server Definitions:** These contain the definitions for the data models and server endpoints.

   - **Server Extensions:** This directory may include custom server extensions or middleware.

   - **Data Type Definitions:** Here, you'll find the definitions for various data types used in the project.

   - **Mapping Modules:** Mapping modules are crucial for data processing, ensuring that data is structured and presented correctly.

3. **Use Cases:**
   Consider the potential use cases for the Move Indexer. For instance, you can create innovative applications that manipulate and query data, utilizing the capabilities of the Move Indexer. This tool opens up a wide range of opportunities for developers to explore.

4. **GraphQL Interface:**
   The Move Indexer primarily provides a GraphQL interface for querying data. Developers can leverage this interface to interact with various data sources. You can refer to the GraphQL documentation for specific queries and mutations.

5. **CLI :**
   The Move Indexer could also be accessible via CLI to make development a bit more developer friendly(Need to discuss further)

6. **Contributions and Enhancements:**
   As the Move Indexer will be open-source, you're encouraged to contribute to its development and enhancement. The community welcomes suggestions, bug fixes, and feature additions to make the tool even more powerful and user-friendly for data-related applications.

7. **Conclusion:**
   By using the Move Indexer, developers can streamline the querying and manipulation of data on the blockchain. This not only saves time but also makes it easier to build innovative and user-friendly decentralized applications within the Web 3.0 ecosystem. The Move Indexer is a valuable resource that simplifies and accelerates the development of blockchain-based applications, providing efficient access to a wide range of data sources.

#### Architecture 🏗

1. **Architecture Overview:**
   The architecture of this Web3 data indexer is designed with a focus on simplicity and efficiency, ensuring a seamless interaction with various data sources within the Web3 ecosystem.

2. **Language and Reliability:**
   At the core of this architecture is Rust.

3. **Data Processing Framework:**
    Need some suggestions for any favorable framework available

4. **Database System:**
   This architecture interacts with a database(possibility of postgres or any other alternative) or RPC node.

5. **Data Flow:**
   The architectural flow involves several layers:
   - Data is obtained from RPC nodes for real-time data.
   - When new data events are obtained, they are automatically processed by defined handlers. Data is then stored in the database, providing a structured and scalable storage solution.

6. **Data Access and Querying:**
   To expose the data to clients, a GraphQL interface is provided. GraphQL is a powerful query language for APIs and a runtime for executing those queries with existing data. It allows clients to request precisely the data they need, optimizing performance and enhancing developer tools.

This architecture is designed to create an efficient and user-friendly framework for managing and querying data within the Web3 ecosystem, ensuring robustness, reliability, and scalability.

#### Technology Stack 💻

- Rust
- Node.js
- Docker
- Postgres(or any DB)
- GraphQL
  
### Ecosystem Fit

The Web3 data architecture described here is a significant asset to the broader Web3 and data ecosystem. It addresses a variety of challenges that developers frequently encounter when working with blockchain data and data sources, making it an indispensable resource for various projects and applications within the ecosystem.

**Key Aspects of Ecosystem Fit:**

**Tooling** refers to the various software tools and applications that are used by individuals or teams to develop, manage, and maintain software, systems, and infrastructure. These tools are designed to streamline processes, enhance productivity, and support specific tasks within the software development and IT operations domains. Types of tooling include:

- **Development Tools**: Integrated Development Environments (IDEs), code editors, version control systems (e.g., Git), compilers, and debugging tools are used by developers to write, test, and manage code.
- **DevOps Tools**: Continuous Integration and Continuous Delivery (CI/CD) pipelines, containerization and orchestration tools (e.g., Docker, Kubernetes), and infrastructure as code (IaC) tools (e.g., Terraform, Ansible) automate the deployment and management of software and infrastructure.
- **Monitoring and Observability Tools**: Tools like application performance monitoring (APM), log management, and error tracking systems help organizations monitor the health and performance of their applications and infrastructure.
- **Collaboration and Communication Tools**: Messaging platforms, project management software, and team collaboration tools facilitate communication and coordination among team members.
- **Security Tools**: Security-focused tooling includes antivirus software, intrusion detection systems, vulnerability scanners, and encryption tools to protect data and systems from security threats.
- **Data and Analytics Tools**: Database management systems (DBMS), data analysis platforms, and reporting tools support data storage, analysis, and reporting.

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
- **Costs:**   


## Milestone 1 - Move Indexer Implementation first part
- **Estimated duration:**  3 months ⌛️
- **FTE:**  2 FTE
- **Costs:**  

                                             

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


These future plans are designed to keep the Web3 data architecture at the cutting edge, providing users with a robust, user-friendly, and continuously improving data ecosystem. The ongoing development and expansion will align with user needs and technological advancements, fostering innovation and efficiency in the Web3 data space.

## Additional Information  ➕

We learned about the Grants Program through encode move course
