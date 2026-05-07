# Mason Kim

**AI Security & Platform Governance Engineer** | Secure control planes, cloud/Kubernetes security, and adversarial abuse defense

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/junkukkim/)
[![Portfolio](https://img.shields.io/badge/Portfolio-FF5722?style=flat&logo=blogger&logoColor=white)](https://mason5052.github.io/mason-kim/)
[![CI](https://github.com/mason5052/commerce-abuse-defense/actions/workflows/ci.yml/badge.svg)](https://github.com/mason5052/commerce-abuse-defense/actions)

---

## What I Build

I build secure control planes for AI-enabled infrastructure: policy gateways, audit trails, cloud/Kubernetes security, and adversarial abuse defense.

- Published: [AI Security & Platform Governance](https://github.com/mason5052/ai-security-platform-governance) -- reference architecture for policy gateways, agent threat modeling, and production AI operations
- Currently building: [Commerce Abuse Defense](https://github.com/mason5052/commerce-abuse-defense) -- ML-based anomaly detection for bot scoring and WAF rule generation
- Contributing to: [PentAGI](https://github.com/vxcontrol/pentagi) -- contributor, not owner. Selected merged PRs across OAuth hardening, runtime reliability, Docker Compose health checks, and broad test coverage for core packages
- Contributing to: [Trivy](https://github.com/aquasecurity/trivy) (33.8K+ stars) -- container and IaC vulnerability scanner, test coverage contributions
- Contributing to: [Strix](https://github.com/usestrix/strix) (21.1K+ stars) -- AI pentesting agents, reconnaissance skill docs and bug triage

---

## Featured Projects

| Project | Description | Stack |
|---------|-------------|-------|
| [Commerce Abuse Defense](https://github.com/mason5052/commerce-abuse-defense) | Bot abuse detection and scoring tool with WAF rule generation. 6 detection rules, weighted scoring (0-100), auto-generates Cloudflare and AWS WAF rules. v0.2.1, 60 tests, CI. | Python, Shopify, Cloudflare, AWS WAF |
| [K8s Security Baseline](https://github.com/mason5052/k8s-security-baseline) | CIS Benchmark v1.8.0 audit automation with RBAC templates, network policies, and SOC 2 control mapping. | Bash, Python, Kubernetes |
| [AWS WAF Security Framework](https://github.com/mason5052/aws-waf-security-framework) | Production Terraform WAF modules for eCommerce. Bot Control, IP Reputation, Rate Limiting, Geo Blocking. Reduced bot traffic from 30%+ to under 3%. | Terraform, AWS WAF, CloudWatch |

---

## Research

Published attack chain analyses documenting real-world eCommerce attack patterns:

- **[001: Hidden Product Card-Testing on Shopify](https://github.com/mason5052/commerce-abuse-defense/blob/main/docs/attack-chains/001-hidden-product-card-testing.md)** -- How attackers discover $0 products via API enumeration and use them for card validation. MITRE ATT&CK T1595, T1190.
- **[002: App-Layer Bot Defense Bypass Patterns](https://github.com/mason5052/commerce-abuse-defense/blob/main/docs/attack-chains/002-app-layer-defense-bypass.md)** -- Why client-side bot mitigation is necessary but insufficient. 5 bypass techniques, multi-layer defense architecture.

Reference architecture for AI policy gateways, agent threat models, and production AI operations is published as a public-safe portfolio repository. The three core documents:

- **[Generic AI Policy Gateway Architecture](https://github.com/mason5052/ai-security-platform-governance/blob/main/Generic-AI-Policy-Gateway-Architecture.md)** -- a control-plane design that secures AI assistants and agents with deterministic policy checks, redaction, and audit logging.
- **[Agent Security Threat Model](https://github.com/mason5052/ai-security-platform-governance/blob/main/Agent-Security-Threat-Model.md)** -- six categories of risk for AI agents that act on tools, files, browsers, APIs, and infrastructure, with concrete control responses for each.
- **[AI Production Operations Playbook](https://github.com/mason5052/ai-security-platform-governance/blob/main/AI-Production-Operations-Playbook.md)** -- service health, fallback patterns, incident runbooks, and governance metrics for AI systems.

Repository: [github.com/mason5052/ai-security-platform-governance](https://github.com/mason5052/ai-security-platform-governance)

---

## Open Source Contributions

Active contributor to security-focused open-source projects. Listed as a contributor in PentAGI [v1.2.0 release](https://github.com/vxcontrol/pentagi/releases/tag/v1.2.0).

| Project | Stars | Contributions | Stack |
|---------|-------|---------------|-------|
| [PentAGI](https://github.com/vxcontrol/pentagi) | 15K+ | Contributor, not owner. Selected merged PRs include OAuth hardening ([#120](https://github.com/vxcontrol/pentagi/pull/120), [#125](https://github.com/vxcontrol/pentagi/pull/125), [#127](https://github.com/vxcontrol/pentagi/pull/127)), runtime and reliability fixes ([#150](https://github.com/vxcontrol/pentagi/pull/150), [#151](https://github.com/vxcontrol/pentagi/pull/151), [#152](https://github.com/vxcontrol/pentagi/pull/152), [#178](https://github.com/vxcontrol/pentagi/pull/178), [#179](https://github.com/vxcontrol/pentagi/pull/179)), CA private key cleanup ([#168](https://github.com/vxcontrol/pentagi/pull/168)), Docker Compose health checks ([#243](https://github.com/vxcontrol/pentagi/pull/243)), and test coverage across search tools, config, terminal, providers, graph/server context, schema validation, Langfuse, and Graphiti ([#153](https://github.com/vxcontrol/pentagi/pull/153), [#170](https://github.com/vxcontrol/pentagi/pull/170)-[#172](https://github.com/vxcontrol/pentagi/pull/172), [#189](https://github.com/vxcontrol/pentagi/pull/189), [#199](https://github.com/vxcontrol/pentagi/pull/199)-[#202](https://github.com/vxcontrol/pentagi/pull/202), [#213](https://github.com/vxcontrol/pentagi/pull/213)-[#214](https://github.com/vxcontrol/pentagi/pull/214), [#230](https://github.com/vxcontrol/pentagi/pull/230)-[#244](https://github.com/vxcontrol/pentagi/pull/244)). | Go, TypeScript, GraphQL |
| [Trivy](https://github.com/aquasecurity/trivy) | 33.8K+ | Container and IaC vulnerability scanner, test coverage contributions | Go |
| [Strix](https://github.com/usestrix/strix) | 21.1K+ | Reconnaissance skill docs, Discord badge fix, Windows compatibility, bug triage | Python, Docker, LLM |

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
