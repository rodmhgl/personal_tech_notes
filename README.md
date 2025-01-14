# Personal Tech Notes

A collection of notes (some AI-generated) of talks I've watched, courses I've taken, labs I've done. It's a tech blog without the fancy formatting, organized thoughts, or regard for the reader. :blush:

## Completed Readings

[Archive](./ARCHIVE.md)

## To-Do Reading List

I always find more articles than I have time to read. This is an attempt to track them and schedule reading by week. All dates approximate and, if we're being realistic, optimistic.

## 01-13-25

- The Platform Engineering Book (gumroad PDF - no longer available standalone, but available as part of [Platform Engineering: From Beginning to End](https://thenjdevopsguy.gumroad.com/l/perealworld))
   - [X] Part 3: The "Implementation" (LAB) [Notes](./book_notes/Michael_Levan_-_The_Platform_Engineering_Book/3_the_implementation.md)

- [X] Review for possible purchase: [The Kubernetes Book: 2024 Edition](https://www.amazon.com/Kubernetes-Book-Version-November-2018-ebook/dp/B072TS9ZQZ/ref=sr_1_1?)

- [ ] Complete [GitOps at Scale](https://learning.codefresh.io/course/gitops-scale) course / certification.

- [ ] [Continuous Promotion on Kubernetes with GitOps (Kargo)](https://piotrminkowski.com/2025/01/14/continuous-promotion-on-kubernetes-with-gitops/)

- Kubestronaut Prep - KCSA
   - [ ] [KodeKloud KCSA](https://learn.kodekloud.com/courses/kubernetes-and-cloud-native-security-associate-kcsa)
      - [ ] Kubernetes Security Fundamentals
         - [X] Pod Security Standards & Pod Security Admissions
         - [X] Authentication
         - [ ] Authorization
         - [ ] RBAC
         - [ ] Secrets
         - [ ] Isolation and Segmentation - Namespace
         - [ ] Isolation and Segmentation - Resource Quotas and Limits
         - [ ] Isolation and Segmentation - Security Context
         - [ ] Audit
         - [ ] Network Policies
      - [ ] Kubernetes Threat Model
         - [ ] Kubernetes Trust Boundaries and Data Flow
         - [ ] Persistence
         - [ ] Denial of Service
         - [ ] Malicious Code Execution
         - [ ] Compromised Applications in Containers
         - [ ] Attacker on the Network
         - [ ] Access to Sensitive Data
         - [ ] Privilege Escalation
      - [ ] Platform Security
         - [ ] Supply Chain Security - Minimize Base Image Footprint
         - [ ] Supply Chain Security - Scan Images for Known Vulnerabilities
         - [ ] Image Repository Security
         - [ ] Observability - Overview
         - [ ] Observability - Falco Overview and Installation
         - [ ] Observability - Using Falco to Detect Threats
         - [ ] Service Mesh - Monolithics vs Microservices
         - [ ] Service Mesh
         - [ ] Service Mesh - Istio
         - [ ] Service Mesh - Security in Istio
         - [ ] Service Mesh - Isti Security Architecture
         - [ ] K8s PKI - Certificate Creation
         - [ ] K8s PKI - View Certificate Details
         - [ ] Connectivity - TLS Introduction
         - [ ] Connectivity - TLS Basics
         - [ ] Connectivity - TLS in Kubernetes
         - [ ] Connectivity - Mutual TLS
         - [ ] Admission Controllers
      - [ ] Compliance and Security Frameworks
         - [ ] Compliance Frameworks
         - [ ] Threat Modeling Frameworks
         - [ ] Supply Chain Compliance
         - [ ] Automation and Tooling

- Fabric AI
   - [ ] Review web interface feature of [Fabric](https://github.com/danielmiessler/fabric)

- Platform Engineering (Physical - O'Reilly - Fournier and Nowland)
   - [ ] Part 1: The What and Why of Platform Engineering (36)

- aks-platform-engineering
   - [ ] [aks-platform-engineering](https://github.com/Azure-Samples/aks-platform-engineering) (LAB)
      - [ ] [Crossplane or CAPZ?](https://github.com/Azure-Samples/aks-platform-engineering/blob/main/docs/capz-or-crossplane.md)
      - [ ] [Onboard New Dev Team](https://github.com/Azure-Samples/aks-platform-engineering/blob/main/docs/Onboard-New-Dev-Team.md) (LAB)
      - [ ] [Backstage](https://github.com/Azure-Samples/aks-platform-engineering/blob/main/docs/backstage.md) (LAB)
   - [ ] [Deploying AKS Clusters Using Cluster API provider for Azure (CAPZ) and Helm](https://www.youtube.com/watch?v=ondiKVYZ1W0)

## 01-20-25

- [ ] Terraform Patterns, Observed
   - [ ] [Part 1: Module Types](https://medium.com/devoops-discourse/terraform-observed-part-1-module-types-9dec5aa9dc9f)
   - [ ] [Part 2: Module Arrangement](https://medium.com/devoops-discourse/terraform-observed-part-2-module-arrangement-109d2cf517e1)
   - [ ] [Part 3: State Misconceptions and Pitfalls](https://medium.com/devoops-discourse/terraform-patterns-observed-part-3-state-misconceptions-pitfalls-e051ca1b7be9)
   - [ ] [Part 4: State Management](https://medium.com/devoops-discourse/terraform-patterns-observed-part-4-state-management-dccec970f554)
   - [ ] [Part 5: Logic in Terraform](https://medium.com/devoops-discourse/terraform-patterns-observed-part-5-logic-in-terraform-a0b1207b3a56)

- [ ] The 6 Pillars of Platform Engineering
   - [ ] [Part 1 — Security](https://thenewstack.io/the-6-pillars-of-platform-engineering-part-1-security/)
   - [ ] [Part 2 — CI/CD & VCS Pipeline](https://thenewstack.io/the-6-pillars-of-platform-engineering-part-2-ci-cd-vcs-pipeline/)
   - [ ] [Part 3 — Provisioning](https://thenewstack.io/the-pillars-of-platform-engineering-part-3-provisioning/)
   - [ ] [Part 4 — Connectivity](https://thenewstack.io/the-pillars-of-platform-engineering-part-4-connectivity/)
   - [ ] [Part 5 — Orchestration](https://thenewstack.io/the-pillars-of-platform-engineering-part-5-orchestration/)
   - [ ] [Part 6 — Observability](https://thenewstack.io/the-pillars-of-platform-engineering-part-6-observability/)

- [ ] Fundamentals of DevOps and Software Delivery
   - [ ] [An Introduction to DevOps and Software Delivery](https://new.gruntwork.io/fundamentals-of-devops/introduction-to-devops-and-software-delivery#how_to_deploy_your_app)
   - [ ] [How to Manage Your Infrastructure as Code](https://new.gruntwork.io/fundamentals-of-devops/how-to-manage-your-infrastructure-as-code#how_to_manage_your_infra_as_code)
   - [ ] [How to Deploy Your Apps](https://new.gruntwork.io/fundamentals-of-devops/deploying-apps-orchestration-vms-containers-serverless#how_to_deploy_many_apps)
   - [ ] [How to Version, Build, and Test Your Code](https://new.gruntwork.io/fundamentals-of-devops/testing-your-systems#how_to_version_build_test)
   - [ ] [How to Set Up Continuous Integration (CI) and Continuous Delivery (CD)](https://new.gruntwork.io/fundamentals-of-devops/setup-ci-cd#how_to_set_up_ci_cd)
   - [ ] [How to Work with Multiple Teams and Environments](https://new.gruntwork.io/fundamentals-of-devops/work-with-teams-and-environments#how_to_work_with_multiple_teams)
   - [ ] [How to Set Up Networking](https://new.gruntwork.io/fundamentals-of-devops/setup-networking-vpc-vpn-dns#how_to_set_up_networking)
   - [ ] [How to Secure Communication and Storage](https://new.gruntwork.io/fundamentals-of-devops/manage-authentication-authorization-secrets#how_to_manage_auth_and_secrets)
   - [ ] [How to Store Data](https://new.gruntwork.io/fundamentals-of-devops/store-data-sql-nosql-queues-warehouses-file-stores#how_to_store_data)
   - [ ] [How to Monitor Your Systems](https://new.gruntwork.io/fundamentals-of-devops/monitor-your-systems-metrics-logs-alerts-observability#how_to_monitor_your_systems)

- Platform Engineering (Physical - O'Reilly - Fournier and Nowland)
   - [ ] Part 2: Platform Engineering Practices (180)
      - [ ] Chapter 3: How and When to Get Started (17)
      - [ ] Chapter 4: Building Great Platform Teams (23)

## 01-27-25

- [ ] [CNCF Platform Engineer Maturity Model](https://tag-app-delivery.cncf.io/whitepapers/platform-eng-maturity-model/)

- Platform Engineering (Physical - O'Reilly - Fournier and Nowland)
   - [ ] Part 2: Platform Engineering Practices (180)
      - [ ] Chapter 5: Platform as a Product (33)
      - [ ] Chapter 6: Operating Platforms (22)

## 02-03-25

- Platform Engineering (Physical - O'Reilly - Fournier and Nowland)
   - [ ] Part 2: Platform Engineering Practices (180)
      - [ ] Chapter 7: Planning and Delivery (24)
      - [ ] Chapter 8: Rearchitecting Platforms (21)

## 02-10-25

- Platform Engineering (Physical - O'Reilly - Fournier and Nowland)
   - [ ] Part 2: Platform Engineering Practices (180)
      - [ ] Chapter 9: Migrations and Sunsetting of Platforms (19)
      - [ ] Chapter 10: Managing Stakeholder Relations (21)
   - [ ] Part 3: What Does Success Look Like? (48)
      - [ ] Chapter 11: Your Platforms are Aligned (12)
      - [ ] Chapter 12: Your Platforms are Trusted (13)
      - [ ] Chapter 13: Your Platforms Managed Complexity (13)
      - [ ] Chapter 14: Your Platforms are Loved (10)

## 02-17-25

- Platform Engineering (Physical - O'Reilly - Fournier and Nowland)
   - [ ] Part 3: What Does Success Look Like? (48)
      - [ ] Chapter 11: Your Platforms are Aligned (12)
      - [ ] Chapter 12: Your Platforms are Trusted (13)
      - [ ] Chapter 13: Your Platforms Managed Complexity (13)
      - [ ] Chapter 14: Your Platforms are Loved (10)

## 02-24-25
