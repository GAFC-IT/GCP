# GCP



## Chapter1. Architecture Overview

**GCP** (Genius Cloud Platform) designed as a private container cloud platform for GeniusAFC, which combined with **Kubernetes** and **Ceph** as major components.

**Kubernetes** run as a Orchestration Platform for both Compute Resource and Storage Resource, and provide solid container service with those resource. 

**Ceph** run as a Distributed Storage System for providing Storage Resource to Kubernetes and Containers.





## Chapter2. Design Princeples

Auto Scale

Portable

Extensible







## Chapter3. Core Functions

## 

### 3.1 Node & Cluster Management



#### 3.1.1 Kubernetes Node 

Node init deploy

Node update/upgrade

Node destory



#### 3.1.2 Kubernetes Cluster

Cluster deploy

Capacity management for K8s cluster



#### 3.1.3 Ceph Node

Node init deploy

Node update/upgrade

Node destory





#### 3.1.4 Ceph Cluster

Cluster Deploy

Capacity Management for Ceph Cluster and Resource Pool





### 3.2 Workload Deployment

Standard for Image Build



Various Type of Workloads

1.Daemon Set

2.Replica Set

3.Statful Set





### 3.3 Service  Orchestration



Service Registry/Discovery

Service Release



### 3.4 Service Scaling 



Scale Up/Scale Down



Scale Out/Scale In







