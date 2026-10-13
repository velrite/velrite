# Olamide Olalekan — Platform & DevSecOps Engineer

I build and break Kubernetes platforms, then write down what happened.

Mechatronics engineer (FUOYE, 2025) turned platform engineer. Embedded systems taught me to ask what a system does when a part fails, and I apply that to cloud infrastructure.

📍 Lagos, Nigeria (WAT) · Open to remote contracts and full-time roles

---

## What I help with

- **Secure CI/CD:** image scanning, SBOMs, signing and admission policy
- **Kubernetes + GitOps:** Terraform, Argo CD, autoscaling and TLS on EKS or GKE
- **Reliability reviews:** failure testing, SLOs and runbooks

---

## Main projects

**[Atlas](https://github.com/velrite/atlas)** — Distributed job platform on GKE with a capacity-aware scheduler, canary deploys with automatic rollback, chaos experiments and SLOs. *[One measured result here.]* Includes a scheduler race condition I found by testing and fixed.

**[Enterprise Cloud Platform](https://github.com/velrite/enterprise-cloud-platform)** — Secure supply chain, Istio and observability on EKS, deployed onto a fork of Bank of Anthos. *[One measured result here.]* Includes a NetworkPolicy that existed but wasn't enforced until I traced it to the CNI.

**[Production Platform on Kubernetes](https://github.com/velrite/Production-Platform-on-Kubernetes)** — Multi-environment EKS with Karpenter, GitOps, private-CA TLS and ExternalDNS. I terminated a node on purpose and timed the recovery.

Also: [Forge](https://github.com/velrite/forge) (internal developer platform on GKE) · [LLM inference on GKE](ADD-LINK) (signed-image admission, vLLM)

Every repo has a "limitations" section. I'd rather you read it from me than find it yourself.

---

## Tools I've actually used

**Cloud:** AWS (EKS) · GCP (GKE)
**Infrastructure:** Terraform · Helm · Docker
**Delivery:** GitLab CI · GitHub Actions · Argo CD · Argo Rollouts
**Security:** Trivy · Syft · Cosign · Kyverno · OPA/Conftest · Vault
**Observability:** Prometheus · Grafana · Loki · Tempo · OpenTelemetry
**Languages:** Python · Bash · C/C++
**Embedded:** Arduino · ESP32

---

## Contact

velrite.tech@gmail.com · [LinkedIn](https://www.linkedin.com/in/olamide-olalekan-12138a265)
