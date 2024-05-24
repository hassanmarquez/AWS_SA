# **AWS SOLUTION ARCHITECT - ASSOCIATED**
This repository is specifically dedicated to AWS Solution Architect documentation, offering technical and business details essential for implementing various cloud solutions provided by AWS, These notes are focused on the solution architecture-associated certification.

## AWS Architecture fundamentals
AWS is the most complete solution to cloud infrastructure environments, it provides multiple cloud solutions based on the service needed. AWS counts on experience, viability, performance and security.

## Important Concepts
The following are the main concepts that are present during the whole study process, it's very important to have a clear meaning of each of them.

### AWS Regions
- AWS has regions all around the world
- Names can be us-east-1, eu-west-3....
- A region is a cluster of data centers
- Most AWS services are region-scoped

*Note:* *Not all regions have all services.
      In the following link you can validate the services available based on the region https://aws.amazon.com/about-aws/global-infrastructure/regional-product-services/*

  ***Factors that impact region selection***
  - Governance (Compliance)
  - Latency (Proximity)
  - Service availability
  - Cost (Pricing)
  
### AWS Availability zones
-   Each region has many availability zones (Usually 3 as minimum and 6 as maximum):
    Example:
    - ap-southeast-2a
    - ap-southeast-2b
    - ap-southeast-2c
  
    #### AWS Data Centers

- They are separate from each other, so they are isolated from disasters.
- They are connected with high bandwidth, ultra-low latency networking.
  
    #### AWS Edge Locations/Points of Presence*

- AWS has 400+ Points of presence.
- Content is delivered to end users with lower latency.

*Note:* Each availability zone (AZ) is one or more discrete data centers with redundant power, networking and connectivity.

