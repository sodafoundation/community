# [SODA Foundation](https://sodafoundation.io/) Project Ideas for GSoC 2022

The below are the project ideas from [SODA Foundation](https://sodafoundation.io/) for GSoC 2022. We will be providing more information once the contributors are on boarded with specific mentors and mentoring support.
We will guide from learning the background, basic setup and guidance to the requirements and development of each project.
Please join our slack once you are interested in the project where we can have more communication. 
Based on the project finalization, we will have specific slack channels the projects. 
Additionally you will get a chance to connect and network with SODA Foundation community and also participate our global events like SODACON, SODACODE(hackathon) and more.
Thanks for joining and all the very best.

# Project Ideas List

## 1 : Serve my metdata!
*Metadata Server with Basic APIs for Data Lake solution*

**Project Type: Development**

**Project Description:**

Develop a metadata management server with REST APIs for basic CRUD(Create/Read/Update/Delete) operation. Need to have a metadata data base. This will include developing a REST API server, some basic API definitions (may be in a swagger file). We would like to see the metadata get stored in a local db.

**Expected Outcome:**
- REST API Server which can be accessed through POSTMAN or similar tool
- List of APIs for metadata management CRUD operations
- Has local metadata storage
- Demo with testing through command line/api interface along with an introduction report.

**Skills required/preferred:**
- Programming Skills in golang (we prefer) or you can develop in any other language.
- Undersanding of REST API
- Client - Server understanding
- Basic understanding of metadata

**Possible Mentors:**
- We will provided dedicated project mentor for you and dedicated slack channel for communication.
- We will also have some community members / maintainers to support

**Expected size of project (175 or 350 hour):**
350 Hours


## 2 : Search! Search! Search Engine!
*Build a simple search engine with specific performance indicators*

**Project Type: Development**

**Project Description:**

Develop a search engine using existing or new search algorithms for metadata search. It is targeted for a data lake solution. You can create the search engine independently as well which can be a pluggable to external solutions (means, you provide the right interfaces to use your search engine). You can also provide the performance metrics of your solution and also the key unique search attributes.

**Expected Outcome:**
- Search engine can be used independently with proper APIs / internfaces
- Show case the key uniqueness of your search algo (you can provide any detailed analysis)
- Demo with testing through command line/api interface along with an introduction report.

**Skills required/preferred:**
- Programming Skills in golang (we prefer) or you can develop in any other language.
- Undersanding of search and search algos
- Basic understanding of metadata

**Possible Mentors:**
- We will provided dedicated project mentor for you and dedicated slack channel for communication.
- We will also have some community members / maintainers to support

**Expected size of project (175 or 350 hour):**
350 Hours


## 3 : Where is my cache?!
*Developing a cache engine for improving the performance for data lake*

**Project Type: Development**

**Project Description:**

Develop a cache engine using existing tools/cache solutions(like redis) or new ideas. Showcase the performance indicators of the solution especially for metadata management. With your cache implementaiton and without, please showcase a workload performance. You can use any platform to showcase.

**Expected Outcome:**
- The cache engine
- Show case the key uniqueness of your cache (you can provide any detailed analysis)
- Demo with testing through command line/api interface along with an introduction report.

**Skills required/preferred:**
- Programming Skills in golang (we prefer) or you can develop in any other language.
- Undersanding of cache and how it impacts the performance

**Possible Mentors:**
- We will provided dedicated project mentor for you and dedicated slack channel for communication.
- We will also have some community members / maintainers to support

**Expected size of project (175 or 350 hour):**
350 Hours


 ## 4 : Monit Now!
*Performance Monitoring for Storage in Kubernetes*

**Project Type : Porting and Enhancement**

**Project Description:**

We have the existing project for storage monitoring at [https://github.com/sodafoundation/delfin](https://github.com/sodafoundation/delfin). Need to port the same for Kubernetes (some working PoC is already available). We need to build native kubernetes APIs through CRDs and controllers. Provide the custom APIs of delfin in k8s. You can at least implement for Resource OR alert OR performance metrics (need not be for all supported features)

**Expected Outcome:**
- Custom APIs implemented to access the delfin features
- Delfin integrated in k8s (we already have basic running of delfin in k8s, it can be a good starting point for you!)
- Demo with all basic delfin APIs through k8s custom APIs (at least getting the data and configure) through command line/api interface along with an introduction report.

**Skills required/preferred:**
- Programming Skills in python & golang.
- Undersanding of Kubernetes Operators(CRD, Controller), K8S API, Basic cluster deployment

**Possible Mentors:**
- We will provided dedicated project mentor for you and dedicated slack channel for communication.
- We will also have some community members / maintainers to support

**Expected size of project (175 or 350 hour):**
175 Hours


 ## 5 : Hi AI!
*Build Intelligent Insights*

**Project Type : Development and Enhancement**

**Project Description:**

We have the existing project for storage monitoring at [https://github.com/sodafoundation/delfin](https://github.com/sodafoundation/delfin). It has interfaces to get all the resource, alert and performance monitoring data. You need to apply AI algorithms (existing or new) to do predictive analysis on the monitoring data to provide deeper insights. We support kafka interface already, you may use the same or any new exporter can be developed

**Expected Outcome:**
- The statistical data from delfin can be analysed through the solution. It gives indicators and prediction or anomalies
- Exporter for your solution (you can use existing kafka or develop one)
- Demo with Delfin and your analytics engine together. Project report

**Skills required/preferred:**
- Programming Skills in python.
- Undersanding of ML/AI, ML algos, predictive analysis, anomaly detection
- At least you know one ML algos to use

**Possible Mentors:**
- We will provided dedicated project mentor for you and dedicated slack channel for communication.
- We will also have some community members / maintainers to support

**Expected size of project (175 or 350 hour):**
175 Hours (If you are using any existing ML algo)
350 Hours (If you plan to develop and enhance any existing algos)

## 6 : Let me port it!
Port Delfin to different Operating Systems

**Project Type : Porting**

**Project Description:**

We have the existing project for storage monitoring at [https://github.com/sodafoundation/delfin](https://github.com/sodafoundation/delfin). It is supported on Ubuntu versions. We would like you to port this to CentOS, Redhat and Windows.

**Expected Outcome:**
- Delfin works with all the basic features on the ported OS version
- Demo and Project report

**Skills required/preferred:**
- Programming Skills in python.
- Basic understanding of application porting to new OS (optional! - In fact you start learing this project as well!)

**Possible Mentors:**
- We will provided dedicated project mentor for you and dedicated slack channel for communication.
- We will also have some community members / maintainers to support

**Expected size of project (175 or 350 hour):**
175 Hours for each OS porting

**Additional Notes:**
- Each OS version can be different project. While accepting the project we will decide the OS version mutually and you can work on it.



 ## 7: Show off the data!
*Custom visualization for Monitoring data*

**Project Type : Visualization Development**

**Project Description:**

We have the existing project for storage monitoring at [https://github.com/sodafoundation/delfin](https://github.com/sodafoundation/delfin). It supports a basic dashboard based on prometheus and grafana. You can build custom visualization using custom visualization profiles to provide useful insights and representation of the data. As we have resource, alert and performance data from various storage vendors and models, providing a comprehensive visualization will very useful for users.

**Expected Outcome:**
- Delfin with custom visualization
- Just show off your creativity with any type of useful represenation of the data!
- You can also create custom webpages or dashboard based on SODA Dashboard [https://github.com/sodafoundation/dashboard](https://github.com/sodafoundation/dashboard)
- Demo and Project report

**Skills required/preferred:**
- Any web programming (prefer JS/typescript ....)
- Basic understanding of visualisation of statistical data, graphs, charts etc
- Experience of understanding of Prometheus and Grafana can really help you! :)

**Possible Mentors:**
- We will provided dedicated project mentor for you and dedicated slack channel for communication.
- We will also have some community members / maintainers to support

**Expected size of project (175 or 350 hour):**
175 Hours

**Additional Notes:**
- If you wish to define a specific set of visualization types and work on it, we can define during the project planning. In that case, even multiple members can work on different sets based on the interest.


 ## 8: Store with Containers
*Integrate more Container Storage plugins for Kubernetes in SODA CSI*

**Project Type : Integration/Development**

**Project Description:**

 SODA CSI(Container Storage Interface) is a typical CSI plugin which supports multiple vanilla CSI plugins. You need to integrate and qualify more CSI plugins to SODACSI. You can also provide enhancement to SODACSI, especially to manage multiple CSI plugins and provide consolidated health and other information about it
 
 **Expected Outcome:**
- Showcase at least 1 new CSI plugin working with SODACSI
- In case you do not have storage, hard to test. But even if you show the integration with code instrumentation, we can accept
- Show the enhancements done on SODACSI (optional)
- Demo and Project report

**Skills required/preferred:**
- Programming Skills in golang.
- Basic understanding of Storage, CSI, Kubernetes basic installation/app deployment
- Understanding of SODACSI. You can get the info [here](https://docs.sodafoundation.io/guides/user-guides/csi/ceph-csi/)

**Possible Mentors:**
- We will provided dedicated project mentor for you and dedicated slack channel for communication.
- We will also have some community members / maintainers to support

**Expected size of project (175 or 350 hour):**
175 Hours (per CSI plugin)

**Additional Notes:**
- We can define one CSI plugin during the project planning
- Different sub projects by contributors possible for different CSI plugin

## 9: So much data, So Many Clouds..
*Data migration workflows development and automation*

**Project Type : Development**

**Project Description:**

We have a multi-cloud project [https://github.com/sodafoundation/multi-cloud](https://github.com/sodafoundation/multi-cloud) which can work across different cloud vendors through a unified API interface. It also supports data migration and lifecycle management features. You need to build custom workflows and automation policies for data movement from one cloud to another. The policy can be modified by the user based on the needs and schedule. So scheduling and policy management operations to be supported along with role based access.

**Expected Outcome:**
- Create custom workflows for multicloud data management
- Automation policies defined
- Demo and Project report

**Skills required/preferred:**
- Programming Skills in golang.
- Basic understanding of Data Migration, Cloud
- Understanding of [SODA Multicloud](https://docs.sodafoundation.io/guides/user-guides/multi-cloud/) and [Orchestration](https://docs.sodafoundation.io/guides/developer-guides/orchestration/)

**Possible Mentors:**
- We will provided dedicated project mentor for you and dedicated slack channel for communication.
- We will also have some community members / maintainers to support

**Expected size of project (175 or 350 hour):**
175 Hours 


 ## 10: Archive Smartly
*Hybrid Smart Archival Solution across Edge and Cloud*

**Project Type : Enhancement / Development**

**Project Description:**

We have a multi-cloud project [https://github.com/sodafoundation/multi-cloud](https://github.com/sodafoundation/multi-cloud) which can work across different cloud vendors through a unified API interface. It supports basic data archival from on premise to cloud. Utilizing these existing features, we need to build data archival with more intelligence with custom policies and scheduling. Needs to be fully automated. Along with this, we need to provide the archival solution to do data archival from Edge location to any supported cloud.

**Expected Outcome:**
- Show case data archival from edge to any cloud or vice versa.
- Show case data restore from edge to any cloud or vice versa
- Demo and Project report

**Skills required/preferred:**
- Programming Skills in golang.
- Basic understanding of Data Migration, Cloud, Edge computing, Data Archival, secondary storages
- Understanding of [SODA Multicloud](https://docs.sodafoundation.io/guides/user-guides/multi-cloud/) 

**Possible Mentors:**
- We will provided dedicated project mentor for you and dedicated slack channel for communication.
- We will also have some community members / maintainers to support

**Expected size of project (175 or 350 hour):**
350 Hours


# SODA Foundation Links

## Development Community
[https://sodafoundation.io/slack/](https://sodafoundation.io/slack/)

## Website, Twitter, Linkedin
Website : https://www.sodafoundation.io/

Twitter: https://twitter.com/sodafoundation

Linkedin: https://www.linkedin.com/company/sodafoundation

## Documentation
[https://docs.sodafoundation.io](https://docs.sodafoundation.io/)

## Latest Releases
[https://github.com/sodafoundation/soda/releases](https://github.com/sodafoundation/soda/releases)


