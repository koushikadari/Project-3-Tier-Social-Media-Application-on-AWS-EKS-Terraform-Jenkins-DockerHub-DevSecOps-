# Project-3-Tier-Social-Media-Application-on-AWS-EKS-Terraform-Jenkins-DockerHub-DevSecOps-
Project: 3-Tier Social Media Application on AWS EKS (Terraform, Jenkins, DockerHub, DevSecOps)

# Overview:
+ I worked on designing and deploying a 3-tier social media application on Amazon EKS using Terraform for Infrastructure as Code and Jenkins for CI/CD automation. The project also included security scanning, artifact storage, and Kubernetes-based deployment.
+ Built and deployed a 3-tier social media application on AWS EKS using Terraform and Jenkins. Implemented CI/CD pipelines with DockerHub image publishing, stored artifacts in S3, and integrated Trivy, OWASP, and SonarQube for security and code quality. Automated Kubernetes deployments with scalable, secure infrastructure.

# step-1:
+ Built a complete EKS cluster using Terraform modules:
   *  VPC, Subnets, Route Tables
   *  EKS Control Plane
   *  Managed Node Groups
   *  IAM roles and policies

# step-2:
+ CI/CD Pipeline with Jenkins:
   * Source code checkout
   * Build and packaging
   * Docker image creation
   * Vulnerability scanning
   * Pushing image to DockerHub
   * Kubernetes deployment to EKS

# step-3:
 + Artifact & Image Management:
    * Build artifacts stored in Amazon S3 with versioning enabled.
    * Docker images pushed to DockerHub using automated Jenkins pipelines.
  

# step-4:
+ Containerization & Deployment on EKS:
    * Dockerized microservices for frontend, backend, and database layer.
    * Deployed on EKS using:
         @ Kubernetes Deployments
         @ Services (ClusterIP / NodePort)
         @ Ingress with load balancer
    * Implemented Horizontal Pod Autoscaler (HPA) and readiness/liveness probes.

# step-5:
+ DevSecOps Implementation:
    * OWASP Dependency Check → Application dependency vulnerability scanning
    * Trivy → Container image & IaC vulnerability scanning
    * SonarQube → Code quality, bug detection, code smells, coverage analysis
 
# step-6:
+ Logging & Monitoring:
   * Configured CloudWatch for EKS logs and application logs.
   * Set up metric monitoring for pod usage, cluster health, and scaling.








