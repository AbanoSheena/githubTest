# githubTest
1.	Define Service Oriented Architecture (SOA).
-	SOA or Service Oriented Architecture is a software development that allows reusability of services. Other applications also apply SOA that needs services from other existing services and those services will communicate with each other to work together. Services link with one other using a method known as "loose coupling," which is a technique for eliminating dependencies between components in a system or network so they can exchange data or manage a business activity. 
2.	List and discuss the characteristics of SOA.
1.	It supports loose coupling – Dependencies between services are minimized. For this reason, if the service functionality occasionally fails, it should not have a disastrous effect on the client application or cause it to crash.
2.	It supports interoperability - follows criteria that enable various customer or client to utilize the service.
3.	Standardized Service Contracts - contain some information that explains its purpose for the clients safety. 
4.	Abstraction - The way the service operates should not be visible to anyone. 
5.	Service Reusability - Logic is divided to maximize the re-usability of the services.
6.	Autonomy - control the logic they encapsulate. The services should be more isolated.
7.	Statelessness - should not retain data between different states. And each client application should handle this responsibility instead.
8.	Discoverability –include relevant information for easy identification, providing details about their purpose and capabilities for human understanding.
9.	Composability - divides complex issues into smaller, more manageable problems.
3.	Define Microservices.
-	Microservices represent a way of structuring and organizing software development. In this approach, software consists of compact independent services that interact through clearly defined APIs. These services are managed by small, self-contained teams. The adoption of microservices architectures facilitates quicker development and scalability of applications. 
4.	List and discuss the benefits of using Microservices.
-	Independently deployable – one of the benefits Microservices offers to organization is that due to the smaller and independent deployable nature, they are a remedy for the frustrating experience of those minor changes that consumes significant amounts of time.
-	Right tool for the job –gives flexibility to choose the most suitable tools or services for solving unique challenges. Have the freedom to choose the most effective tool they see fit for each specific task. 
-	Precise Scaling – the benefits here is that when each service is deployed and scaled independently and is done correctly, in future the microservices will demand less infrastructure or you can scale only the specific component that is needed and not the entire application which is commonly seen in a monolithic setup. 
5.	List and discuss the similarities and differences of SOA and Microservices.
-	SOA and Microservices differ in scope. SOA has an enterprise focus, one part of the company can use and benefit from the capabilities of another part without being tightly bound together. Microservices, with an application focus, operates independently. Microservices has its own way of talking to others. SOA relies on a common Enterprise Service Bus (ESB), posing a risk if it fails, it affects everything. Microservices prioritize simplicity in message sending, whereas SOA allows or open for more complex methods. Additionally, Microservices designed in specialized tasks, while SOA encompasses both specialists and those who handle tasks for the whole company. Microservices preference for duplication contributes to faster operation, while SOA common structure can slow down development and problem-solving.
-	The similarities of SOA and Microservices. Microservices and SOA are alike in terms of they both use cloud or hybrid environment to build and run applications. They both break down big applications into smaller and flexible parts that works together.