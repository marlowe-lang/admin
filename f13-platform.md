# General

## Proposal title

**Marlowe 2025: Developer-Driven Platform Enhancements**

OR

**Marlowe 2025: Platform Enhancements and Maintainance**

OR

**Marlowe 2025: DApp Builder Platform Enhancements**

OR

**Marlowe 2025: Platform Usability and Performance Enhancements**

## Name and surname of main applicant

> Please provide the name and surname of the main applicant. The main applicant is considered as ...

Tomasz Rybarczy (aka @paluh)

## Are you delivering this project as an individual or as an entity (whether formally incorporated or not)

> Please select from one of the following:

## Co-proposers and additional applicants

> List any persons who are submitting the proposal jointly with the main applicant. Make sure ... Add Co-proposers Enter
> Display Name, Username or Email Address

## Requested funds in ada

180K

> There is a minimum and a maximum amount of funding that can be requested in a single Catalyst ...

## Please specify how many months you expect your project to last (from 2-12 months)

12

## Please indicate if your proposal has been auto-translated into English from another language

> YES/NO - Tick YES so readers are reminded that your proposal has been translated, and that ...
No

## What is the problem you want to solve? (200-character limit including spaces)

> Ensure you present a well-defined problem. What is the core issue that you hope to fix? ...

**Existing Marlowe platform limitations restrict developers from fully leveraging its potential for efficient DApp creation.**

OR

**To become the first choice for Cardano devs, Marlowe needs improvements in developer experience, performance, and runtime efficiency.**

## Summarize your solution to the problem (200-character limit including spaces)

**Enhance Marlowe with a streamlined DevEx, performance-optimized contracts, and comprehensive tools to empower Cardano DApp builders.**

OR

**Deliver a DevEx-focused Marlowe platform with optimized contracts, richer DApp Starter Kit and lightweight backend for seamless developer onboarding.**

OR

**Introduce tools, optimizations, and resources that make Marlowe the go-to solution for Cardano DApp creation and contract efficiency.**


> Focus on what you are going to do, or make, or change, to solve the problem. So not 'There ...

## Website / GitHub repository, White paper, Marketing or any other relevant link

> Here, provide links to yours or your partner organization’s website, repository, or marketing. ...

## Does your project have any dependencies on other organizations, technical or otherwise?

No

## Will your project’s output/s be fully open source?

> Open source refers to something people can modify and share because its design is publicly ...

## Please provide here more information on the open source status of your project outputs

> If you answered YES to the above question: If declaring the project is open source in the ...

## Metadata - Horizons

Smart Contracts

# Solution

> Please describe your proposed solution .How you write this section will depend
> on what type of proposal you are writing. You might want to include details on:
> * How do you perceive the problem you are solving?
> * What are your reasons for approaching it in the way that you have?
> * Who will your project engage?
> * How will you demonstrate or prove your impact?

## Marlowe 2025

This is one of a set of proposals that together consolidate the Marlowe infrastructure and improve the developer experience, enhance Marlowe with an innovative oracle protocol, developed in collaboration with leading Cardano oracle providers, and design the successor core language, Marlowe V2, working with the Marlowe developer ecosystem.

### Solution Summary

Our proposal, Marlowe 2025: Platform Enhancements for Cardano Developers, is designed to transform Marlowe into the most accessible, efficient, and developer-friendly platform for building DApps on the Cardano blockchain. Our enhancements focus on optimizing contract execution, refining the developer experience, and expanding Marlowe’s runtime capabilities—all aligned with the needs of the Cardano developer community.

### Problem Overview

Currently, Marlowe offers a secure, high-level DSL for smart contracts but requires improvements to fully support a seamless, low-cost, and developer-centric experience. While Marlowe has robust foundational tools, it lacks critical optimizations in contract execution, developer workflow, and runtime flexibility. This limits its appeal for rapid DApp development and broader adoption among developers accustomed to mainstream blockchain tools.

### Solution Breakdown

Our solution comprises targeted, modular enhancements across the Marlowe platform. These are tailored to increase ease of integration, reduce on-chain costs, and broaden Marlowe’s appeal as a versatile tool for both novice and experienced Cardano developers.

#### Enhanced Validator Execution

* **Fine-Grained Double Satisfaction Control**: To minimize the need for additional `Notify` steps in contracts, we will add finer control over double satisfaction prevention. This will reduce redundant steps in contract execution, lowering on-chain costs and improving efficiency.
* **Automatic Withdrawal Mechanism**: During contract closure, we will introduce an automatic withdrawal feature if the role token is present, simplifying end-of-contract handling for developers and contract participants.
* **Input Authorization via Signing for Micropayments**: By introducing input signing, we will enable incremental off-chain micropayments as part of contract execution, opening new avenues for real-time applications within Marlowe.

#### Streamlined Runtime API and TypeScript SDK Enhancements

* **Simplified Contract State Management**: We will enhance the API to make contract integration in DApps straightforward, treating contract states as manageable, named stages and transitions. This allows contract integrators to focus exclusively on their business logic and easily overlay a custom UI, tailored to their unique requirements.

* **Merkleization and Runtime Integration**: We aim to bring Merkleization into the core runtime lifecycle APIs to streamline use, making complex contract logic easier to integrate.

#### Optional Runtime Enhancements

* **Lightweight Indexer**: For efficient on-chain data handling, we will introduce a lightweight indexer. Key features include:
    * **SQLite Support**: Introducing support for SQLite allows a simpler, lighter solution for developers without the need for a full database setup.
    * **Much, much smaller so faster DB layer**: By limiting data to Marlowe-specific on-chain details, this indexer will offer a performance boost and reduce complexity.
    * **Selective UTxO Access via Transaction API**: We will extend the transaction buildup API so that the indexer supplies only Marlowe-relevant UTxOs, while user-specific UTxOs are provided by their wallet.

* **Configurable Runtime Fee Mechanism**: For sustained development and platform scaling, we will add a fee mechanism where service providers can set contract execution fees. This feature, explicitly defined in the API, will enable monetization, incentivizing infrastructure providers and increasing Marlowe’s appeal as a revenue-generating platform for service providers and developers alike.

### Engagement and Value Proposition

Our project will engage a diverse spectrum of developers, including DApp developers, infrastructure providers, and both new and established Cardano community members. By addressing core pain points around developer experience, execution cost, and usability, our enhancements aim to make Marlowe a go-to tool within the Cardano ecosystem. With these changes, Marlowe will not only facilitate the creation of secure financial applications but will also empower developers to build innovative, complex DApps with ease.


# Impact

> Please include here a description of how you intend to measure impact (whether quantitative or qualitative) and how and with whom you will share your outputs:
> * In what way will the success of your project bring value to the Cardano Community?
> * How will you measure this impact?
> * How will you share the outputs and opportunities that result from your project?

## Impact

Our project, **Marlowe 2025: Platform Enhancements for Cardano Developers**, aims to elevate Marlowe as a highly accessible and efficient smart contract platform within the Cardano ecosystem. By improving the developer experience and enhancing runtime capabilities, we’re committed to driving broader adoption and innovation on Cardano. This proposal will serve not only current users but also attract new developers by offering streamlined contract integration, cost-efficient contract execution, and simplified deployment options.

### Value to the Cardano Community

Our enhancements are designed to expand Marlowe’s usability and appeal across multiple developer and stakeholder groups:

* **Developers and DApp Builders**: Marlowe’s simplified integration and high-level abstractions will make it more approachable for developers, helping them save time and costs on complex smart contract development. Features like streamlined state management, Merkleization integration, and input signing for micropayments mean developers can focus on their core business logic instead of low-level execution details. The impact will manifest as an increase in innovative DApps built on Cardano, spanning finance, micropayments, and more.

* **Infrastructure Providers and Service Providers**: Optional runtime fees offer infrastructure providers a clear incentive to integrate Marlowe into their offerings. By allowing configurable transaction fees, Marlowe aligns with sustainable business models for service providers, fostering a cooperative ecosystem and positioning Marlowe as a value-generating component within the Cardano infrastructure.

* **Developers Seeking Lightweight Solutions**: The introduction of an optional lightweight indexer with SQLite support targets developers seeking a faster, simpler approach to working with on-chain data. By minimizing resource requirements, we reduce the entry barriers for developers looking to build without extensive infrastructure, broadening Marlowe’s appeal to a larger audience.

### Impact Measurement

To gauge the success of our enhancements, we will monitor both quantitative and qualitative metrics:

* **Adoption Metrics**: We will track the number of Marlowe contracts deployed and actively used on the Cardano mainnet and testnets, with a particular focus on contracts using new features like micropayment integrations, Merkleization, and the simplified state management APIs.

* **Developer Feedback and Engagement**: Feedback from the community will be crucial in evaluating the success of our improvements. We will gather qualitative data through user feedback from early testers, developer forums, and community discussions, which will help refine our approach and ensure our enhancements align with real developer needs.

# Capability & Feasibility

> Please describe your existing capabilities that demonstrate how and why you believe you’re best suited to deliver this project?
> Please include the steps or processes that demonstrate that you can be trusted to manage funds properly.


# Project Milestones

> A clear set of milestones and acceptance criteria will demonstrate your capability to deliver the project as proposed. More guidance on submitting milestones as part of your project proposal can be found here.
> What are the key milestones you need to achieve in order to complete your project successfully? A clear set of milestones and acceptance criteria will demonstrate your capability to deliver ...


### Milestone 1: Validator Execution Optimization

- **Rationale**: Optimizing the Marlowe validator is key to enhancing contract efficiency by reducing the number of transactions needed for contract completion. We aim to simplify contract execution, particularly for common contracts like open swaps or auctions and improve efficiency by implementing fine-grained control over double satisfaction checks and enabling automatic withdrawals based on role tokens.

- **Outputs**:
  - **Validator Changes**:
    - Introduction of proper thread token using CIP-0069 capabilities.
    - Introduction of finer control over double satisfaction to avoid extra `Notify` steps.
    - Addition of an automatic withdrawal mechanism during contract closure when a role token is present.
  - **Runtime Changes**:
    - Thread token is removed from the develoeper facing Runtime API and is handled seamlessly in the background.
    - Integration of these validator changes within the Marlowe Runtime.
    - REST API enhancements to enable the automatic withdrawal feature.

- **Acceptance Criteria**:
  - Thread token is successfully managed and the Runtime API is updated.
  - Successful optimization of a common swap contract, reducing it to two transactions instead of four.
  - Demonstration of automatic fund withdrawal upon contract closure.

- **Evidence of Milestone Completion**:
  - Release of updated validators, Marlowe Runtime, and TypeScript SDK (TS-SDK) supporting optimized execution.
  - Deployment of an Atomic Swap DApp prototype showcasing the new features on preprod and mainnet.
  - Accompanying documentation detailing the optimization and showcasing the features, integrated into the existing Marlowe DApp Starter Kit.

### Milestone 2: Micropayments via Signed Inputs

- **Rationale**: Introducing off-chain micropayment functionality will enable Marlowe to support real-time payments akin to payment channels (e.g., Lightning Network). This milestone focuses on partial payments through signed inputs, enhancing cost efficiency and making Marlowe contracts more competitive for end users.

- **Outputs**:
  - **Validator Changes**:
    - Unique tagging of the contract nodes to enable safe in and cross contract input identification.
    - Support for input authorization through direct `Input` signatures, enabling micropayment functionalities.
  - **Runtime Changes**:
    - REST endpoint for signing inputs to facilitate partial off-chain payments.
    - Full integration of validator changes into the runtime.

- **Acceptance Criteria**:
  - Successful off-chain partial payments executed via signed inputs, with final settlement performed on-chain in a single transaction.
  - Deployment of an example contract demonstrating micropayments functionality.

- **Evidence of Milestone Completion**:
  - The example contract with micropayment functionality available on the main branch of the marlowe-ts-sdk GitHub repository, tested on an updated Runtime version.
  - Release of a revamped Bounty DApp showcasing the micropayments capability, with documentation included in the enhanced Marlowe DApp Starter Kit.

### Milestone 3: Seamless DApp Integration for Complex Contracts

- **Rationale**: This milestone aims to provide a simplified DApp integration experience for complex Marlowe contracts. By introducing state annotations and integrating Merkleization examples into the Runtime API, we’ll enable developers to manage Marlowe contract execution as a straightforward state machine, focusing only on business logic.

- **Outputs**:
  - **Enhanced State Management**:
    - Implementation of state and transition annotation capabilities for Marlowe contracts.
  - **SDK & Runtime Integration**:
    - Merkleization examples integrated seamlessly into the runtime lifecycle API, simplifying contract management.
  - **Prototype Update**:
    - **Prototype Token Plan v2**, which supports multiple periods with fewer transactions and incorporates state annotations.

- **Acceptance Criteria**:
  - Successful deployment of a Token Plan prototype (v2) allowing simplified state management and extended contract periods with fewer transactions.
  - Use of the updated Marlowe TS-SDK with the state and transition annotations.

- **Evidence of Milestone Completion**:
  - The Token Plan v2 prototype will be deployed on preprod and mainnet, accompanied by thorough documentation.
  - An updated guide in the Marlowe DApp Starter Kit, showcasing optimized contract execution and detailing new features.

### Optional Milestone 4: Lightweight Runtime Indexer

- **Rationale**: Introducing a lightweight indexer with SQLite support will make Marlowe more accessible for developers seeking low-overhead data solutions. By supporting only Marlowe-specific on-chain data and Marlowe-relevant UTxOs, we’ll enable faster contract integration without needing a full database infrastructure.

- **Outputs**:
  - **Runtime Indexer**:
    - Support for SQLite database.
    - Marlowe-specific UTxO filtering within the transaction buildup API.
  - **Wallet Integration**:
    - Enhancements to provide Marlowe-specific UTxOs while keeping user-specific UTxOs managed by their wallet.

- **Acceptance Criteria**:
  - Lightweight indexer successfully delivers Marlowe-specific data to the contract while minimizing database complexity and storage requirements.
  - Full support for SQLite and UTxO filtering functionality demonstrated in a test environment.

- **Evidence of Milestone Completion**:
  - Deployment of the lightweight indexer, accessible on the Marlowe GitHub repository.
  - Accompanying documentation for developers on using the lightweight indexer as part of their DApp integration.

### Optional Milestone 5: Runtime Monetization

- **Rationale**: To encourage sustainable development within the Marlowe ecosystem, we aim to introduce a fee mechanism that enables infrastructure providers to charge fees for contract execution. This would incentivize the broader adoption of Marlowe by creating opportunities for service providers to monetize their offerings.

- **Outputs**:
  - **Runtime Fee Mechanism**:
    - Integration of a configurable fee system within the Marlowe Runtime, with transaction fees set by providers.
    - Explicit API updates reflecting fee amounts and recipient addresses.

- **Acceptance Criteria**:
  - Runtime successfully handles fees for contract execution, with provider-specific configuration.
  - Deployment of a prototype showing the monetization process.

- **Evidence of Milestone Completion**:
  - Public deployment of a fee-enabled Marlowe Runtime.
  - Detailed documentation in the Marlowe GitHub repository, outlining the fee mechanism and usage for service providers.

### Final Milestone: Project Close-out Report and Video

- **Outputs**: We will produce a completion report and video summarizing the project’s achievements, challenges, and future directions, shared publicly with the Cardano community.

- **Acceptance Criteria**:
  - Completion report available on the Marlowe GitHub repository, with a link provided to reviewers.
  - Video published on YouTube and other community platforms.

- **Evidence of Milestone Completion**:
  - Public links to the final report and video, accessible to the Cardano community for transparency and knowledge sharing.


# Resources

> Who is in the project team and what are their roles? List your team, their Linkedin profiles (or similar) and state
> what aspect of the proposal’s ...

# Budget & Costs

> Please provide a cost breakdown of the proposed work and resources Make sure every element mentioned in your plan
> reflects its cost. It may be helpful to refer ...

# Value for Money

> How does the cost of the project represent value for money for the Cardano ecosystem? Use the response to provide the
> context about the costs you listed previously, particularly if ...
