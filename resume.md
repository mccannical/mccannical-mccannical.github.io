# Jesse McCann

**Staff Infrastructure Engineer - Platform, Cloud & AI Infrastructure**

Philadelphia, PA | jesse@mccannical.com | 818-403-8142
linkedin.com/in/jessemccann | github.com/mccannical | mccannical.com

---

## PROFESSIONAL SUMMARY

Staff infrastructure engineer with 15+ years owning production platforms across AWS, GCP, and Azure -
and a subject-matter expert and lead SRE for onboarding new clients and supporting large customers. I
turn manual, fragile operations into one-command automation (multi-cloud Kubernetes, Terraform /
OpenTofu, CI/CD, cloud cost governance) and build AI infrastructure and enterprise AI platforms:
multi-agent systems, agentic tooling, and the identity and tenancy foundations (standalone GCP
tenants, Workforce Identity Federation, MCP) that let teams and models ship real code together.
FedRAMP High/Moderate and NIST 800-171 experience; mentor to 10+ engineers.

## TECHNICAL SKILLS

- **Cloud & Infrastructure:** AWS, GCP, Azure, Kubernetes (GKE), Terraform / OpenTofu, Ansible, Docker, Linux
- **Languages:** Python, Go, Bash, PowerShell, SQL
- **Identity & Access:** Microsoft Entra ID, Workforce Identity Federation, OIDC, SAML, least-privilege IAM, SCIM
- **AI Platform & Infrastructure:** Gemini Enterprise (Agentspace), Vertex AI, GitHub Copilot, multi-agent orchestration, MCP / agentic tooling
- **Automation & Integration:** Workato, Workday, CI/CD (GitHub Actions, Cloud Build, GitLab CI), mise, uvx, Git
- **Observability & Data:** OpenSearch, Apache Kafka, ELK Stack, PRTG
- **Security & Compliance:** FedRAMP (High/Moderate), NIST 800-171, Zero Trust, vulnerability management, continuous monitoring

## PROFESSIONAL EXPERIENCE

### Senior Systems Infrastructure Engineer, Corporate IT (Consultant)
**BlackLine - Greater Philadelphia | 2025 - Present**

Consulting at the intersection of Corporate IT and AI engineering; building BlackLine IT's enterprise AI platform foundation.

- Launched BlackLine's Gemini Enterprise (Agentspace) platform: stood up Dev, Test, and Prod environments and data connectors (SharePoint, OneDrive, Outlook, Teams, Jira, Confluence), moved apps from SAML to OIDC, and restricted production data access.
- Designed and delivered a standalone, Terraform-managed GCP tenant for AI and agent workloads - org and folder structure, least-privilege IAM for citizen developers, network and tenant isolation, and a reusable Terraform module for business-unit agent projects.
- Implemented Workforce Identity Federation between Microsoft Entra ID and GCP; added a vaulted break-glass account and dedicated elevated accounts, and removed over-privileged ("god-mode") bindings and legacy admin tiers.
- Established infrastructure-as-code and release discipline - migrated Terraform state, centralized shared configuration, consolidated Entra identity management, and added semantic versioning, Conventional Commits, automated changelogs, and release pipelines; built self-service AI Playgrounds with on-demand provisioning, automatic TTL cleanup, and a v1.0.0 library of reusable AI skills.
- Automated the employee lifecycle (PowerShell onboarding/offboarding, scheduled Workday export, daily reports, PRTG monitoring); delivered Workato SSO/SCIM and a Confluence OAuth connector; authored ~100 Confluence pages of architecture and runbooks.

### Site Reliability Engineer, DAS Cloud
**DTEX Systems - Greater Philadelphia | May 2024 - Present**

SME and lead SRE for new-client onboarding and large customers on multi-tenant DAS Cloud, across commercial and FedRAMP High/Moderate environments.

- Served as lead SRE and subject-matter expert for new-client onboarding and large customers; delivered ~300 completed Jira issues (SRE, Service Desk, DAS 7, FedRAMP, customer environments) and authored ~126 Confluence pages of architecture, runbooks, and standards.
- Built a multi-cloud Kubernetes deployment platform (Terraform / OpenTofu) that cut new-customer environment provisioning from days of manual work to one command and ~1 hour, and reduced monthly cloud spend 45% through Cloud Custodian policy automation.
- Designed an internal multi-agent AI platform (Vertex AI + Copilot) with a durable issue graph for long-running agent work, now the team's blueprint for large-scale legacy refactoring.
- Defined Terraform style and module standards, introduced a facade-based infrastructure pattern, split the SRE monorepo into independently managed repositories, and shipped the DAS 7.3 Terraform and Ansible release.
- Closed critical FedRAMP controls (SSH hardening, key rotation, SAML protection for Nessus, scanner evidence, Salt/Zabbix remediation, GitLab upgrades) and expanded production IAM controls across RDS, CloudWatch, logging, Lambda, and snapshots.
- SME for OpenSearch and GCP architecture: evaluated and delivered multiple OpenSearch architectures (AWS, Aiven, Canonical Charmed with Juju), adopting Cluster Insights, UltraWarm/cold storage, and in-place DAS upgrades; completed GCP commercial productionization.
- Improved detection and recovery via DAS CloudWatch alerting, CloudWatch-to-Slack integration, a service-status page, RDS snapshots, immutable backups, and multi-AZ conversion; led resolution of customer-impacting incidents involving Elasticsearch health, storage, certificate expiry, and message-queue pressure.

### Sr. Cloud Systems Engineer / Technical Lead
**Confluent - Mountain View, CA | Nov 2020 - Apr 2024**

Infrastructure through pre-IPO, IPO, and post-IPO growth at the company behind enterprise Apache Kafka.

- Built and operated Go and Python infrastructure services on GCP Cloud Run, with CI/CD from GitHub through Cloud Build; deployed GKE with Terraform and custom Go cluster-management tooling.
- Led a multi-quarter Zero Trust network rollout (Palo Alto) for a global workforce, writing the allow-list automation so the cutover caused zero work interruptions.
- Killed a proposed GitHub EMU migration by building proof-of-concept tooling to quantify its blast radius; presented findings to InfoSec, TPM, and Engineering leadership to steer the decision to GitHub Enterprise. Mentored 10 engineers across the infrastructure teams.

### Staff System Engineer
**BlackLine - Woodland Hills, CA | Feb 2018 - Nov 2020**

Migrated 4 Nutanix clusters, 30 servers, and 10 applications to GCP with Terraform; ran the Atlassian stack (3,000 users) in high availability and automated HRIS updates, server deployment, and patch management, saving 10-15 hours per week.

### Earlier Roles

**Senior System Engineer, Applied Minds** (2014-2018) - NIST 800-171 compliance, AWS migration at 99.99% uptime, real-time ELK monitoring; promoted to IT Manager. **Senior Systems Engineer, Virgin Galactic** (2012-2014) - high-availability clusters, network security, SAN / Dell PowerVault storage migration. **Server Support Engineer, Publix Super Markets** (2007-2012).

## EDUCATION, CERTIFICATIONS & PUBLICATIONS

- AWS Certified Solutions Architect - Associate | Technical Mentor, Princeton University | Polk State College, 2005-2006 | CFCC, 1999-2001
