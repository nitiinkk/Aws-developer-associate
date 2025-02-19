## Getting Started with AWS

### AWS Cloud Overview, Regions & A-Zs
#### Region
- AWS has regions all around the world.
- Names can be us-east-1, eu-west-3
- A region is a cluster of datacenters.

#### Availaibility zones
- Each region has many availability zones(min:3 , max : 6)
- Each AZs is one or more discrete data centers with redundant power, networking and connectivity.
- They're separate from each other, so that they're isolated from disasters.
- They are connected with high bandwidth and ultra low latency networking.

AWS has Global Services
- IAM, S3, CloudFront, WAF(Web application firewall)
- Most ohter services are region scoped(EC2, Lambda, Elastic BeanStalk)