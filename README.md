# Mason Kim

**Security Engineer** | Platform security, cloud defense automation, and security-focused open source

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/junkukkim/)
[![Portfolio](https://img.shields.io/badge/Portfolio-FF5722?style=flat&logo=blogger&logoColor=white)](https://mason5052.github.io/mason-kim/)

---

## What I Work On

Public work I can explain deeply: Kubernetes hardening, WAF automation, and security-focused contributions to open-source security tooling.

- Public project: [K8s Security Baseline](https://github.com/mason5052/k8s-security-baseline) -- CIS benchmark audit automation, RBAC templates, network policies, and SOC 2-aligned reporting
- Public project: [AWS WAF Security Framework](https://github.com/mason5052/aws-waf-security-framework) -- Terraform modules for AWS WAF v2 with bot protection, rate limiting, and eCommerce-focused rules
- Open-source contributor: [PentAGI](https://github.com/vxcontrol/pentagi) -- merged PRs across OAuth hardening, runtime reliability, test coverage, observability, and Docker Compose infrastructure
- Open-source contributor: [Trivy](https://github.com/aquasecurity/trivy) -- test coverage contributions for container and IaC security scanning
- Open-source contributor: [Strix](https://github.com/usestrix/strix) -- documentation fixes and bug triage for AI pentesting agents

---

## Featured Work

| Project | Description | Stack |
|---------|-------------|-------|
| [PentAGI](https://github.com/vxcontrol/pentagi) | Contributor, not owner. Selected merged PRs across OAuth hardening, runtime reliability, Docker Compose health checks, and broad test coverage for core packages. | Go, TypeScript, GraphQL |
| [K8s Security Baseline](https://github.com/mason5052/k8s-security-baseline) | CIS Benchmark v1.8.0 audit automation with RBAC templates, network policies, and SOC 2 control mapping. | Bash, Python, Kubernetes |
| [AWS WAF Security Framework](https://github.com/mason5052/aws-waf-security-framework) | Terraform modules for AWS WAF v2 with bot protection, rate limiting, IP reputation, and geo controls. | Terraform, AWS WAF, CloudWatch |
| [mason-kim](https://github.com/mason5052/mason-kim) | Portfolio site and writing hub for public projects, credentials, and contact information. | HTML, GitHub Pages |

---

## Open Source Contributions

I use GitHub to show public projects I can defend in detail and merged upstream work that has third-party validation.

| Project | Contribution Focus | Stack |
|---------|--------------------|-------|
| [PentAGI](https://github.com/vxcontrol/pentagi) | Contributor, not owner. Selected merged PRs include OAuth hardening ([#120](https://github.com/vxcontrol/pentagi/pull/120), [#125](https://github.com/vxcontrol/pentagi/pull/125), [#127](https://github.com/vxcontrol/pentagi/pull/127)), runtime and reliability fixes ([#150](https://github.com/vxcontrol/pentagi/pull/150), [#151](https://github.com/vxcontrol/pentagi/pull/151), [#152](https://github.com/vxcontrol/pentagi/pull/152), [#178](https://github.com/vxcontrol/pentagi/pull/178), [#179](https://github.com/vxcontrol/pentagi/pull/179)), CA private key cleanup ([#168](https://github.com/vxcontrol/pentagi/pull/168)), Docker Compose health checks ([#243](https://github.com/vxcontrol/pentagi/pull/243)), and test coverage across search tools, config, terminal, providers, graph/server context, schema validation, Langfuse, and Graphiti ([#153](https://github.com/vxcontrol/pentagi/pull/153), [#170](https://github.com/vxcontrol/pentagi/pull/170)-[#172](https://github.com/vxcontrol/pentagi/pull/172), [#189](https://github.com/vxcontrol/pentagi/pull/189), [#199](https://github.com/vxcontrol/pentagi/pull/199)-[#202](https://github.com/vxcontrol/pentagi/pull/202), [#213](https://github.com/vxcontrol/pentagi/pull/213)-[#214](https://github.com/vxcontrol/pentagi/pull/214), [#230](https://github.com/vxcontrol/pentagi/pull/230)-[#244](https://github.com/vxcontrol/pentagi/pull/244)). | Go, TypeScript, GraphQL |
| [Trivy](https://github.com/aquasecurity/trivy) | Test coverage contributions for vulnerability and IaC scanning packages. | Go |
| [Strix](https://github.com/usestrix/strix) | Documentation fixes and bug triage for AI pentesting agents. | Python, Docker, LLM |

### PentAGI Highlights

- Security and auth hardening: OAuth GET callback state enforcement ([#120](https://github.com/vxcontrol/pentagi/pull/120)), required field validation in OAuth state parsing ([#125](https://github.com/vxcontrol/pentagi/pull/125)), missing return fix in OAuth callback redirect ([#127](https://github.com/vxcontrol/pentagi/pull/127)), and CA private key cleanup after certificate signing ([#168](https://github.com/vxcontrol/pentagi/pull/168)).
- Runtime and reliability: browser tool graceful degradation on screenshot failure ([#150](https://github.com/vxcontrol/pentagi/pull/150)), `http.DefaultClient` mutation guard in search tools ([#151](https://github.com/vxcontrol/pentagi/pull/151)), error propagation in `GetTool` container lookup ([#152](https://github.com/vxcontrol/pentagi/pull/152)), repeating tool-call infinite loop fix ([#178](https://github.com/vxcontrol/pentagi/pull/178)), detached command context isolation ([#179](https://github.com/vxcontrol/pentagi/pull/179)), and pgvector Docker Compose health checks ([#243](https://github.com/vxcontrol/pentagi/pull/243)).
- Test coverage and maintainability: search tools ([#153](https://github.com/vxcontrol/pentagi/pull/153)), executor helpers and terminal utilities ([#172](https://github.com/vxcontrol/pentagi/pull/172)), provider coverage ([#189](https://github.com/vxcontrol/pentagi/pull/189)), config and terminal packages ([#199](https://github.com/vxcontrol/pentagi/pull/199)-[#200](https://github.com/vxcontrol/pentagi/pull/200)), response and embeddings packages ([#201](https://github.com/vxcontrol/pentagi/pull/201)-[#202](https://github.com/vxcontrol/pentagi/pull/202)), graph and server context helpers ([#213](https://github.com/vxcontrol/pentagi/pull/213)-[#214](https://github.com/vxcontrol/pentagi/pull/214)), server models and schema validation ([#230](https://github.com/vxcontrol/pentagi/pull/230)-[#231](https://github.com/vxcontrol/pentagi/pull/231)), Langfuse coverage ([#241](https://github.com/vxcontrol/pentagi/pull/241)-[#242](https://github.com/vxcontrol/pentagi/pull/242)), and Graphiti client coverage ([#244](https://github.com/vxcontrol/pentagi/pull/244)).

---

## Certifications

| Certification | Issuer | Valid |
|---------------|--------|-------|
| Certified Ethical Hacker (CEH) | EC-Council | 2025-2028 |
| Terraform Associate (004) | HashiCorp | Current |
| CASE Java (Application Security) | EC-Council | 2024-2027 |

## Education

| Degree | Institution | Status |
|--------|-------------|--------|
| MS Cybersecurity | Georgia Institute of Technology | Expected 2026 |

---

## Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat&logo=terraform&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazon-aws&logoColor=white)
![AWS WAF](https://img.shields.io/badge/AWS_WAF-FF9900?style=flat&logo=amazon-aws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat&logo=gnu-bash&logoColor=white)
![Trivy](https://img.shields.io/badge/Trivy-1904DA?style=flat&logo=aqua&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat&logo=grafana&logoColor=white)
