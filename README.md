# Mason Kim

**Security Engineer** | Platform security, adversarial defense, and attack chain research

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/junkukkim/)
[![Portfolio](https://img.shields.io/badge/Portfolio-FF5722?style=flat&logo=blogger&logoColor=white)](https://mason5052.github.io/mason-kim/)
[![CI](https://github.com/mason5052/commerce-abuse-defense/actions/workflows/ci.yml/badge.svg)](https://github.com/mason5052/commerce-abuse-defense/actions)

---

## What I Build

Security tools and AIOps infrastructure for real operational environments. I build detection systems, AI-powered monitoring pipelines, and WAF automation -- solving real problems with open-source code.

- Currently building: [Argus-Ops](https://github.com/mason5052/argus-ops) -- AI-powered K8s monitoring CLI with full detect -> diagnose -> fix pipeline
- Currently building: [Commerce Abuse Defense](https://github.com/mason5052/commerce-abuse-defense) -- ML-based anomaly detection for bot scoring
- Contributing to: [OWASP Nettacker](https://github.com/OWASP/Nettacker) (4.8K+ stars) -- automated pentesting framework, CVE detection modules and framework improvements
- Contributing to: [PentAGI](https://github.com/vxcontrol/pentagi) (8.3K+ stars) -- autonomous AI pentesting, security hardening and reliability (9 merged commits in v1.2.0)
- Contributing to: [Strix](https://github.com/usestrix/strix) (20K+ stars) -- AI pentesting agents, reconnaissance skill docs and bug triage

---

## Featured Projects

| Project | Description | Stack |
|---------|-------------|-------|
| [Argus-Ops](https://github.com/mason5052/argus-ops) | AI-powered infrastructure monitoring CLI. Full AIOps loop: detect -> AI diagnose -> propose fix -> approve -> execute -> verify. Pluggable LLM via LiteLLM (OpenAI, Anthropic, Ollama, 100+ providers). v0.1.0, 51 tests, CI. | Python, Kubernetes, LiteLLM, Click |
| [Commerce Abuse Defense](https://github.com/mason5052/commerce-abuse-defense) | Bot abuse detection and scoring tool with WAF rule generation. 6 detection rules, weighted scoring (0-100), auto-generates Cloudflare and AWS WAF rules. v0.2.1, 60 tests, CI. | Python, Shopify, Cloudflare, AWS WAF |
| [K8s Security Baseline](https://github.com/mason5052/k8s-security-baseline) | CIS Benchmark v1.8.0 audit automation with RBAC templates, network policies, and SOC 2 control mapping. | Bash, Python, Kubernetes |
| [AWS WAF Security Framework](https://github.com/mason5052/aws-waf-security-framework) | Production Terraform WAF modules for eCommerce. Bot Control, IP Reputation, Rate Limiting, Geo Blocking. Reduced bot traffic from 30%+ to under 3%. | Terraform, AWS WAF, CloudWatch |

---

## Research

Published attack chain analyses documenting real-world eCommerce attack patterns:

- **[001: Hidden Product Card-Testing on Shopify](https://github.com/mason5052/commerce-abuse-defense/blob/main/docs/attack-chains/001-hidden-product-card-testing.md)** -- How attackers discover $0 products via API enumeration and use them for card validation. MITRE ATT&CK T1595, T1190.
- **[002: App-Layer Bot Defense Bypass Patterns](https://github.com/mason5052/commerce-abuse-defense/blob/main/docs/attack-chains/002-app-layer-defense-bypass.md)** -- Why client-side bot mitigation is necessary but insufficient. 5 bypass techniques, multi-layer defense architecture.

---

## Open Source Contributions

Active contributor to security-focused open-source projects. Listed as a contributor in PentAGI [v1.2.0 release](https://github.com/vxcontrol/pentagi/releases/tag/v1.2.0).

| Project | Stars | Contributions | Stack |
|---------|-------|---------------|-------|
| [OWASP Nettacker](https://github.com/OWASP/Nettacker) | 4.8K+ | CISA KEV CVE detection modules, YAML module schema fixes, framework improvements | Python, YAML, Poetry |
| [PentAGI](https://github.com/vxcontrol/pentagi) | 8.3K+ | 9 merged commits: OAuth CSRF fix ([#120](https://github.com/vxcontrol/pentagi/pull/120)), resource leak prevention, TLS/CA cert hardening, browser tool reliability ([#150](https://github.com/vxcontrol/pentagi/pull/150)), Swagger/docs fixes | Go, TypeScript, GraphQL |
| [Strix](https://github.com/usestrix/strix) | 20K+ | Reconnaissance skill docs, Discord badge fix, Windows compatibility, bug triage | Python, Docker, LLM |

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
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat&logo=terraform&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazon-aws&logoColor=white)
![AWS WAF](https://img.shields.io/badge/AWS_WAF-FF9900?style=flat&logo=amazon-aws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat&logo=gnu-bash&logoColor=white)
![Trivy](https://img.shields.io/badge/Trivy-1904DA?style=flat&logo=aqua&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat&logo=grafana&logoColor=white)

