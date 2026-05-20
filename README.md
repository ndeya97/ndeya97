# 👋🏽 Ndeye Awa Diop
**IAM Engineer — Identity Governance & Cloud IAM**  
Calgary, Alberta, Canada · Permanent Resident · No sponsorship required

---

## 🔐 About me

IAM Engineer with a background in software development and hands-on experience 
with SailPoint IdentityIQ at **BNP Paribas** — one of Europe's largest regulated 
banking environments.

Directly implemented Leave of Absence and ComeBack workflows, BeanShell 
aggregation rules, and Mover access certification campaigns in a complex, 
multi-system banking context.

Currently based in Calgary and actively transitioning to Cloud IAM — 
preparing **Microsoft SC-300** and upskilling on **SailPoint Identity Security Cloud (ISC)**.

---

## 🏦 Key Experience

**Junior Security Consultant — Synetis (Client: BNP Paribas)** · Paris · Oct 2023 – Feb 2024  
*Reference letter available upon request*

**Directly implemented:**
- Leave of Absence (LOA) workflow — temporary access suspension via HR event trigger
- ComeBack workflow — access restoration and re-provisioning after return from leave
- Access certification campaigns — Mover scenarios (least-privilege enforcement)
- BeanShell aggregation rules for identity data processing
- CSV onboarding and identity model configuration
- Notification templates (EmailTemplate) using Velocity
- IdentityIQ UI customization (branding, HTML/CSS)
- Technical documentation (admin guides, spec updates)

**Participated in (testing & UAT):**
- Joiner / Mover / Leaver workflows — debugging and production issue resolution

---

## 🧪 Project

### 🏦 sailpoint-iiq-lifecycle-demo
> Based on hands-on work with SailPoint IdentityIQ at BNP Paribas (via Synetis)

**What it does:** Reproduces IAM lifecycle patterns from a regulated banking 
environment — HR data ingestion, identity correlation, LOA/ComeBack handling, 
and access certification.

| Layer | Implementation |
|---|---|
| **Data ingestion** | HR CSV → identity attribute mapping |
| **Joiner** | Account creation + role assignment (UAT & testing) |
| **Mover** | Department change → remove old access, assign new entitlements |
| **LOA** | Temporary access suspension — accounts disabled, roles preserved |
| **ComeBack** | Access restoration based on current role profile |
| **Certification** | Mover scenarios — manager review, least-privilege enforcement |

**Project files:**

| File | Description |
|---|---|
| `/rules/correlation-rule.bsh` | BeanShell rule — identity matching by employeeId or email |
| `/data/hr-sample.csv` | Sample HR file with JML event types |
| `/workflows/loa-comeback-workflow-spec.md` | LOA & ComeBack technical specification |

**Tech:** `SailPoint IIQ` `BeanShell` `Java` `CSV` `SQL` `Velocity`

📁 [View project →](https://github.com/ndeya97/sailpoint-iiq-lifecycle-demo)

---

## 🚧 In Progress — Cloud IAM Project

**sailpoint-isc-entra-identity-governance** *(coming soon)*  
Hybrid Cloud IAM demo: SailPoint ISC Transforms + Microsoft Entra ID 
provisioning via Terraform.  
`Python` `Terraform` `JSON` `REST API` `Microsoft Graph`

---

## 🎯 Certifications & Learning

| Certification | Provider | Status |
|---|---|---|
| SC-300 — Identity & Access Administrator | Microsoft | 🔄 In progress |
| Identity Security Engineer | SailPoint | ⬜ Planned |

*Preparing via Microsoft Learn (SC-300) and developer.sailpoint.com*

---

## 🛠 Technical Skills

**IAM / IGA:** SailPoint IdentityIQ · Identity Lifecycle (JML) · Access Certification · BeanShell · Velocity  
**Cloud IAM:** SailPoint ISC (in progress) · Microsoft Entra ID (learning)  
**Auth protocols:** SSO · SAML · OAuth2 · MFA (conceptual knowledge · deepening via SC-300)
**Development:** Java · Spring Boot · REST APIs · SQL / PL-SQL  
**Tools:** Git · Docker · Postman · Apache Tomcat · IntelliJ · VS Code

---

## 📫 Connect

[LinkedIn](https://linkedin.com/in/ndeyeawadiop)  
Open to IAM Engineer / IGA roles in Calgary — **available now**
