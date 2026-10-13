VELRITE | Platform Engineering · Cloud Infrastructure · DevSecOps

Building infrastructure that holds under failure.

I build cloud-native platforms designed to be automated, observable, secure, and resilient under failure.

My work focuses on Kubernetes, cloud infrastructure, GitOps, secure software delivery, and reliability engineering. Through Atlas, Forge, and the Velrite Enterprise Cloud Platform, I investigate the engineering problems that matter beyond a successful deployment: capacity management, identity and access control, deployment safety, policy enforcement, recovery behaviour, and operational visibility.

I believe infrastructure should be judged by how it behaves when something goes wrong — not just by whether it works when everything goes right.

"Portfolio" (https://velrite.com) · "GitHub" (https://github.com/velrite) · "LinkedIn" (https://www.linkedin.com/in/olamide-olalekan-12138a265) · "Contact" (mailto:velrite.tech@gmail.com)

---

ENGINEERING AT A GLANCE

- Cloud platforms: AWS, Google Cloud, Amazon EKS, Google GKE
- Infrastructure as code: Terraform, Helm, Docker
- Platform delivery: Kubernetes, Argo CD, Argo Rollouts, GitLab CI/CD, GitHub Actions
- Cloud-native security: Workload Identity Federation, image scanning, SBOMs, image signing, admission policies
- Reliability & observability: Prometheus, Grafana, OpenTelemetry, SLOs, controlled failure testing
- Automation: Python, Bash, CI/CD pipelines, policy-as-code

SELECTED ENGINEERING PROJECTS

01 — Atlas

Distributed Workload Platform · Google Cloud / GKE

"Explore Atlas →" (https://github.com/velrite/atlas)

A Kubernetes-based workload platform built to explore capacity-aware scheduling, automated delivery, and distributed-system resilience.

- Implemented capacity-aware scheduling and corrected a capacity-reservation race discovered during testing.
- Built a GitOps delivery workflow with Argo CD and progressive delivery with automated rollback.
- Implemented keyless CI/CD authentication to Google Cloud using workload identity federation.
- Tested configuration-drift recovery, with GitOps reconciliation completing in under three seconds in the documented test.
- Developed observability, SLOs, controlled failure experiments, and multi-region resilience scenarios.

Engineering focus: Scheduling correctness, deployment safety, identity security, and measurable recovery.

02 — Forge

Internal Developer Platform · Google Cloud / GKE Autopilot

"Explore Forge →" (https://github.com/velrite/forge)

An internal developer platform exploring safer application delivery and self-service workflows.

- Integrated Backstage, GitLab CI/CD, Argo CD, and Argo Rollouts.
- Implemented canary delivery with an automated abort when the rollout failed its configured checks.
- Applied Kyverno admission policies to enforce selected workload and supply-chain requirements.
- Used workload identity federation to avoid storing long-lived Google Cloud credentials in the delivery pipeline.
- Documented implementation gaps and components that remain unverified.

Engineering focus: Developer experience, delivery guardrails, policy enforcement, and automation.

03 — Velrite Enterprise Cloud Platform

Cloud-Native Security & Observability · AWS / EKS

"Explore the platform →" (https://github.com/velrite/enterprise-cloud-platform)

An independently built cloud platform using a bank-themed demonstration application to investigate secure delivery and operational controls.

- Implemented infrastructure provisioning and Kubernetes deployment on Amazon EKS.
- Integrated supply-chain controls including vulnerability scanning, SBOM generation, image signing, and policy checks.
- Used Argo CD and Argo Rollouts to explore GitOps delivery and rollback behaviour.
- Integrated observability tooling across metrics, logs, traces, and alerting.
- Investigated real configuration and enforcement issues, documenting security boundaries, incidents, and technical debt.

Engineering focus: Secure delivery, cloud-native controls, observability, and operational investigation.

04 — Auto-Healing Kubernetes Platform

Recovery, Autoscaling & Operations

"Explore the project →" (https://github.com/velrite/Auto-Healing-Kubernetes-Platform)

A Kubernetes lab built to test recovery and operational behaviour through controlled failure scenarios.

- Observed recovery after a worker-node failure, with approximately 20-second recovery in the documented test.
- Tested automated rollback after a bad-image deployment, with approximately 32-second rollback in the documented test.
- Exercised horizontal pod autoscaling and secret rotation.
- Built monitoring and alerting workflows while documenting gaps in application-level metrics.

Engineering focus: Failure recovery, workload health, autoscaling, and operational visibility.

ENGINEERING PRINCIPLES

Automate repeatable operations. Prefer reproducible infrastructure and declarative delivery over undocumented manual changes.

Test failure deliberately. Use controlled experiments to examine recovery, deployment behaviour, and system boundaries.

Secure the delivery path. Treat identity, artifacts, dependencies, and admission controls as parts of the platform.

Measure before making claims. Distinguish configured components from behaviour verified through testing.

Document the limitations. Every serious engineering project has boundaries. I make them explicit rather than presenting a lab as a production system.

BACKGROUND

Mechatronics Engineering graduate from the Federal University Oye-Ekiti, 2025. My background encourages a systems-oriented approach to software infrastructure: understand dependencies, identify failure modes, test assumptions, and validate behaviour.

I am focused on Platform Engineering, Cloud Infrastructure, DevOps, and DevSecOps opportunities where automation, reliability, and engineering discipline matter.

---

LET'S CONNECT

"Website" (https://velrite.com) · "GitHub Projects" (https://github.com/velrite?tab=repositories) · "LinkedIn" (https://www.linkedin.com/in/olamide-olalekan-12138a265) · "Email Velrite" (mailto:velrite.tech@gmail.com)

VELRITE — Building infrastructure that holds under failure.
