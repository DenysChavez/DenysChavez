# Hi there 👋

I'm Denys — a Cloud Computing student who likes understanding how a business actually runs, then building the systems that support it.

- 🔭 **Currently working on** a private, production-style AWS environment built entirely with modular Terraform — zero-SSH access via Systems Manager, least-privilege IAM, encryption at rest, automated backups with tested restores, and CloudWatch billing alarms.
- 🌱 **Currently learning** SAP BTP beyond the fundamentals (Cockpit, subaccounts, IAS/IPS identity, Cloud Foundry), plus Python and Azure through my A.S. coursework.
- 👯 **Looking to collaborate on** infrastructure-as-code projects, small-business web builds, and anything that replaces a manual process with a documented, repeatable one.
- 🤔 **Looking for help with** going deeper on enterprise SAP workflows and on data/reporting tooling — if you work in that space, I'd love to hear how you got started.
- 💬 **Ask me about** Terraform module design, locking down an AWS account without SSH, debugging a server you can't shell into, or scoping a real client project before writing any code.
- 📫 **How to reach me:** [LinkedIn](https://linkedin.com/in/denyschavez-fuentes) 
- ⚡ **Fun fact:** I once spent a day debugging a server I had no shell access to. The fix was one line — a Terraform AMI filter was quietly matching the "minimal" image variant, which ships without the SSM agent. I found it by injecting a diagnostic script through EC2 user_data.

---

### 🛠️ What I work with

**Cloud & Infrastructure** — AWS (EC2, VPC, IAM, S3, Systems Manager, AWS Backup, CloudWatch, SNS) · Terraform

**Security** — Least-privilege IAM, IMDSv2, encryption at rest, HTTPS-only bucket policies, zero-inbound-port networks

**Enterprise Platforms** — SAP BTP (Cockpit, account/subaccount structure, IAS/IPS, Cloud Foundry)

**Web** — Next.js · React · Payload CMS · Postgres (Neon) · Vercel · HTML/CSS/JS

**Other** — Git/GitHub · Linux CLI · Python

---

### 📌 Projects

**Secure AWS Environment with Automated Controls** — Terraform, AWS
Private VPC with public/private subnets, all admin access through Session Manager instead of SSH, a least-privilege IAM policy validated over four rounds of live testing, and automated daily backups with restore tests.

**Custom-Furniture Business Site** — Next.js 16, Payload CMS 3, Postgres, Vercel
Ran end-to-end discovery for a real client and wrote a 20-section spec before building. Designed an inventory model covering three product types and consolidated four separate inquiry flows into one lead pipeline.

---

### 🎓 Education & Certifications

- **A.S., Cloud Computing** — Delaware County Community College *(expected 2027)*
- **SAP BTP Fundamentals — Level 1: Foundations** *(SAP Learning, 2026)*
- **SAP BTP Fundamentals — Level 2: Administration, Security, Extensibility & Data-to-Value** *(SAP Learning, 2026)*
