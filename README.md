# CloudFoundry Cassandra Service

This repository and sub repository at (src/services/cassandra) contains complete code dealing with  [Cassandra] [1] as a service on [CloudFoundry] [2].

The features that this implementation support are:
1. Multi node Cassandra Cluster
2. Multiple Cassandra instances (services)
3. Monit script integrated with each Cassandra process that deals with auto restart of the cassandra process in case of a crash/VM restart/upgrade

Features not supported
1. Adding new cassandra node to an existing service. (Before creating service number of cassandra node running through bosh jobs instances decides the number of nodes in a cluster)

