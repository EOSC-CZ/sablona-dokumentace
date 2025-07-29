
# Technical infrastructure

# Technology

The data centers of the e-Infra repository infrastructure, operated by CESNET are based on object storage utilizing Ceph and Kubernetes cluster technology stack. These data centers are located exclusively within the Czech Republic, meaning all your data remains within the country. The distributed model of these data centers enhances data redundancy through the use of geographical replicas. This approach ensures that your data is protected against media failures, natural disasters, or user errors.

Ceph is an open-source system designed to provide object storage that includes an object store, block store, and distributed file system. Data stored in Ceph is replicated across multiple nodes based on a defined replication policy. CESNET S3 service is a versatile solution suitable for a wide range of use cases, including basic data storage, automated backups, and various data handling applications.

Access to the service is managed through virtual organizations and corresponding groups. S3 is ideal for sharing data between individual users and groups, which may include members from different institutions. Tools for managing users and groups are provided by the e-infrastructure.

For sensitive data, encrypted buckets can be used on the client side, ensuring that even the storage manager does not have access to the data. Client-side encryption also secures data transmission over the network, protecting it from being decrypted in case of eavesdropping.

Data storage and cluster services are certified compliant with information security management system standard ČSN EN ISO/IEC 27001:2014.

[Read more on data infrastructure in e-Infra documentation](https://docs.du.cesnet.cz/en/docs/introduction/introduction)

- *Describe how the repository operates on reliable and stable core infrastructures that maximizes service availability. Indicate hardware and software technologies appropriate to the services it provides to its Designated Community.*
- *Describe what standards does the repository use for reference (e.g., Spatial Data Infrastructure (SDI) standards, OGC, W3C, or ISO 19115), how often are these reviewed and how are the standards implemented. Explain any significant deviations from the standards.*
- *Describe repository plan for infrastructure development.*
- *Describe how is the software inventory maintained and system documentation available.*
- *Indicate how connectivity to public and private networks at a bandwidth that is sufficient to meet the global and/or regional responsibilities of the repository is provided.*

# Security
- *Describe how the repository analyzes potential threats, assess risks, and creates a consistent security system.*
- *Describe damage scenarios based on malicious actions, human error, or technical failure that pose a threat to the repository and its data, products, services, and users. Include measures of likelihood and impact of such scenarios, risk analysis tools in use, decisions which risk levels are acceptable, and determine which measures should be taken to counter the threats to the repository and its Designated Community.*
- *Indicate procedures and arrangements in place to provide swift recovery or backup of essential services in the event of an outage.*

---
Staff positions and roles for technical infrastructure expertise can be found in [Organisational infrastructure](../organizational-documents/organizational-infrastructure.md)
