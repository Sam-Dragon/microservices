# Design Patterns

<details>
<summary>Decomposition</summary>
- It is responsible for breaking down a monolith to microservice

> By Business Capabilities / Sub Domain
- decompose by business functionality
- decompose based on DDD [Domanin Driven Design] which is sub-domain   

> **Strangler**
- Incrementally refactor a monolithic application into a microservices architecture.
- It involves gradually replacing specific functionalities of the monolith with new, independently deployable microservices

> Sidecar 
- It is reponsible for segregating the primary functionality with secondary concerns and making it dependent
- It allows loose coupling, resource sharing, low latency, reduces code complexity and duplication
- It is useful in logging, monitoring, security, configuration, proxy / routing

> Service Mesh
-  

</details>

<details>
<summary>Database</summary>
  
- Database per service
- Shared Database
- CQRS
- Saga
- Event Sourcing

</details>

<details>
<summary>Communication</summary>

- synchronous
- Asynchronous
- Medium
  - REST
  - Graphql
  - GRPC

</details>

<details>
<summary>Integration</summary>

- API Gateway
- Aggregator
  - Chained
  - Branch
- Client Side UI composition 

</details>

<details>
<summary>Deployment</summary>

- Multiple Service Instance per host
- Service Instance per host
- Service Instance per vm
- Service Instance per container
- serverless
- blue-green
- canary

</details>

<details>
<summary>Observability</summary>

- Log Aggregation
- Performance Metrices
- Distributed Tracing
- Health Check

</details>

<details>
<summary>Cross Cutting Concern</summary>

- External Configration
- Service Discovery
- Circuit Breaker

</details>
