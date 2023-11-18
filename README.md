## Assignment in Advanced Systems Integration & Architecture
1. Define Service Oriented Architecture(SOA).
- Service-oriented architecture reuses different functions and services and combines them in different systems to create software applications.
 These services can communicate with each other to complete the software development process.

2. List and discuss the characteristics of SOA.
- Standardized Service Contract: Services adhere to a service-description. A service needs to have some information that defines what the service is about.
- Loose Coupling: Services minimize dependencies on each other. So if the service functionality breaks at several points in time, this should not crush the client application or stop it from running.
- Service Abstraction: Services wrap the logic they encapsulate from the unknown external world. The service shouldn't show how it performs its functionality.
- Service Reusability: Logic is divided into services to maximize re-use.
- Service Autonomy: Services must control the logic they encapsulate.
- Service Statelessness: Services should stay stateless. This determines that services should not keep data from one state to the other. This would be required to be done from each client application.
- Service Discoverability: Services can be discovered (usually in a service registry). We have previously viewed this in the theory of the UDDI, which performs a registry which can contain information about the web service.
- Service Composability: It breaks large problems into tiny problems.
- Service Interoperability: Services should use standards that provide different supporters to use the service. This is examined so obviously these days that it is frequently dropped as a principle.

3. Define Microservices.
- The application is built using a software development methodology called microservices, and the applications are composed of several services. Each micro service addresses a business problem by using simple interfaces to communicate with other services.
4. List and discuss the benefits of using Microservices.
- Microservices architecture involves breaking a monolithic application into component functions or services, which are then loosely connected via APIs. This allows for improved scalability, better fault isolation, and faster time to market.

- Each microservice in this architecture can be programmed in any language and run on any platform, offering flexibility in using the best tools for each project’s needs.

- Microservices allow for better data security and compliance, as each service is responsible for a specific task, making it easier to implement security measures at the service level.

5. List and discuss the similarities and differences of SOA and Microservices.
- similarities : The development teams can create, install and maintain contemporary cloud applications easily with microservices and serviceOriented Architecture. But microservices, compared to the SOA implementations, offer a few advantages.

- difference : Microservices is a highly scalable while SOA is a less scalable architecture.
