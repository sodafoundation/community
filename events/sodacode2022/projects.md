## SODACODE2022 Participating Projects
As part of the SODACODE 2022, contributions to the following projects will be considered.

### Cortx (SODA Eco Project)

CORTX is a distributed object storage system designed for great efficiency, massive capacity, and high HDD-utilization. CORTX is 100% Open Source. Most of the project is licensed under the Apache 2.0 License and the rest is under AGPLv3; check the specific License file for each submodule to determine which is which.

[View Project Code](https://github.com/Seagate/CORTX) | [Issues](https://github.com/Seagate/cortx/issues?q=is%3Aissue+is%3Aopen+label%3ASODACODE2022) | [PRs](https://github.com/Seagate/cortx/pulls) | [Documentation](https://github.com/Seagate/cortx/blob/main/QUICK_START.md)

### Karmada (SODA Eco Project)

Karmada (Kubernetes Armada) is a Kubernetes management system that enables you to run your cloud-native applications across multiple Kubernetes clusters and clouds, with no changes to your applications. By speaking Kubernetes-native APIs and providing advanced scheduling capabilities, Karmada enables truly open, multi-cloud Kubernetes.

Karmada aims to provide turnkey automation for multi-cluster application management in multi-cloud and hybrid cloud scenarios, with key features such as centralized multi-cloud management, high availability, failure recovery, and traffic scheduling.

[View Project Code](https://github.com/karmada-io/karmada) | [Issues](https://github.com/karmada-io/karmada/issues) | [PRs](https://github.com/karmada-io/karmada/pulls) | [Documentation](https://github.com/karmada-io/karmada/blob/master/README.md)

### KubeEdge (SODA Eco Project)

KubeEdge is an open source system for extending native containerized application orchestration capabilities to hosts at Edge.It is built upon kubernetes and provides fundamental infrastructure support for network, app. deployment and metadata synchronization between cloud and edge. Kubeedge is licensed under Apache 2.0. and free for personal or commercial use absolutely. We welcome contributors!

Our goal is to make an open platform to enable Edge computing, extending native containerized application orchestration capabilities to hosts at Edge, which is built upon kubernetes and provides fundamental infrastructure support for network, app deployment and metadata synchronisation between cloud and edge.

[View Project Code](https://github.com/kubeedge) | [Issues](https://github.com/kubeedge/kubeedge/issues) | [PRs](https://github.com/kubeedge/kubeedge/pulls) | [Documentation](https://kubeedge.io/en/)

### LINSTOR (SODA Eco Project)

LINSTOR is a configuration management system for storage on Linux systems. It manages LVM logical volumes and/or ZFS ZVOLs on a cluster of nodes. It leverages DRBD for replication between different nodes and to provide block storage devices to users and applications. It manages snapshots, encryption and caching of HDD backed data in SSDs via bcache.

[View Project Code](https://github.com/LINBIT/linstor-server) | [Issues](https://github.com/LINBIT/linstor-server/issues?q=is%3Aissue+is%3Aopen+label%3Asodacode2022) | [PRs](https://github.com/LINBIT/linstor-server/pulls) | [Documentation](https://linbit.com/drbd-user-guide/linstor-guide-1_0-en/)

### OpenEBS (SODA Eco Project)

OpenEBS is Kubernetes native Container Attached Storage solution that makes it possible for Stateful applications to easily access Dynamic Local PVs or Replicated PVs. By using the Container Attached Storage pattern users report lower costs, easier management, and more control for their teams.

OpenEBS helps Developers and Platform SREs easily deploy Kubernetes Stateful Workloads that require fast and highly reliable container attached storage. OpenEBS turns any storage available on the Kubernetes worker nodes into local or distributed Kubernetes Persistent Volumes.

[View Project Code](https://github.com/openebs/openebs) | [Issues](https://github.com/search?q=org%3Aopenebs+label%3ASODACODE2022&type=Issues) | [PRs](https://github.com/openebs/openebs/pulls) | [Documentation](https://openebs.io/docs)

### DAOS (SODA Eco Project)

The Distributed Asynchronous Object Storage (DAOS) is an open-source object store designed from the ground up for massively distributed Non Volatile Memory (NVM). DAOS takes advantage of next-generation NVM technology, like Intel© Optane™ Persistent Memory and NVM express (NVMe), while presenting a key-value storage interface on top of commodity hardware that provides features, such as transactional non-blocking I/O, advanced data protection with self-healing, end-to-end data integrity, fine-grained data control, and elastic storage, to optimize performance and cost.

[View Project Code](https://github.com/daos-stack/daos) | [Issues](https://daosio.atlassian.net/jira/software/c/projects/DAOS/issues/DAOS-10028?jql=project%20%3D%20%22DAOS%22%20AND%20labels%20%3D%20SODACODE2022) | [PRs](https://github.com/daos-stack/daos/pulls) | [Documentation](https://docs.daos.io/v2.0/)

### Configurator

Configurator is a version control and a sync service that keeps Kubernetes ConfigMaps and Secrets in sync with the deployments. When a ConfigMap content is changed, Configurator creates a custom resource of type CustomConfigMap (CCM) with a postfix. CCM with a postfix acts like ConfigMap revision. Configurator then copies the modified contents of the ConfigMap in to the CCM resource and triggers a rolling update on deployments using the ConfigMap. Configurator keeps the ConfigMap contents in sync with the deployment revisions with the help of annotations and works well for both rolling updates and rollbacks. Configurator supports GitOps workflows as well.

[View Project Code](https://github.com/gopaddle-io/configurator.git) | [Issues](https://github.com/gopaddle-io/configurator/issues?q=is%3Aissue+is%3Aopen+label%3ASODACODE2022) | [PRs](https://github.com/gopaddle-io/configurator/pulls) | [Documentation](https://gopaddle-io.github.io/configurator/docs/Introduction/)

### CubeFS

CubeFS  is a cloud-native storage platform that provides both POSIX-compliant and S3-compatible interfaces. It is hosted by the Cloud Native Computing Foundation (CNCF) as a sandbox project.

CubeFS has been commonly used as the underlying storage infrastructure for online applications, database or data processing services and machine learning jobs orchestrated by Kubernetes. An advantage of doing so is to separate storage from compute - one can scale up or down based on the workload and independent of the other, providing total flexibility in matching resources to the actual storage and compute capacity required at any given time.

[View Project Code](https://github.com/cubeFS/cubefs) | [Issues](https://github.com/cubeFS/cubefs/issues?q=is%3Aissue+is%3Aopen+label%3ASODACODE2022) | [PRs](https://github.com/cubeFS/cubefs/pulls) | [Documentation](https://cubefs.readthedocs.io/en/latest/)

### kube-fledged
kube-fledged is a kubernetes operator for creating and managing a cache of container images directly on the worker nodes of a kubernetes cluster. It allows a user to define a list of images and onto which worker nodes those images should be cached (i.e. pulled). As a result, application pods start almost instantly, since the images need not be pulled from the registry.

kube-fledged provides CRUD APIs to manage the lifecycle of the image cache, and supports several configurable parameters to customize the functioning as per one's needs.

[View Project Code](https://github.com/senthilrch/kube-fledged) | [Issues](https://github.com/senthilrch/kube-fledged/issues?q=is%3Aissue+is%3Aopen+label%3ASODACODE2022) | [PRs](https://github.com/senthilrch/kube-fledged/pulls) | [Documentation](https://github.com/senthilrch/kube-fledged#readme)

### Storage Benchmark  
The SBK (Storage Benchmark Kit) is an open source software framework for the performance benchmarking of any storage system. If you are curious to measure the maximum throughput performance of your storage device/system, then SBK is the right software for you. The SBK itself is a very high-performance benchmark tool/framework. It massively writes the data to the storage system and reads the data from the storage system. The SBK supports multi writers and readers and also the End to End latency benchmarking. The latency quartiles and percentiles are calculated for complete data written/read without any sampling; hence the percentiles are 100% accurate.

[View Project Code](https://github.com/kmgowda/SBK) | [Issues](https://github.com/kmgowda/SBK/issues?q=is%3Aissue+is%3Aopen+label%3Asodacode2022) | [PRs](https://github.com/kmgowda/SBK/pulls) | [Documentation](https://kmgowda.github.io/SBK/)

### SODA Delfin (SODA Incubator Project)

Delfin, the SODA Infrastructure Manager project, is an open-source project that aims to provide unified, intelligent, and scalable resource management, alert, and performance monitoring.

[View Project Code](https://github.com/sodafoundation/delfin) | [Issues](https://github.com/sodafoundation/delfin/issues?q=is%3Aissue+is%3Aopen+label%3ASODACODE2022) | [PRs](https://github.com/sodafoundation/delfin/pulls) | [Documentation](https://docs.sodafoundation.io/)

### SODA Strato (Multicloud) (SODA Incubator Project)

SODA Multi-cloud project provides a cloud vendor agnostic data management for hybrid cloud, intercloud or intracloud.

[View Project Code](https://github.com/sodafoundation/multi-cloud) | [Issues](https://github.com/sodafoundation/multi-cloud/issues?q=is%3Aissue+is%3Aopen+label%3ASODACODE2022) | [PRs](https://github.com/sodafoundation/multi-cloud/pulls) | [Documentation](https://docs.sodafoundation.io/)

### SODA Dashboard (SODA Incubator Project)

SODA Dashboard provides a front end UI which integrates with the different APIs provided by SODA API. This dashboard can be used to test basic SODA functionality.

[View Project Code](https://github.com/sodafoundation/dashboard) | [Issues](https://github.com/sodafoundation/dashboard/issues?q=is%3Aissue+is%3Aopen+label%3ASODACODE2022) | [PRs](https://github.com/sodafoundation/dashboard/pulls) | [Documentation](https://docs.sodafoundation.io/)

### SODA Installer (SODA Incubator Project)

SODA Installer provides easy installation and basic deployment based on specific configurations for SODA Projects\
[View Project Code](https://github.com/sodafoundation/installer) | [Issues](https://github.com/sodafoundation/installer/issues?q=is%3Aissue+is%3Aopen+label%3ASODACODE2022) | [PRs](https://github.com/sodafoundation/installer/pulls) | [Documentation](https://docs.sodafoundation.io/)

### SODA Terra (API / Controller / Dock) (SODA Incubator Project)

#### SODA API

SODA API is an open source implementation of SODA API Standards for Data and Storage Management.\
[View Project Code](https://github.com/sodafoundation/api) | [Issues](https://github.com/sodafoundation/api/issues) | [PRs](https://github.com/sodafoundation/api/pulls) | [Documentation](https://docs.sodafoundation.io/)

#### SODA Controller

All the control services (like metadata management, scheduler, other bookkeeping, utils etc)\
[View Project Code](https://github.com/sodafoundation/controller) | [Issues](https://github.com/sodafoundation/controller/issues) | [PRs](https://github.com/sodafoundation/controller/pulls) | [Documentation](https://docs.sodafoundation.io/)

#### SODA Dock

SODA Dock is an open source implementation for the unified interface to connect heterogeneous storage backends.\
[View Project Code](https://github.com/sodafoundation/dock) | [Issues](https://github.com/sodafoundation/dock/issues) | [PRs](https://github.com/sodafoundation/dock/pulls) | [Documentation](https://docs.sodafoundation.io/)

### SODA Documentation
Documentation for SODA Foundation and SODA Core projects. Covers code for documentation site generation.  
[Documentation website](https://docs.sodafoundation.io/) | [View Project Code](https://github.com/sodafoundation/documentation) | [Documentation Issues](https://github.com/sodafoundation/documentation/issues) | [Documentation PRs](https://github.com/sodafoundation/documentation/pulls)  
