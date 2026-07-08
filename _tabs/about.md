---
# the default layout is 'page'
icon: fas fa-info-circle
order: 4
---

## Jesse McCann
**Staff Platform / Infrastructure Engineer**

📍 Philadelphia, Pennsylvania &nbsp;·&nbsp; [jesse@mccannical.com](mailto:jesse@mccannical.com) &nbsp;·&nbsp; 818-403-8142 &nbsp;·&nbsp; [LinkedIn](https://www.linkedin.com/in/jessemccann) &nbsp;·&nbsp; [GitHub](https://github.com/mccannical)

I've spent 15+ years owning production infrastructure, from aerospace systems at Virgin Galactic to multi-cloud Kubernetes platforms in FedRAMP High environments. Most of my work is the plumbing other engineers build on: deployment automation, developer environments, cloud cost governance, and lately, the workflows that let engineers and AI agents work together on real codebases. On the side I ship complete products solo (Next.js / Supabase / Stripe), and I build with Claude daily.

### Experience

#### Site Reliability Engineer — DTEX Systems
*Jun 2024–Present · Greater Philadelphia*

Platform engineering for multi-tenant SaaS across commercial and FedRAMP High/Moderate environments.

- Built and own the multi-cloud Kubernetes "deployment factory": Terraform/OpenTofu IaC that turns standing up a customer environment from days of manual work into one command and about an hour.
- Cut monthly cloud spend 30% in the first cleanup pass and 45% overall, mostly through Cloud Custodian policy automation.
- Built an internal multi-agent AI platform: Vertex AI and Copilot for inference, with a durable issue graph holding state so agents can handle long-running work. The team now uses the blueprint for large-scale legacy refactoring, and one prototype goes from a PRD to a working web UI validated with Playwright.
- Built an agentic tool that pulls a full picture of a customer out of Jira and Confluence in about 30 seconds.
- Standardized the team's developer environment: mise for tool versions, Python tools distributed via uvx, one-command GCP/AWS auth.
- SME for OpenSearch and GCP architecture. Own continuous monitoring, vulnerability management, and patching, with 24×7 on-call.
- Mentor engineers on AI-assisted development.

#### Sr. Cloud Systems Engineer / Technical Lead — Confluent
*Nov 2020–Apr 2024 · Mountain View, CA*

Infrastructure through pre-IPO, IPO, and post-IPO growth at the company behind enterprise Apache Kafka.

- Wrote and operated Go and Python infrastructure services on GCP Cloud Run, with CI/CD from GitHub through Cloud Build. Deployed GKE with Terraform plus custom Go cluster-management tooling.
- Led a multi-quarter Zero Trust network rollout (Palo Alto) for a global workforce. Wrote the allow-list automation so the cutover didn't interrupt anyone's work.
- When a GitHub EMU migration was on the table, built proof-of-concept tools to measure how much would break, took the findings to InfoSec, TPM, and Engineering leadership, and helped steer the decision to GitHub Enterprise instead.
- Mentored 10 engineers and ran continuous-learning efforts across the infrastructure teams.

#### Staff System Engineer — BlackLine
*Feb 2018–Nov 2020 · Woodland Hills, CA*

- Directed the migration of legacy infrastructure to GCP with Terraform.
- Ran the Atlassian stack in a high-availability setup; integrated SAP Resolve with Salesforce.
- Put the cloud infrastructure under version control in GitLab.
- Trained the team on Git, PowerShell, Python, and Terraform. Automated HRIS updates, server deployment, and patch management.

#### Senior System Engineer — Applied Minds
*Dec 2014–Feb 2018 · Burbank, CA*

- Led the company's NIST 800-171 compliance effort and implemented the security controls behind it.
- Built real-time monitoring on the ELK stack in Azure; set up backup and disaster recovery.
- Migrated internal applications to AWS on time and on budget; maintained 99.99% uptime. Led an Exchange → Office 365 migration.

#### Senior Systems Engineer — Virgin Galactic
*Jul 2012–Nov 2014 · Mojave, CA*

- Ran high-availability clusters for critical services and scripted their installs.
- Handled network security: firewalls and intrusion detection.
- Led the storage migration to SANs and Dell PowerVaults; integrated Linux servers with Active Directory. Started as a System Administrator and was promoted.

#### Server Support Engineer — Publix Super Markets
*Mar 2007–Jul 2012 · Lakeland, FL*

### Skills

- **Core:** Kubernetes, Terraform / OpenTofu, Python, Go
- **Cloud:** AWS, GCP, Azure
- **Platform & DevEx:** CI/CD, Ansible, mise, uvx, Make, Git
- **AI:** Multi-agent workflows, MCP / agentic tooling, Vertex AI, Copilot
- **Compliance & Security:** FedRAMP (High/Moderate), NIST 800-171, continuous monitoring, vulnerability management
- **Data & Observability:** OpenSearch, Apache Kafka

### Certifications & Education

- AWS Certified Solutions Architect – Associate
- Polk State College, 2005–2006
- CFCC, 1999–2001
- Technical Mentor, Princeton University
