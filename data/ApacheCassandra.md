# Apache Cassandra - http://cassandra.apache.org
Apache Cassandra is a free and open-source distributed
NoSQL database management system.

## Scalability
- highly-scalable
    - [@Cockcroft2011]
    - Partitioning across multiple machines in an application-transparent matter.
      Automatic partition as machines are added and removed from cluster.

## Availability
- Replication
    - Has two different replication Strategies [@Strickland2014]:
        - SimpleStrategy 
        - NetworkTopologyStrategy

## Latency
- low
    - No atomicity of transactions
    
## User Management
- RBAC

## Communication
- C2N SSL
- N2N SSL

## Features
- Row store
- Close to SQL

## Repository
- https://github.com/apache/cassandra

## License
- Apache-2.0
