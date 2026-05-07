# Aurélien Kumarathas

## DevSecOps & Cloud Security Engineer — AWS · Terraform · Kubernetes · GitHub Actions

I help teams ship faster **without** shipping vulnerabilities — by building security into IaC, CI/CD pipelines, and Kubernetes from day one.

Recent focus areas:
- **Secure-by-default Terraform** — hardened AWS modules, policy-as-code with OPA/Rego, SARIF reporting
- **Multi-tool DevSecOps pipelines** — SAST, SCA, secrets detection, IaC and container scanning in GitHub Actions
- **Kubernetes hardening** — OPA Gatekeeper constraints, network policies, runtime detection, CIS compliance
- **Threat modelling** — STRIDE, DREAD, MITRE ATT&CK for regulated (healthcare/fintech) workloads

Based in **London, UK** — open to hybrid or remote-first roles.

---

### 🎯 Roles I'm Targeting

DevSecOps Engineer · Cloud Security Engineer · Security Engineer (Platform/Cloud)

---

### 📂 Featured Projects

| Project | What I built | Impact | Stack |
|---------|-------------|--------|-------|
| [**Terraform AWS Security Hardening**](https://github.com/AurelienKumarathas/terraform-security-project) | Hardened AWS stack (VPC, EC2, RDS, S3, KMS) with Checkov, tfsec & OPA wired into GitHub Actions. SARIF uploads feed the GitHub Security tab at PR level. Full SOC 2 control mapping and findings register included. | **19 Checkov + 19 tfsec findings → 0 on main.** All Critical/High remediated. | Terraform · Checkov · tfsec · OPA/Rego · GitHub Actions · AWS |
| [**DevSecOps Pipeline**](https://github.com/AurelienKumarathas/devsecops-pipeline-project-1) | Two-branch pipeline: `main` holds intentionally vulnerable code to prove every gate catches real issues; `hardened` branch is fully remediated. Open PR with before/after diffs, CVSS scores and MITRE ATT&CK mappings for every finding. | **7 vulnerability classes eliminated** — SQLi, SSTI, CMDi, path traversal, YAML injection, hardcoded creds, root container. | GitHub Actions · CodeQL · Bandit · Trivy · Gitleaks · Docker |
| [**Kubernetes Security Portfolio**](https://github.com/AurelienKumarathas/k8s-security-portfolio) | Hardened a 3-node GKE cluster end-to-end: OPA Gatekeeper constraints (no root/privileged pods, required resource limits), namespace network policies, Trivy image scanning, RBAC audit, custom Falco rules. | **CIS non-compliance: 38% → 6%** | GKE · Kubernetes · OPA Gatekeeper · Falco · Trivy · Helm |
| [**Healthcare Threat Model**](https://github.com/AurelienKumarathas/complete-threat-model-for-healthcare-application) | Full threat model for a fictional NHS-style cloud platform on AWS. 31 threats across STRIDE categories, all DREAD-scored and placed in a risk register. ATT&CK Navigator layer JSON included. APT attack simulation timeline written to show where controls break real kill chains. | **31 threats identified**, mapped to MITRE ATT&CK, NIST CSF, NHS DSPT & UK GDPR. | STRIDE · DREAD · MITRE ATT&CK · NIST CSF · AWS |

---

### 🚀 Pipeline Status

![IaC Security Pipeline](https://github.com/AurelienKumarathas/terraform-security-project/actions/workflows/iac-security.yml/badge.svg)
![DevSecOps Pipeline](https://github.com/AurelienKumarathas/devsecops-pipeline-project-1/actions/workflows/devsecops-pipeline.yml/badge.svg)

---

### 🛠️ Core Skills

**DevSecOps & CI/CD**

![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![CodeQL](https://img.shields.io/badge/-CodeQL-brightgreen?style=flat-square)
![Trivy](https://img.shields.io/badge/-Trivy-1904DA?style=flat-square)
![Gitleaks](https://img.shields.io/badge/-Gitleaks-red?style=flat-square)

**Cloud & IaC**

![AWS](https://img.shields.io/badge/-AWS-FF9900?style=flat-square&logo=amazon-aws&logoColor=white)
![Terraform](https://img.shields.io/badge/-Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Checkov](https://img.shields.io/badge/-Checkov-brightgreen?style=flat-square)
![OPA](https://img.shields.io/badge/-OPA%2FRego-7D3C98?style=flat-square)

**Containers & Kubernetes**

![Kubernetes](https://img.shields.io/badge/-Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Falco](https://img.shields.io/badge/-Falco-00AEC7?style=flat-square)

**Languages**

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/-Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![HCL](https://img.shields.io/badge/-HCL-7B42BC?style=flat-square)

---

### 📜 Certifications

- HashiCorp **Terraform Associate 003** (2025)
- AWS Certified **Cloud Practitioner** (2025)
- **GitHub Actions** Certification (2025)
- Google **Cybersecurity Professional Certificate** (2024)
- BCS **Information Security Management Principles** (2024)
- SailPoint Certified **IdentityNow Associate** (2024)

---

### 📫 Let's Connect

- 💼 [LinkedIn](https://www.linkedin.com/in/aurelienkumarathas)
- 📧 [Email](mailto:akumarathas27@gmail.com)

> Actively seeking DevSecOps / Cloud Security Engineer roles. Happy to walk you through any of the projects above — just reach out.
