# CDN
Content Delivery Network.
- [Geographically distributed group of servers that caches content close to end users.]()
[![CDN Working](https://cf-assets.www.cloudflare.com/slt3lc6tev37/7Dy6rquZDDKSJoeS27Y6xc/4a671b7cc7894a475a94f0140981f5d9/what_is_a_cdn_distributed_server_map.png)]()

##### [Benefits of Using CDN]()
- Improving website load times
- Reducing bandwidth costs
- Increasing content availability and redundancy
- Improving website security

##### [CDN Providers:]()
- CloudFlare
- AWS
- MaxCDN
- Incapsula
- Google

# Computing
#### [Types of Computing]()
- [Cloud Computing]()
- [Personal Computing]()
- [Client Server Computing]()
- [Time Sharing Computing]()
- [Cluster Computing]()
- [Distributed Computing]()
- [Grid Computing]()

##### [Cloud Computing]()
###### [Types of Cloud]() - Deployment Model
- [Public Cloud]() - Manufacturing organization shares cloud with general public.
- [Private Cloud]() - Manufacturing organization has its own private cloud.\
Model offers similar benefits to a public cloud.\
Services and infrastructure are maintained on a private network.\
This provides greater control and privacy, making it suitable for organizations with strict security, compliance, and regulatory requirements.\
They can be physically located on the company's on-site data center or hosted by a third-party service provider.
- [Hybrid Cloud]() - Combination of cloud deployment models\
Hybrid cloud combines the features of both public and private clouds, allowing data and applications to be shared between the two.
##### [Personal Computing]()
##### [Client Server Computing]()
##### [Time Sharing Computing]()
##### [Cluster Computing]()
##### [Distributed Computing]()
##### [Grid Computing]()


# Networking
#### [Computer Network Architecture]()
- [Computer Network Architecture]()

- [Peer-to-Peer Architecture]()

#### [Load Balancer]()
[Types of Load Balancer]()

#### [VPN]()

# Storage

# Security

# Database

#### [SQL (Structered Query Language)]()
RDBMS - A Relational Database Management System which stores and process information in a relational database.
##### [Structure]()
Organizes data in relational, tabular ways, using tables with columns or attributes and rows of records.
##### [Benefits]()

##### [Examples:]()
- MySQL
- Postgresql
###### [Areas of Use:]()
Well suited for building applications structured around a relationship between data tables.

#### [NOSQL (Non SQL or Non Structured Query Language)]()
Database design that enables the storage and querying of data outside the traditional structures found in relational databases.
###### [Structure]()
###### [Types of NoSQL Databses]()
- Document Databases
- Key-value databases
- Wide-column stores
- Graph databases
###### [Benefits of NoSQL Databases]()
- Flexible schemas
- Horizontal scaling
- Fast queries due to the data model
- Ease of use for developers
###### [Applications:]()

Areas of Use:

###### [Examples:]()
- MongoDB

###### [Best performance is achieved when both are used simultaneously in an application.]()
# Caching
Example: Reddis

# Architecture
##### [API \{ Application Programming Interface \}]()
User Request -----> API GateWay -----> API Endpoint -----> Controller Layer(Controls and Handles User Request and delivers response to user) -----> Service Layer(Bussiness Logic) ------> Dao Layer(Talks to the Database: Performs CRUD Operations,ie. Create, Read, Update and Delete Data)
[![API WORKING](https://media.geeksforgeeks.org/wp-content/uploads/20220306170607/Fig48.jpg)]()

#### [MonoLith Applications]()
- Standalone Applications
- Computes every task on its own
[![Monolith Architecture](https://wac-cdn.atlassian.com/dam/jcr:95b9a276-c524-42b1-8d06-ded56d589858/Monolithic%20architecture@2x.png?cdnVersion=1302)]()
##### [Benefits]()
- Easy deployment – One executable file or directory makes deployment easier.
- Development – When an application is built with one code base, it is easier to develop.
- Performance – In a centralized code base and repository, one API can often perform the same function that numerous APIs perform with microservices.
- Simplified testing – Since a monolithic application is a single, centralized unit, end-to-end testing can be performed faster than with a distributed application. 
- Easy debugging – With all code located in one place, it’s easier to follow a request and find an issue.

- Cost-Effectiveness – Amazon Reported - ["Amazon Prime Video team's recent case study has revealed an interesting shift from a serverless microservices architecture to a monolith approach. This change resulted in a significant 90% reduction in operating expenses ..."]()
##### [Drawbacks]()
- Application becomes complex as it grows over the time
- Slower development speed – A large, monolithic application makes development more complex and slower.
- Scalability – You can’t scale individual components.
- Reliability – If there’s an error in any module, it could affect the entire application’s availability.
- Barrier to technology adoption – Any changes in the framework or language affects the entire application, making changes often expensive and time-consuming.
- Lack of flexibility – A monolith is constrained by the technologies already used in the monolith.
- Deployment – A small change to a monolithic application requires the redeployment of the entire monolith.
#### [Microservices]()
- Application is divided into small group of applications which communicate over the network to receive request and return response which results in the overall functioning of the application.
- Each task is performed by a individual application(Application may be independent or dependent on other services)
[![Microservices Architecture](https://wac-cdn.atlassian.com/dam/jcr:5308ccab-dc94-46f5-978c-8a77b8d5be57/Microservice%20architecture@2x.png?cdnVersion=1302)]()


##### [Benefits]()
- Agility – Promote agile ways of working with small teams that deploy frequently.

- Flexible scaling – If a microservice reaches its load capacity, new instances of that service can rapidly be deployed to the accompanying cluster to help relieve pressure. We are now multi-tenanant and stateless with customers spread across multiple instances. Now we can support much larger instance sizes. 

- Continuous deployment – We now have frequent and faster release cycles. Before we would push out updates once a week and now we can do so about two to three times a day. 

- Highly maintainable and testable – Teams can experiment with new features and roll back if something doesn’t work. This makes it easier to update code and accelerates time-to-market for new features. Plus, it is easy to isolate and fix faults and bugs in individual services.

- Independently deployable – Since microservices are individual units they allow for fast and easy independent deployment of individual features. 

- Technology flexibility – Microservice architectures allow teams the freedom to select the tools they desire. 

- High reliability – You can deploy changes for a specific service, without the threat of bringing down the entire application.

- Happier teams – The Atlassian teams who work with microservices are a lot happier, since they are more autonomous and can build and deploy themselves without waiting weeks for a pull request to be approved.

# Observability
