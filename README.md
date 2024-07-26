# pwncorp

© 2024 Clustering Ninjas

### Project Summary

**Aim:**
To automate the processing and storage of CVE data, ensuring timely updates and enhancing the ability to query this data using advanced machine learning techniques, while maintaining a scalable and efficient infrastructure.

**Implementation:**
- Deployed infrastructure on AWS EKS using Terraform and managed Kubernetes resources with Helm charts and Docker.
- Configured Jenkins for CI/CD pipelines, incorporating Packer for image creation and deploying on EC2 instances with Caddy as a sidecar proxy.
- Developed Kafka-based distributed systems with Go to process and store CVE data in a Postgres database.
- Built a custom Kubernetes operator to process CVE deltas released every hour.
- Automated the CVE data ingestion pipeline, integrating processed data into a vector database to enhance an LLM's capability to answer CVE-related queries.

**Outcome:**
The project successfully created a robust, automated system for processing and storing CVE data, ensuring timely updates and improving query capabilities through machine learning integration. This resulted in enhanced system reliability, data integrity, and overall efficiency in managing and utilizing CVE information.

<img src="https://github.com/csye7125-fall2023-group05/.github/assets/97932746/d5dc9003-8827-4002-9d4d-db4071b205e6)" alt="final-patch" width="800" height="800">


## Topics

- [x] DevOps, GitOps, SRE
- [x] Linux, Shell Scripting
- [x] Version Control with Git
- [x] Cloud Computing
- [x] Microservices Architecture
- [x] Application containerization
- [x] Orchestration of containerized applications using Kubernetes
- [x] Custom Kubernetes Operator
- [x] Identity & Access Management
- [x] Infrastructure as Code
- [x] Service Meshes
- [x] Continuous Integration, Continuous Delivery, and Continuous Deployment
- [x] Operational Visibility (Logging, Metrics, Monitoring, and Alerting)
- [x] Bash/Shell scripting
- [x] Auto-scaling Applications
- [x] Event-driven Architecture
- [x] Serverless Computing
- [x] Securing cloud applications and infrastructure
- [x] Training LLM models

## Authors

- [Piyush Dongre](https://github.com/dongrep)
- [Anuraag Bhatula](https://github.com/local-man)

<!--img src="https://user-images.githubusercontent.com/97932746/201548646-8a8439bd-5f6e-487a-a9b7-1d57ba0187be.png" alt="final-patch" width="500" height="500" -->
