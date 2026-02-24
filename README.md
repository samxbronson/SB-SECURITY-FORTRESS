# SB-SECURITY-FORTRESS
## Mission

Build and document a business-grade IT and security infrastructure in a VMware Workstation homelab environment. Develop analyst skills across infrastructure, GRC, and SOC disciplines. Every build decision, configuration, and finding is documented as if it were a client deliverable — supporting the development of a solo security consulting practice.

## Repo Structure

```
/
├── README.md                     ← This file
├── index.html                    ← Project roadmap webpage
├── docs/
│   ├── phase1-infrastructure/    ← All Phase 1 docs (network, systems, VMs)
│   ├── phase2-iam/               ← All Phase 2 docs (OU, GPO, RBAC)
│   ├── phase3-detection/         ← All Phase 3 docs (SIEM, rules, logs)
│   ├── phase4-risk/              ← All Phase 4 docs (vuln scans, risk register)
│   ├── phase5-hardening/         ← All Phase 5 docs (remediation, baselines)
│   └── grc/                      ← Cross-cutting: policies, compliance mappings
├── playbooks/                    ← IR procedures, SOC runbooks
├── scripts/                      ← PowerShell, automation
└── assets/                       ← Diagrams, screenshots
```

---

## Mock Enterprise — Hargrove Financial Group

> This lab simulates the IT environment of a real business. Every infrastructure decision, security finding, and remediation is made in the context of this organization.

**Hargrove Financial Group** is a 45-person regional accounting and financial advisory firm operating out of a single office location. Hargrove serves small-to-mid size business clients across bookkeeping, tax preparation, payroll processing, and financial consulting.

Because they process client payment data and manage sensitive financial records, they operate under **PCI-DSS** requirements for card handling and are working toward **SOC 2 Type II** compliance to satisfy enterprise client contracts.

| Detail | Value |
|--------|-------|
| Industry | Financial Services / Accounting |
| Headcount | 45 employees |
| Location | Single site, on-premise infrastructure |
| Compliance scope | PCI-DSS, SOC 2 Type II (in progress) |
| Security team | None — IT handles security responsibilities |

**Departments:** IT (3 staff), Finance & Accounting, Client Services, HR, Executive & Management

**IT Profile:** On-premise Windows Server environment, Active Directory domain, 45 workstations, shared file servers for client document storage, limited SaaS tooling. No dedicated security function.

**Consulting context:** The absence of a dedicated security team is the engagement entry point. Hargrove needs a consultant to assess their environment, identify risk, and improve their posture ahead of a SOC 2 audit. That is the framing for all work in this lab.

---

## Core Goals

- Build and configure enterprise-grade IT infrastructure from scratch
- Develop hands-on skills in IAM, SOC analysis, vulnerability management, and hardening
- Document at every step — architecture, decisions, findings, remediation
- Produce consulting-ready artifacts throughout the process

---

## Resources

- [Josh Madakor — Active Directory Lab](https://www.youtube.com/watch?v=MHsI8hJmggI&t=194s)
- [CIS Benchmarks](https://www.cisecurity.org/cis-benchmarks)
- [NIST CSF](https://www.nist.gov/cyberframework)
- [Wazuh Documentation](https://documentation.wazuh.com)
- [Nessus Essentials](https://www.tenable.com/products/nessus/nessus-essentials)
- [MITRE ATT&CK](https://attack.mitre.org)

