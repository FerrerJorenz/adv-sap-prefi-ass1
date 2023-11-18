## Assignment in Advanced Systems Integration & Architecture

1. Define Service Oriented Architecture(SOA).

Service-Oriented Architecture (SOA): SOA is an approach to creating software applications that leverages reusable components or services. It also functions as a software design pattern facilitating communication between two or more systems or applications.

2. List and discuss the characteristics of SOA.

Characteristics of SOA:

Standardized Service Contracts: Ensures contracts within a service inventory are standardized, expressing their purpose and capabilities.

Loose Coupling: Allows for implementation while ensuring baseline compatibility for users accustomed to the service features.

Abstraction: Enables defining technology in the context of a business process, breaking dependencies, and introducing agility.

Reusability: Encourages searching for existing services before creating new ones, promoting the reuse of services.

Autonomy: Provides freedom and control for consumers to make decisions without requiring approval or involvement.

Statelessness: Minimizes resource consumption by shortening information while maintaining completeness.

Discoverability: Uses metadata for discovery, communicating purpose and capabilities to humans in detail.

Composability: Breaks down complex problems into manageable parts to facilitate problem-solving.

Interoperability: Sets standards for services, ensuring subscribers can use them, and maintaining interoperability for efficient data exchange.

3. Define Microservices.

Microservices Definition:

Microservices, similar to SOA, is employed to build individual applications in a way that enhances scalability and resilience. It consists of small, independent components that, when combined, create larger applications, assembling services and treating it as a whole.

4. List and discuss the benefits of using Microservices.

Benefits of Microservices:

Independently Deployable: Microservices allow for independent deployment, a crucial characteristic. Smaller services communicate via networks, offering various options for problem-solving.

Right Tool for the Job: Microservices provide flexibility by enabling each service to use its own language and framework, making communication with the chosen application easier.

Precise Scaling: Individual services can be precisely deployed, efficiently handling a large number of tasks simultaneously.

5. List and discuss the similarities and differences of SOA and Microservices.

Similarities:

Reuse: Both emphasize looking for existing services before creating new ones, but microservices lean towards code reuse through copying and accepting data duplication.

Synchronous Calls: Both involve synchronous calls, but microservices' synchronous calls may create real-time dependencies.
Differences:

Communication: SOA relies on an ESB (Enterprise Service Bus) and can become a single point of failure, while microservices use independent communication protocols and simpler messaging systems like APIs.

Interoperability: SOA sets standards for services, whereas microservices enable the exchange and use of information across systems.

Service Granularity: Microservices have highly specialized services designed for specific tasks, while SOA services can range from small and specialized to enterprise-wide services.

Speed: SOA simplifies development and troubleshooting but may operate more slowly than microservices. Microservices allow for quick deployment and testing of independent application pieces without affecting the entire application.