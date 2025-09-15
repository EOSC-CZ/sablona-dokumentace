
# Technical infrastructure

# Hardware

The data centers of the National Repository Platform infrastructure, operated by CESNET are located in several places within the Czech Republic, meaning all your data remains within the country. The distributed model of these data centers enhances data redundancy through the use of geographical replicas. This approach ensures that your data is protected against media failures, natural disasters, or user errors.

# Software

On top of the open source software stack this repository uses [InvenioRDM](https://inveniordm.docs.cern.ch/features/), research data management platform from CERN, scalable to management of millions of records and petabytes of data. InvenioRDM is interoperable with REST APIs, harvestable via OAI-PMH according to the OpenAIRE guidelines and has a metadata model based on the DataCite Metadata Schema.

Storage and virtualisation of the software technology stack in use are based on object storage utilizing [Ceph](https://docs.ceph.com/en/latest/) and [Kubernetes](https://kubernetes.io/docs/home/) cluster. Ceph is an open-source system designed to provide object storage that includes an object store, block store, and distributed file system. Data stored in Ceph is replicated across multiple nodes based on a defined replication policy. For sensitive data, encrypted buckets can be used on the client side, ensuring that even the storage manager does not have access to the data. Client-side encryption also secures data transmission over the network, protecting it from being decrypted in case of eavesdropping.

Access to the services is managed through virtual organizations and corresponding groups, which may include members from different institutions. Tools for managing users and groups are provided by the [Authentication and authorization infrastructure (AAI)](https://docs.account.e-infra.cz/en/docs/access/perun). This AAI, developed jointly by CESNET and Masaryk University, implements he European initiative AARC (Authentication and Authorisation for Research and Collaboration) [Blueprint Architecture](https://aarc-community.org/architecture/) and connects with academic identity federations through the international [eduGAIN network](https://edugain.org), allowing management of users from academic organizations outside the Czech Republic.


[Read more on data infrastructure in NRP documentation](https://docs.nrp.eosc.cz/)


- *Describe how the repository operates on reliable and stable core infrastructures that maximizes service availability. Indicate hardware and software technologies appropriate to the services it provides to its Designated Community.*
- *Describe what standards does the repository use for reference (e.g., Spatial Data Infrastructure (SDI) standards, OGC, W3C, or ISO 19115), how often are these reviewed and how are the standards implemented. Explain any significant deviations from the standards.*
- *Describe repository plan for infrastructure development.*
- *Describe how is the software inventory maintained and system documentation available.*
- *Indicate how connectivity to public and private networks at a bandwidth that is sufficient to meet the global and/or regional responsibilities of the repository is provided.*

# Security

Data storage and cluster services are certified compliant with information security management system standard ČSN EN ISO/IEC 27001:2014.

Te key components of the software stack are actively developped and maintained with corresponding security bug reporting systems. CESNET is participating in development of the main repository system, InvenioRDM. Each major release of the Invenio RDM is tested to be production-grade ready. Repository is re-deployed twice a year with all software components updated versions and fixes.

[Read more on security services in place on CESNET website](https://www.cesnet.cz/en/services/security-4)


- *Describe how the repository analyzes potential threats, assess risks, and creates a consistent security system.*
- *Describe damage scenarios based on malicious actions, human error, or technical failure that pose a threat to the repository and its data, products, services, and users. Include measures of likelihood and impact of such scenarios, risk analysis tools in use, decisions which risk levels are acceptable, and determine which measures should be taken to counter the threats to the repository and its Designated Community.*
- *Indicate procedures and arrangements in place to provide swift recovery or backup of essential services in the event of an outage.*

---
Staff positions and roles for technical infrastructure expertise can be found in [Organisational infrastructure](../organizational-documents/organizational-infrastructure.md)
