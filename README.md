<div align="center">

# Building Reliable, Scalable, and Secure Infrastructure

**Cloud Infrastructure &nbsp;•&nbsp; Platform Engineering &nbsp;•&nbsp; Site Reliability**

[![Profile Views](https://komarev.com/ghpvc/?username=YOUR_USERNAME&style=flat-square&color=0a0a0a&label=PROFILE+VIEWS)](https://github.com/YOUR_USERNAME)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/YOUR_LINKEDIN)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:YOUR_EMAIL@example.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=flat-square&logo=vercel&logoColor=white)](https://your-portfolio.dev)

</div>

<br>

## Introduction

I am an entry-level engineer working at Amazon, currently building toward a career in Cloud / DevOps / Platform Engineering. I do not have prior professional experience in infrastructure roles — my foundation is being built through self-directed, hands-on projects designed to mirror how production systems are actually run.

My focus areas are cloud infrastructure, deployment automation, and observability. Every project in this profile is built with production practices in mind: version-controlled, reproducible, monitored, and documented — the same standards I intend to bring into a DevOps role from day one.

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

![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)

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

[View Repository →](https://github.com/YOUR_USERNAME/REPO_NAME)

</td>
<td width="50%" valign="top">

### Kubernetes Deployment Pipeline
**Stack:** EKS · Docker · GitHub Actions · Helm

CI/CD pipeline that builds, tests, and deploys containerized services to EKS on every merge, with rollback triggers on failed health checks and environment-scoped configuration.

`Kubernetes` `CI/CD` `GitOps` `EKS`

[View Repository →](https://github.com/YOUR_USERNAME/REPO_NAME)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### Infrastructure Monitoring Stack
**Stack:** Prometheus · Grafana · CloudWatch · Alertmanager

Centralized metrics pipeline with service-level dashboards and threshold-based alerting, built to surface degradation before it becomes an incident.

`Observability` `Monitoring` `Alerting`

[View Repository →](https://github.com/YOUR_USERNAME/REPO_NAME)

</td>
<td width="50%" valign="top">

### Serverless Automation Framework
**Stack:** AWS Lambda · Python · EventBridge · S3

Event-driven automation for operational tasks — scheduled maintenance, log rotation, and cost-anomaly reporting — running without persistent compute.

`Serverless` `Automation` `Python`

[View Repository →](https://github.com/YOUR_USERNAME/REPO_NAME)

</td>
</tr>
</table>

<br>

## GitHub Metrics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=YOUR_USERNAME&show_icons=true&theme=dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&icon_color=58a6ff&text_color=c9d1d9" width="49%" />
<img src="https://github-readme-streak-stats.herokuapp.com/?user=YOUR_USERNAME&theme=dark&hide_border=true&background=0d1117&stroke=58a6ff&ring=58a6ff&fire=58a6ff&currStreakLabel=c9d1d9" width="49%" />

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_USERNAME&layout=compact&theme=dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9" width="49%" />

</div>

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=YOUR_USERNAME&theme=react-dark&hide_border=true&bg_color=0d1117&color=58a6ff&line=58a6ff&point=c9d1d9" width="98%" />

</div>

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=YOUR_USERNAME&theme=darkhub&no-frame=true&column=7&margin-w=8&margin-h=8" width="98%" />

</div>

<br>

## Certifications

<table>
<tr>
<td align="center" width="25%">

**In Progress**

AWS Certified Solutions Architect – Associate

</td>
<td align="center" width="25%">

**Planned**

Certified Kubernetes Administrator (CKA)

</td>
<td align="center" width="25%">

**Planned**

HashiCorp Certified: Terraform Associate

</td>
<td align="center" width="25%">

**Planned**

AWS Certified DevOps Engineer – Professional

</td>
</tr>
</table>

> Certifications listed reflect actual progress and planned study targets — not completed credentials unless stated otherwise.

<br>

## Architecture Interests

- **Distributed Systems Design** — consistency models, partition tolerance, and failure isolation in multi-service architectures.
- **Multi-Region Disaster Recovery** — active-passive and active-active strategies for RTO/RPO-driven infrastructure.
- **Zero-Downtime Deployment Strategies** — blue-green and canary rollout patterns for stateful and stateless services.
- **Platform Engineering** — internal developer platforms that reduce cognitive load without hiding operational reality.
- **DevSecOps Integration** — shifting security scanning, secrets management, and policy enforcement into the CI/CD pipeline.

<br>

## Currently Building

A CI/CD pipeline that deploys a containerized service to Amazon EKS, provisions its supporting infrastructure through Terraform, and exposes cluster and application health through a Prometheus and Grafana monitoring stack — built end-to-end as a single reproducible workflow rather than disconnected scripts.

<br>

## Contact

<div align="center">

[![LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/YOUR_LINKEDIN)
[![Email](https://img.shields.io/badge/Send_an_Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:YOUR_EMAIL@example.com)
[![GitHub](https://img.shields.io/badge/Follow_on_GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/YOUR_USERNAME)

</div>

<br>

<div align="center">

---

**Operations experience today. Infrastructure engineering by design.**

<sub>Last updated: automated via profile CI</sub>

</div>
