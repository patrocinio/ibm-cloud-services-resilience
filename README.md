# ibm-cloud-services-resilience
This repository provides links to the HA / DR / Backup information for many IBM Cloud Services.

| Services | DR Capabilities | DR Responsibility | Documentation | RTO |
|---|---|---|---|---|
| CIS | Service available in multiple regions | Client | [Improving application reliability and scalability with Global Load Balancing from IBM Cloud Internet Services](https://cloud.ibm.com/docs/infrastructure/cis?topic=cis-improving-application-reliability-and-scalability-with-global-load-balancing-from-ibm-cloud-internet-services) | 5 seconds TTL:  Link |
| Console | Service available in multiple regions | IBM | N/A |
| CFEE | Service available in multiple regions | Client | TBD | depends on Client DR Implementation |
| Cloudant | Service available in multiple regions | Client | [Disaster recovery and backup](https://cloud.ibm.com/docs/services/Cloudant/guides?topic=cloudant-disaster-recovery-and-backup) | depends on Client DR Implementation |
| CSE | Service available in multiple regions | IBM | ? |
| IAM | Service available in multiple regions | IBM | N/A |
| IBM Cloud DB Elastic Search | ervice available in multiple regions | Client | [Managing Backups](https://cloud.ibm.com/docs/services/databases-for-elasticsearch?topic=cloud-databases-dashboard-backups) | depends on Client DR Implementation |
| IBM Cloud DB Mongo DB | Service available in multiple regions | Client | [Managing Backups](https://cloud.ibm.com/docs/services/databases-for-mongodb?topic=cloud-databases-dashboard-backups) |
| IBM Cloud DB Postgres | Service available in multiple regions | Client | [Managing Backups](https://cloud.ibm.com/docs/services/databases-for-postgresql?topic=cloud-databases-dashboard-backups) | depends on Client DR Implementation |
| IBM Cloud Object Storage | Service available in multiple regions | Client | [About IBM Cloud Object Storage](https://cloud.ibm.com/docs/services/cloud-object-storage/basics?topic=cloud-object-storage-about-ibm-cloud-object-storage) | depends on Client DR Implementation |
| IKS | Service available in multiple regions | Client | [High availability for IBM Cloud Kubernetes Service](https://cloud.ibm.com/docs/containers?topic=containers-ha#ha) [Planning your cluster for high availability](https://cloud.ibm.com/docs/containers?topic=containers-ha_clusters#ha_clusters) | depends on Client DR Implementation |
| Key Protect | Regional: IBM is responsible for bringing the service back in a different Region | IBM | TBD | the current documented RTO is <1 day |
| Message Hub/Event streams | Service available in multiple regions | Client | [FAQs](https://cloud.ibm.com/docs/services/EventStreams?topic=eventstreams-faqs#disaster_recovery) | depends on Client DR Implementation |
| Push Notification | Regional | IBM | TBD | the current documented RTO is 1-3 days |
| Virtual Private Cloud | Service available in multiple regions | Client | [Introduction](https://cloud.ibm.com/apidocs/vpc-on-classic) | depends on Client DR Implementation |
| Watson Natural Language Understanding (NLU) | Client is responsible for restoring the service back in a different Region | Client | [High availability and disaster recovery](https://cloud.ibm.com/docs/services/natural-language-understanding?topic=natural-language-understanding-ha-dr) | depends on Client DR Implementation |

Other documentation:

* [Build resilient applications on the cloud](https://www.ibm.com/cloud/garage/architectures/resilience/allresiliencesolutions)
* [Hybrid integration for solutions that span environments](https://www.ibm.com/cloud/garage/architectures/hybridIntegration/hybrid_dr_microservices)
* [Hybrid integration for solutions that span environments](https://www.ibm.com/cloud/garage/architectures/hybridIntegration/hybrid_connectivity)
* [Strategies for resilient applications](https://cloud.ibm.com/docs/tutorials?topic=solution-tutorials-strategies-for-resilient-applications#strategies-for-resilient-applications)
