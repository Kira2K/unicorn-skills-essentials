# DevOps potential bullets

## expert-confirmed

### CI/CD design / optimization

- Reduced execution time of a critical build pipeline by about 20% by standardizing GitLab CI templates and Kubernetes-based runners.
- Designed and maintained Jenkins/GitLab CI pipelines for 20+ repositories with build-test-deploy stages, linting, unit tests, and versioning.
- Re-engineered firmware build processes, reducing build time from 5 hours to 1 hour.
- Cut the deployment cycle by about 40% through CI/CD refactoring, Bitbucket Pipelines for daily server updates, and a lighter deployment path for low-risk changes.

### Infrastructure as Code / provisioning

- Standardized infrastructure across environments with reusable Terraform modules and Ansible roles, bringing each environment to a consistent, reproducible state.
- Built reusable Terraform modules with remote state and CI-side validation, plus Ansible roles for OS and middleware provisioning across the fleet.
- Automated infrastructure provisioning across multiple environments using Terraform, decreasing deployment time from 2 hours to 25 minutes while keeping deployments uninterrupted.
- Implemented an Ansible configuration management strategy, saving over 20 hours per week in manual server configuration.
- Automated Kubernetes workload deployments and Terraform manifests, achieving 100% Infrastructure as Code coverage.

### Kubernetes orchestration / deployment

- Designed, built, and supported on-prem Kubernetes clusters with 50+ nodes and 200+ pods; automated bootstrap/scale and managed CNI/CSI, Helm, ArgoCD, ingress, and persistent storage.
- Optimized AWS spending by 40% through consolidating environments into a single EKS cluster and simplifying the infrastructure layout.

### Cloud / multi-cloud / multi-region

- Achieved 15% AWS cost savings and 30% latency improvement by migrating from AWS API Gateway to APISIX, handling 10,000 requests per second.
- Defined Terraform manifests and deployed full-scale production environments for new AWS regions across EKS, EC2, RDS, MSK, S3, ElastiCache, DocumentDB, Route53, CloudFront and VPC.

### Infrastructure migration A→B

- Migrated services from Docker Swarm to Kubernetes and automated infrastructure provisioning with Terraform, Ansible, Helm and Kustomize.
- Migrated 12+ microservices from Docker-based setups to Kubernetes using Helm and KEDA-based autoscaling, reducing monthly infrastructure costs by 25%.
- Managed end-to-end infrastructure for a SaaS storage product on Kubernetes, reducing deployment time by about 40%, and migrated core infrastructure to Kubernetes across GKE/AWS.

### On-prem / hybrid infrastructure

- Automated server provisioning and configuration management across 100+ bare-metal servers, reducing manual operations time by 70%.

### Coding for infrastructure / automation

- Developed and deployed a custom Kubernetes Operator in Go to block HPA scaling in the presence of infrastructure errors.

## additional

### Kubernetes lifecycle / cluster internals

- Operated multiple production Kubernetes clusters using custom Ansible automation around kubeadm, kubelet, and kubectl, including version upgrades, etcd maintenance, and Nginx Ingress configuration.

### Backup / DR / restore

- recovery from hours→<30 min.
- multi-site DR.
- AWS Backup cost optimization.

### GitOps / ArgoCD / FluxCD

- ArgoCD ApplicationSets.
- FluxCD.
- declarative ArgoCD configuration.

### Networking / VPN / ingress / load balancing

- Transit Gateway/VPN peering.
- VPN/BGP.
- cloud LBs/CDN/Ingress.

### Messaging / cache infrastructure

- Kafka 6+ brokers + Redis HA, p99≤5 ms.
- Kafka/RabbitMQ operations.

### Virtualization / private cloud

- vSphere + DR.
- OpenStack/OpenNebula.
- Proxmox/Hyper-V.

### Release automation / environment standardization

- standardized environments.
- deployment manifests/charts.
- reusable pipelines as code.

### Performance / capacity / autoscaling / rightsizing

- resource optimization at 6,000 RPS.
- Tuned Linux kernel parameters via sysctl for high-load workloads.
- Tuned conntrack parameters for high-load networking.
- capacity planning + p99≤5 ms.
- latency −30% at 10k RPS.
