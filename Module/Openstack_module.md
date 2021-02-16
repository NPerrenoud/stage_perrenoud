# Usefull Openstack Components

Samuel Paccard

24.06.2020

​           

## Octavia 

**[Load balancer](https://www.openstack.org/software/releases/ussuri/components/octavia)**

Octavia is an open source, operator-scale load balancing solution  designed to work with OpenStack. Octavia was borne out of the Neutron  LBaaS project, and starting with the Liberty release of OpenStack,  Octavia has become the reference implementation for Neutron LBaaS  version 2. Octavia accomplishes its delivery of load balancing services  by managing a fleet of virtual machines, containers, or bare metal  servers —collectively known as amphorae— which it spins up on demand.  This on-demand, horizontal scaling feature differentiates Octavia from  other load balancing solutions, thereby making Octavia truly suited “for the cloud.” 



## Designate

**[DNS service](https://www.openstack.org/software/releases/ussuri/components/designate)**

Designate provides DNS-as-a-service for OpenStack.          



## Kuryr                                            

**[Openstack Networking integration for containers](https://www.openstack.org/software/releases/ussuri/components/kuryr)**

Bridge between containers frameworks networking models to OpenStack networking abstraction                                                      



## Tacker 

**[NFV Orchestration](https://www.openstack.org/software/releases/ussuri/components/tacker)**

Tacker provides a generic VNF Manager (VNFM) and an NFV Orchestrator  (NFVO) to deploy and operate Network Services and Virtual Network  Functions (VNFs) on an NFV infrastructure platform like OpenStack. It is based on ETSI MANO Architectural Framework and provides a functional  stack to Orchestrate Network Services end-to-end using VNFs.                                                                              



## Senlin

**[Clustering service](https://www.openstack.org/software/releases/ussuri/components/senlin)**

Senlin is a clustering service for OpenStack clouds. It creates and  operates clusters of homogeneous objects exposed by other OpenStack  services. The goal is to make orchestration of collections of similar  objects easier.                                                      



## Mistral 

**[Workflow service](https://www.openstack.org/software/releases/ussuri/components/mistral)**

Mistral is a workflow service. Most business processes consist of  multiple distinct interconnected steps that need to be executed in a  particular order in a distributed environment. One can describe such  process as a set of tasks and task relations (via YAML-based language)  and upload such description to Mistral so that it takes care of state  management, correct execution order, parallelism, synchronization and  high availability.                           



## Ceilometer                           

**[Metering & Data Collection Service](https://www.openstack.org/software/releases/ussuri/components/ceilometer)**

Ceilometer's goal is to efficiently collect, normalise and transform  data produced by OpenStack services. The data it collects is intended to be used to create different views and help solve various telemetry use  cases. Aodh and Gnocchi are two examples of services extending  Ceilometer data.                                                                       



## Monasca

**[Monitoring](https://www.openstack.org/software/releases/ussuri/components/monasca)**

Monasca is a open-source multi-tenant, highly scalable, performant,  fault-tolerant monitoring-as-a-service solution that integrates with  OpenStack. It uses a REST API for high-speed metrics processing and  querying and has a streaming alarm engine and notification engine.           



## Panko

**[Event, Metadata Indexing Service](https://www.openstack.org/software/releases/ussuri/components/panko) **

Panko is designed to provide a metadata indexing, event storage service  which enables users to capture the state information of OpenStack  resources at a given time. Its aim is to enable a scalable means of  storing both short and long term data for use cases such as auditing and system debugging.                                                                                                                                                    



## Aodh

**[Alarming Service](https://www.openstack.org/software/releases/ussuri/components/aodh)**

Aodh's goal is to enable the ability to trigger actions based on defined rules against sample or event data collected by Ceilometer.                                                      



## Ironic

**[Bare Metal Provisioning Service](https://www.openstack.org/software/releases/ussuri/components/ironic)**

To implement services and associated libraries to provide massively  scalable, on demand, self service access to compute resources, including bare metal, virtual machines, and containers.     



## Blazar

**[Resource reservation service](https://www.openstack.org/software/releases/ussuri/components/blazar)**

Blazar is a resource reservation service for OpenStack. Blazar enables  users to reserve a specific type/amount of resources for a specific time period and it leases these resources to users based on their  reservations.



## Masakari

**[Instances High Availibility Service](https://www.openstack.org/software/releases/ussuri/components/masakari)**

Masakari provides Instances High Availability Service for OpenStack  clouds by automatically recovering failed Instances. Currently, Masakari can recover KVM-based Virtual Machine(VM)s from failure events such as  VM process down, provisioning process down, and nova-compute host  failure. Masakari also provides an API service to manage and control the automated rescue mechanism.             



## Freezer                                        

**[Backup, Restore, and Disaster Recovery](https://www.openstack.org/software/releases/ussuri/components/freezer)**

Freezer is a distributed backup, restore and disaster recovery as a  service platform. It is designed to be multi OS (Linux, Windows,  OSX...), focused on providing efficiency and flexibility for block based backups, file based incremental backups, point-in-time actions, jobs  synchronization (i.e. backup synchronization over multiple nodes) and  many other features. It is aimed at being useful for all environments,  including large ephemeral Clouds.



## Barbican

**[Key management](https://www.openstack.org/software/releases/ussuri/components/barbican)**

Barbican is the OpenStack Key Manager service. It provides secure  storage, provisioning and management of secret data, such as passwords,  encryption keys, X.509 Certificates and raw binary data.                                                      





