
 Microservices

 Netflix
Netflix migrated from a monolithic system to microservices in 2008 after a database failure disrupted operations. They decomposed their platform into over 1,000 independent services, each owning its own data and deploying independently. They developed supporting tools including Eureka for service discovery, Hystrix for fault tolerance, and Chaos Monkey to test resilience. This architecture allows hundreds of deployments per day with minimal downtime.

 Companies That Reverted to Monolith

Segment built 140+ microservices but reversed course in 2020, consolidating into a monolith after finding that debugging, deployment complexity, and maintaining service contracts slowed development more than the architecture helped.

Istio originally split its service mesh into multiple separate components. In 2020 (v1.5), it merged them into a single binary called istiod, citing excessive operational complexity and latency caused by inter-service communication.

Companies Currently Using Microservices

Amazon decomposed its retail platform in the early 2000s and now runs thousands of microservices across its e-commerce and AWS platforms, with each service independently deployable and maintained by a dedicated team.

Uber runs over 2,000 microservices handling ride matching, pricing, payments, and mapping. They manage complexity through internal tools like Cadence for workflow orchestration and M3 for metrics monitoring.
