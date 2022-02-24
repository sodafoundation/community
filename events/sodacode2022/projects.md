## SODACODE2022 Participating Projects
As part of the SODACODE 2022, contributions to the following projects will be considered.

### SODA Delfin
Delfin, the SODA Infrastructure Manager project, is an open-source project that aims to provide unified, intelligent, and scalable resource management, alert, and  performance monitoring.  
[View Project Code](https://github.com/sodafoundation/delfin) | [Delfin Issues](https://github.com/sodafoundation/delfin/issues) | [Delfin PRs](https://github.com/sodafoundation/delfin/pulls) | [Documentation](https://docs.sodafoundation.io)

### SODA Strato (Multicloud)
SODA Multi-cloud project provides a cloud vendor agnostic data management for hybrid cloud, intercloud or intracloud.  
[View Project Code](https://github.com/sodafoundation/multi-cloud) | [Multicloud Issues](https://github.com/sodafoundation/multi-cloud/issues) | [Multicloud PRs](https://github.com/sodafoundation/multi-cloud/pulls) | [Documentation](https://docs.sodafoundation.io)

### SODA Dashboard
SODA Dashboard provides a front end UI which integrates with the different APIs provided by SODA API. This dashboard can be used to test basic SODA functionality.  
[View Project Code](https://github.com/sodafoundation/dashboard) | [Dashboard Issues](https://github.com/sodafoundation/dashboard/issues) | [Dashboard PRs](https://github.com/sodafoundation/dashboard/pulls) | [Documentation](https://docs.sodafoundation.io)

### SODA Installer
SODA Installer provides easy installation and basic deployment based on specific configurations for SODA Projects
[View Project Code](https://github.com/sodafoundation/installer) | [Installer Issues](https://github.com/sodafoundation/installer/issues) | [Installer PRs](https://github.com/sodafoundation/installer/pulls) | [Documentation](https://docs.sodafoundation.io)

### Configurator  
Configurator is a version control and a sync service that keeps Kubernetes ConfigMaps and Secrets in sync with the deployment. Configurator uses CRDs to create CustomConfigMaps and CustomSecrets that in turn create ConfigMaps and Secrets with a postfix. As and when a change is detected in the CustomConfigMap or CustomSecret, Configurator automatically generates a new ConfigMap with a new postfix. This acts like a version control for the ConfigMaps. In order to keep the deployments and statefulsets in sync with the ConfigMap and Secret version, users must start with creating a CustomConfigMap as the first step. This creates a new ConfigMap with a postfix ie., first version. Users then have to reference the ConfigMap along with the postfix in their deployment and statefulset specifications. From them on, users can edit the CustomConfigMap directly. Any change in the CustomConfigMap will be automatically rolled out to all the deployments and statefulsets referencing the initial configMap version. A change in ConfigMap not only creates a new ConfigMap version, but also rolls out a new deployment version. This enables both rolling update and rollback of ConfigMaps in sync with the deployment versions.

[View Project Code](https://github.com/gopaddle-io/configurator.git) | [Issues](https://github.com/gopaddle-io/configurator/issues) | [PRs](https://github.com/gopaddle-io/configurator/pulls) | [Documentation](https://gopaddle-io.github.io/configurator/docs/Introduction/)

### Cortx  
CORTX is a distributed object storage system designed for great efficiency, massive capacity, and high HDD-utilization. CORTX is 100% Open Source. Most of the project is licensed under the Apache 2.0 License and the rest is under AGPLv3; check the specific License file for each submodule to determine which is which.

[View Project Code](https://github.com/Seagate/CORTX) | [Issues](https://github.com/Seagate/cortx/issues) | [PRs](https://github.com/Seagate/cortx/pulls) | [Documentation](https://github.com/Seagate/cortx/blob/main/QUICK_START.md)

### CubeFS  

CubeFS  is a cloud-native storage platform that provides both POSIX-compliant and S3-compatible interfaces. It is hosted by the Cloud Native Computing Foundation (CNCF) as a sandbox project.

CubeFS has been commonly used as the underlying storage infrastructure for online applications, database or data processing services and machine learning jobs orchestrated by Kubernetes. An advantage of doing so is to separate storage from compute - one can scale up or down based on the workload and independent of the other, providing total flexibility in matching resources to the actual storage and compute capacity required at any given time.

[View Project Code](https://github.com/cubeFS/cubefs) | [Issues](https://github.com/cubeFS/cubefs/issues) | [PRs](https://github.com/cubeFS/cubefs/pulls) | [Documentation](https://cubefs.readthedocs.io/en/latest/)

### Karmada  

Karmada (Kubernetes Armada) is a Kubernetes management system that enables you to run your cloud-native applications across multiple Kubernetes clusters and clouds, with no changes to your applications. By speaking Kubernetes-native APIs and providing advanced scheduling capabilities, Karmada enables truly open, multi-cloud Kubernetes.

Karmada aims to provide turnkey automation for multi-cluster application management in multi-cloud and hybrid cloud scenarios, with key features such as centralized multi-cloud management, high availability, failure recovery, and traffic scheduling.

[View Project Code](https://github.com/karmada-io/karmada) | [Issues](https://github.com/karmada-io/karmada/issues) | [PRs](https://github.com/karmada-io/karmada/pulls) | [Documentation](https://github.com/karmada-io/karmada/blob/master/README.md)

### KubeEdge  

KubeEdge is an open source system for extending native containerized application orchestration capabilities to hosts at Edge.It is built upon kubernetes and provides fundamental infrastructure support for network, app. deployment and metadata synchronization between cloud and edge. Kubeedge is licensed under Apache 2.0. and free for personal or commercial use absolutely. We welcome contributors!

Our goal is to make an open platform to enable Edge computing, extending native containerized application orchestration capabilities to hosts at Edge, which is built upon kubernetes and provides fundamental infrastructure support for network, app deployment and metadata synchronisation between cloud and edge.

[View Project Code](https://github.com/kubeedge) | [Issues](https://github.com/kubeedge/kubeedge/issues) | [PRs](https://github.com/kubeedge/kubeedge/pulls) | [Documentation](https://kubeedge.io/en/)

### kube-fledged
kube-fledged is a kubernetes operator for creating and managing a cache of container images directly on the worker nodes of a kubernetes cluster. It allows a user to define a list of images and onto which worker nodes those images should be cached (i.e. pulled). As a result, application pods start almost instantly, since the images need not be pulled from the registry.

kube-fledged provides CRUD APIs to manage the lifecycle of the image cache, and supports several configurable parameters to customize the functioning as per one's needs.

[View Project Code](https://github.com/senthilrch/kube-fledged) | [Issues](https://github.com/senthilrch/kube-fledged/issues) | [PRs](https://github.com/senthilrch/kube-fledged/pulls) | [Documentation](https://github.com/senthilrch/kube-fledged#readme)

### LINSTOR  
LINSTOR is a configuration management system for storage on Linux systems. It manages LVM logical volumes and/or ZFS ZVOLs on a cluster of nodes. It leverages DRBD for replication between different nodes and to provide block storage devices to users and applications. It manages snapshots, encryption and caching of HDD backed data in SSDs via bcache.

[View Project Code](https://github.com/LINBIT/linstor-server) | [Issues](https://github.com/LINBIT/linstor-server/issues) | [PRs](https://github.com/LINBIT/linstor-server/pulls) | [Documentation](https://linbit.com/drbd-user-guide/linstor-guide-1_0-en/)

### OpenEBS  
OpenEBS is Kubernetes native Container Attached Storage solution that makes it possible for Stateful applications to easily access Dynamic Local PVs or Replicated PVs. By using the Container Attached Storage pattern users report lower costs, easier management, and more control for their teams.

OpenEBS helps Developers and Platform SREs easily deploy Kubernetes Stateful Workloads that require fast and highly reliable container attached storage. OpenEBS turns any storage available on the Kubernetes worker nodes into local or distributed Kubernetes Persistent Volumes.

[View Project Code](https://github.com/openebs/openebs) | [Issues](https://github.com/openebs/openebs/issues) | [PRs](https://github.com/openebs/openebs/pulls) | [Documentation](https://openebs.io/docs)

### Storage Benchmark  
The SBK (Storage Benchmark Kit) is an open source software framework for the performance benchmarking of any storage system. If you are curious to measure the maximum throughput performance of your storage device/system, then SBK is the right software for you. The SBK itself is a very high-performance benchmark tool/framework. It massively writes the data to the storage system and reads the data from the storage system. The SBK supports multi writers and readers and also the End to End latency benchmarking. The latency quartiles and percentiles are calculated for complete data written/read without any sampling; hence the percentiles are 100% accurate.

[View Project Code](https://github.com/kmgowda/SBK) | [Issues](https://github.com/kmgowda/SBK/issues) | [PRs](https://github.com/kmgowda/SBK/pulls) | [Documentation](https://kmgowda.github.io/SBK/)
