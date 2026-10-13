# Olamide Olalekan — Platform & DevSecOps Engineer

Platform engineer focused on Kubernetes, observability, 
infrastructure automation, and failure-aware cloud systems.

Background in embedded systems and mechatronics engineering —
which informs how I think about hardware constraints, 
failure modes, and system behavior under pressure.

---

## Engineering Focus

- Deployment safety and automated rollback behavior
- Observability across golden signals — latency, errors, traffic, saturation
- Secrets management and zero-trust pipeline security
- Infrastructure automation with Terraform and Ansible
- Embedded systems and hardware-software integration

---

## Current Work

Building a failure-aware Kubernetes platform with observability,
automated rollback behavior, and runtime recovery testing.

---

## Core Stack

**Cloud & Infrastructure**
AWS · GCP · Kubernetes · Docker · Terraform

**CI/CD & Automation**
GitLab CI · Ansible · Puppet · GitHub Actions

**Observability**
Prometheus · Grafana · ELK Stack

**Security**
HashiCorp Vault · DevSecOps Pipelines

**Embedded Systems**
Arduino · C · C++ · MATLAB · Proteus

---

## Connect

[LinkedIn](https://www.linkedin.com/in/olamide-olalekan-12138a265)
```

---








# Olamide Olalekan — Platform & DevSecOps Engineer

I build and break Kubernetes platforms, then write down what happened.

Mechatronics engineer (FUOYE, 2025) turned platform engineer. Embedded systems taught me to ask what a system does when a part fails, and I apply that to cloud infrastructure.

Lagos, Nigeria. Open to remote contracts.

---

## What I take on

- **Secure CI/CD:** image scanning, SBOMs, signing and admission policy for teams shipping containers
- **Kubernetes and GitOps setup:** Terraform, Argo CD, autoscaling and TLS on EKS or GKE
- **Reliability reviews:** failure testing, SLOs and runbooks

---

## Main projects

**[Atlas](https://github.com/velrite/atlas)** — Distributed job platform on GKE: capacity-aware scheduler, GitLab CI with keyless GCP auth, Argo CD, canary with automatic rollback, chaos experiments and SLOs. Single region. Includes a scheduler race condition I found by testing and fixed.

**[Enterprise Cloud Platform](https://github.com/velrite/enterprise-cloud-platform)** — Secure supply chain, Istio and observability on EKS, deployed onto a fork of Google's Bank of Anthos. A simulated bank environment, not a real one. Includes a NetworkPolicy that existed but wasn't enforced until I traced it to the CNI.

**[Production Platform on Kubernetes](https://github.com/velrite/Production-Platform-on-Kubernetes)** — Multi-environment EKS with Karpenter, GitOps, private-CA TLS and ExternalDNS. Terminated a node on purpose and timed the recovery.

**[Forge](https://github.com/velrite/forge)** — Internal developer platform on GKE Autopilot: Backstage, GitLab CI, Argo Rollouts canary with automatic abort, Kyverno admission. Its README lists what isn't built.

**Project 7: LLM inference on GKE** — signed images accepted and unsigned images rejected at admission, vLLM on CPU. GPU quota was blocked, and the repo documents that. *(add link)*

Every repo has a "limitations" section. I'd rather you read it from me than find it yourself.

---

## Earlier labs (local Minikube in Codespaces, not real cloud)

[Auto-Healing Kubernetes](https://github.com/velrite/Auto-Healing-Kubernetes-Platform) · [Terraform Kubernetes Platform](https://github.com/velrite/Terraform-Kubernetes-Platform) · [GitOps with Argo CD](https://github.com/velrite/gitops-argocd-platform) · [Dockerize-Everything](https://github.com/velrite/dockerize-everything)

---

## Tools I've actually used

**Cloud:** AWS (EKS) · GCP (GKE)
**Infrastructure:** Terraform · Helm · Docker
**Delivery:** GitLab CI · GitHub Actions · Argo CD · Argo Rollouts
**Security:** Trivy · Syft · Cosign · Kyverno · OPA/Conftest · Vault (dev mode)
**Observability:** Prometheus · Grafana · Loki · Tempo · OpenTelemetry
**Languages:** Python · Bash · C/C++ (embedded)
**Embedded:** Arduino · ESP32 — [94 documented hardware projects](https://github.com/velrite)

---

## Contact

velrite.tech@gmail.com · [LinkedIn](https://www.linkedin.com/in/olamide-olalekan-12138a265)
