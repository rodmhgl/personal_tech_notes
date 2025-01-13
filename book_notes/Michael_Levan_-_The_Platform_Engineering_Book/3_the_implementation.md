# Michael Levan - The Platform Engineering Book - Part 3: The Implementation

## Building the stack

The CNCF Platform Maturity Model specifies two key outcomes of a platform team:

"Platforms curate and present common capabilities, frameworks, and experiences"

"The focus is on platforms that facilitate and accelerate the work of internal users such as product and application
teams."

## The Underlying Platform

The Underlying Platform is the core where everything runs - all of the tooling, automation, applications, and various other components that make the platform come to life.

When choosing the underlying platform:

- Do the Platform Engineers know and understand it?
- Is it the platform the consumers need?

## The Platform Capabilities

Meet with the teams consuming the platform to determine which capabilities are needed. Monitoring? Observability? SDK Access? Crossplane? Messaging? GitOps? Understand the capability needed and the tool will reveal itself.

Regardless of the capabilities, your job as a Platform Engineer is to make the capability a developer/engineer needs to use more efficient, easier, and straightforward. You implement the automation and practices to get this done while they use the finished product.

## Interacting with the Platform

How will teams interact with the platform? CLI? API? UI?

In a perfect world, all three would be preferred.

## Building the Underlying Platform

Book covers deploying managed k8s (AKS / EKS) with Terraform and GitHub Actions and bare-metal or VM deployments with `kubeadm`.

As stated numerous times throughout the book, each of the sections mentioned below could really be books unto themselves.

### Security

#### Security Best Practices

[OWASP Top 10](https://owasp.org/www-project-kubernetes-top-ten/)
[CIS Kubernetes Benchmark](https://www.cisecurity.org/benchmark/kubernetes)

#### Policy Enforcement

Covers installing OPA/Gatekeeper for policy enforcement and creating a policy to block images with the `latest` tag.

#### Authentication and Authorization

- How are the users/team logging into the cluster (authentication)
- What permissions will the users/team have on the cluster (authorization)

The book covers setting up the out-of-the-box RBAC API resource while acknowledging that most people use a third-party OpenID Connect (OIDC) solution such as Entra ID, AWS IAM, or Keycloak.

Setups using Entra ID (called Azure Active Directory at the time of writing) and Keycloak are also covered.

#### Monitoring and Observability

Two primary options:

- Homegrown with an open-source stack
   - Usually comprised of open-source tools of a monitoring/observability tool you build in-house
- Enterprise
   - Usually a paid option such as `Datadog` or `AppDynamics`

One popular stack is `Grafana` (visualization), `Prometheus` (metrics), `Loki` (log aggregator), and `Tempo` (tracing). The book covers setting up this stack along with Datadog.

## Platform Interface and Capabilities

An overview of various methods of interacting with the platform are discussed, such as `Backstage`, `Crossplane`, `Radius`, and `Port`.

### Backstage

Web-based internal developer portal. Uses Typescript for all operations. The book covers setting up Backstage, plugins, and creating your own plugin.

### Radius

Radius is an open-source tool created by Microsoft that works on Azure and AWS. Recipes (plugins) are created by Platform Engineers and provided to the platform users. The book covers using Radius CLI with an AKS cluster.

### Port

Port is a paid GUI-based IDP that allows you to provide self-service pipelines to your users. The book covers deploying a simple pre-made pipeline with Port.

### Crossplane

Crossplane allows you to use Kubernetes manifests to deploy resources outside of Kubernetes. The book covers deploying Crossplane and using it to create a Virtual Network in Azure.

## Cognitive Load Reduction

### CNOE (Canoe)

CNOE is an app stack that reduces the complexities of Platform Engineering by providing an app stack from tools based on maturity, user experience, user engagement, and adoption. This ready-made stack reduces complexity and cognitive load.

Stack includes:

- ArgoCD
- Crossplane
- Backstage
- Nginx Ingress

## Wrapping Up

Platform Engineering is about putting the human back into technology.

Platform Engineering is the implementation of customer service into existing engineering practices. Instead of building out a system or implementing a tool to automate a process for yourself, youre implementing a system thatll be automated by you, but youll also implement said automation practices for the engineers/developers using it.

When implementing Platform Engineering, underlying platform and platform capabilities should be the last thing on your
mind. The first thing you should be asking is “What do the engineers/developers need that will be using this platform?

## Resources

- [Part 1: The Why](./1_the_why.md)
- [Part 2: The Planning](./2_the_planning.md)
