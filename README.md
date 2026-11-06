# Ibrahima Aw

**Identity & Access Management · Identity Governance · Security Automation**

I work in enterprise IAM operations, with a focus on the practical side of identity security: understanding who has access, why they have it, what changed, and whether the evidence holds up during review.

My background spans Active Directory and LDAP, Microsoft Entra ID group administration, Okta access workflows, NetIQ identity operations, SailPoint access review campaigns, and operational/audit workflows involving ServiceNow and Sentinel. I build small, read-only automation tools to make that work more repeatable and easier to investigate.

**[Explore my IAM Automation Portfolio](https://norones-rgb.github.io/ad-ldap-exception-risk-analyzer/)** · [Read the engineering overview](https://github.com/norones-rgb/ad-ldap-exception-risk-analyzer/blob/main/IAM-AUTOMATION-PORTFOLIO.md)

## Featured IAM automation projects

Five independent **PowerShell 7.2+** projects using synthetic fixtures, Pester tests, and GitHub Actions on Windows and Linux. Each produces reviewable HTML, CSV, and JSON evidence without making access changes.

| Project | What it examines |
| --- | --- |
| [AD/LDAP Exception & Risk Analyzer](https://github.com/norones-rgb/ad-ldap-exception-risk-analyzer) | Stale accounts, privileged memberships, authentication and directory exceptions. |
| [Employee Offboarding Verification](https://github.com/norones-rgb/employee-offboarding-verification-tool) | HR-to-AD-to-application access reconciliation and outstanding offboarding evidence. |
| [AD Group Membership Change Tracker](https://github.com/norones-rgb/ad-group-membership-change-tracker) | Membership additions/removals, privileged changes and incomplete snapshot coverage. |
| [Service Account Hygiene Auditor](https://github.com/norones-rgb/service-account-hygiene-auditor) | Traditional service accounts, gMSAs/sMSAs, delegation settings and ownership gaps. |
| [User Access Review Evidence Generator](https://github.com/norones-rgb/user-access-review-evidence-generator) | Entitlement reconciliation, reviewer decisions, review baselines and evidence gaps. |

**[See the visual portfolio →](https://norones-rgb.github.io/ad-ldap-exception-risk-analyzer/)**

## More work in Python

- **[Entra & Microsoft 365 Access Governance Auditor](https://github.com/norones-rgb/entra-m365-governance-auditor)** — synthetic Entra/SharePoint governance evidence, access-review signals and a scoped audit scorecard.
- **[Application Access Reconciler](https://github.com/norones-rgb/application-access-reconciler)** — reconciles identity records and application account exports into an investigation queue.
- **[SaaS License Optimization Analyzer](https://github.com/norones-rgb/saas-license-optimization-analyzer)** — reviews Jira/Confluence license allocations and models potential savings under documented assumptions.

## Areas I work in

**Identity operations:** Active Directory / LDAP · Microsoft Entra ID · Okta · NetIQ IDM  
**Identity governance:** SailPoint access requests and approvals · User Access Reviews · Job-role reviews · Audit evidence  
**Operations and analysis:** ServiceNow · Jira / Confluence · Sentinel · Access reconciliation  
**Automation:** PowerShell · Python · CSV / JSON · HTML reporting · Pester · GitHub Actions

## How I approach the work

An incomplete export should not look like successful offboarding. A missing approval should not be silently treated as valid access. My projects are designed to surface those uncertainties and give operators something concrete to review.

> **Portfolio scope:** These are independent, synthetic-data demonstrations, not employer deployments or certifications of production security. The analyzers are read-only; remediation and access decisions remain with authorized people and processes.