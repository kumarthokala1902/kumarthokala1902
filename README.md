<div align="center">

# Building Reliable, Scalable, and Secure Infrastructure

**Cloud Infrastructure &nbsp;•&nbsp; Platform Engineering &nbsp;•&nbsp; Site Reliability**

[![Profile Views](https://komarev.com/ghpvc/?username=kumarthokala1902&style=flat-square&color=0a0a0a&label=PROFILE+VIEWS)](https://github.com/kumarthokala1902)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kumarreddythokala/)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:kumarreddythokala13@gmail.com)

</div>

<br>

## Introduction

I am an entry-level engineer working at Amazon, currently building toward a career in Cloud / DevOps / Platform Engineering. I do not have prior professional experience in infrastructure roles — my focus is on learning and applying production-grade practices.

My focus areas are cloud infrastructure, deployment automation, and observability. Every project in this profile is built with production practices in mind: version-controlled, reproducible, and monitored.

<br>

## Current Position

<div align="center">

**ML Data Associate @ Amazon**

</div>

<br>

## Engineering Philosophy

- **Production-first, not proof-of-concept.** Every project is built to run continuously, not to be demoed once.
- **Automate the reproducible, document the irreducible.** If a process is repeated more than twice, it belongs in a pipeline, not in a runbook.
- **Design for failure, not around it.** Systems should degrade predictably and recover automatically before they require a human.
- **Observability is not optional.** If a system cannot be measured, it cannot be operated. Metrics, logs, and traces are part of the design, not an afterthought.
- **Infrastructure is code, and code is reviewed.** Manual changes to production infrastructure are treated as incidents waiting to happen.
- **Security is a default, not a phase.** Least privilege, secrets management, and network segmentation are considered at design time.

<br>

## Core Expertise

<table>
<tr>
<td valign="top" width="33%">

**Cloud & Infrastructure**
- AWS Core Services (EC2, VPC, IAM)
- Infrastructure as Code (Terraform)
- Container Orchestration (Kubernetes, EKS)
- Serverless & Managed Compute (ECS, Fargate)

</td>
<td valign="top" width="33%">

**Delivery & Automation**
- CI/CD Pipeline Design
- GitHub Actions / Jenkins
- GitOps Workflows
- Automated Deployment Strategies

</td>
<td valign="top" width="33%">

**Reliability & Operations**
- Monitoring & Observability
- Incident Response Fundamentals
- High Availability Design
- Disaster Recovery Planning

</td>
</tr>
</table>

<br>

## Tech Stack

<div align="center">

**Cloud & Infrastructure**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=FF9900)
![EC2](https://img.shields.io/badge/EC2-FF9900?style=for-the-badge&logo=amazon-ec2&logoColor=white)
![S3](https://img.shields.io/badge/S3-569A31?style=for-the-badge&logo=amazon-s3&logoColor=white)
![VPC](https://img.shields.io/badge/VPC-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=FF9900)
![IAM](https://img.shields.io/badge/IAM-DD344C?style=for-the-badge&logo=amazon-aws&logoColor=white)
![CloudWatch](https://img.shields.io/badge/CloudWatch-FF4F8B?style=for-the-badge&logo=amazon-cloudwatch&logoColor=white)

**Containers & Orchestration**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![EKS](https://img.shields.io/badge/EKS-FF9900?style=for-the-badge&logo=amazon-eks&logoColor=white)
![ECS](https://img.shields.io/badge/ECS-FF9900?style=for-the-badge&logo=amazon-ecs&logoColor=white)
![Fargate](https://img.shields.io/badge/Fargate-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white)

**Infrastructure as Code & CI/CD**

![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

**Networking & Delivery**

![NGINX](https://img.shields.io/badge/NGINX-009639?style=for-the-badge&logo=nginx&logoColor=white)
![ALB](https://img.shields.io/badge/ALB-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white)

**Observability**

![CloudWatch](https://img.shields.io/badge/CloudWatch-FF4F8B?style=for-the-badge&logo=amazon-cloudwatch&logoColor=white)

**Languages & Runtime**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)

</div>

<br>

## Production Projects

<table>
<tr>
<td width="50%" valign="top">

### Highly Available Web Infrastructure on AWS
**Stack:** Terraform · EC2 · ALB · Auto Scaling · VPC

Multi-AZ architecture provisioned entirely through Infrastructure as Code, with load-balanced traffic distribution, health-check-driven auto scaling, and network segmentation across public and private subnets.

`Terraform` `AWS` `High Availability` `IaC`

[View Repository →](https://github.com/kumarthokala1902)

</td>
<td width="50%" valign="top">

### Kubernetes Deployment Pipeline
**Stack:** EKS · Docker · GitHub Actions · Helm

CI/CD pipeline that builds, tests, and deploys containerized services to EKS on every merge, with rollback triggers on failed health checks and environment-scoped configuration.

`Kubernetes` `CI/CD` `GitOps` `EKS`

[View Repository →](https://github.com/kumarthokala1902)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### Infrastructure Monitoring Stack
**Stack:** CloudWatch · Alerting

Centralized metrics pipeline with service-level dashboards and threshold-based alerting, built to surface degradation before it becomes an incident.

`Observability` `Monitoring` `Alerting`

[View Repository →](https://github.com/kumarthokala1902)

</td>
<td width="50%" valign="top">

### Serverless Automation Framework
**Stack:** AWS Lambda · Python · EventBridge · S3

Event-driven automation for operational tasks — scheduled maintenance, log rotation, and cost-anomaly reporting — running without persistent compute.

`Serverless` `Automation` `Python`

[View Repository →](https://github.com/kumarthokala1902)

</td>
</tr>
</table>

<br>

## Architecture Interests

- **Distributed Systems Design** — consistency models, partition tolerance, and failure isolation in multi-service architectures.
- **Multi-Region Disaster Recovery** — active-passive and active-active strategies for RTO/RPO-driven infrastructure.
- **Zero-Downtime Deployment Strategies** — blue-green and canary rollout patterns for stateful and stateless services.
- **Platform Engineering** — internal developer platforms that reduce cognitive load without hiding operational reality.
- **DevSecOps Integration** — shifting security scanning, secrets management, and policy enforcement into the CI/CD pipeline.

<br>

## Currently Building

A CI/CD pipeline that deploys a containerized service to Amazon EKS, provisions its supporting infrastructure through Terraform, and exposes cluster and application health through CloudWatch.

<br>

## Contact

<div align="center">

[![LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kumarreddythokala/)
[![Email](https://img.shields.io/badge/Send_an_Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:kumarreddythokala13@gmail.com)
[![GitHub](https://img.shields.io/badge/Follow_on_GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/kumarthokala1902)

</div>

<br>

<div align="center">

---

**Operations experience today. Infrastructure engineering by design.**

<sub>Last updated: automated via profile CI</sub>

</div>
