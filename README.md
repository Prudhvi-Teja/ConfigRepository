# ConfigRepository
This is the Repository of all Microservices Properties

This Repository for the Spring Config Server to Access all Properties or Yaml files at one place


Project:

Pension Managment System
________________________________________________________________________________________________________________________________________________________________________

It has six microservices which are three of the Platform services and Business Services

Platform Services:
1. Discovery Server (netflix Eureka Server)
2. Spring Cloud Config Server (Maintaining all at Center repo)
3. Spring Cloud Gateway

Business Services:
1. Authorization Microservice (for Authentication and Authorization of the identity)
2. Pension Detail Microservice (Contains all details of the Pension details like personal details in the Internal memory H2 database)\
3. Pension Process Microservice (for Processing the amount to the pensioner we should use for the total amount and deducting the bank charges)

