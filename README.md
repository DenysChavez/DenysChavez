# Hi, I'm Denys 👋

Cloud Computing student building a career in **cloud engineering**, focused on AWS and SAP BTP. My goal: start as a **Junior SAP BTP Administrator / Junior SAP Cloud Engineer** and grow into an **SAP Cloud Solutions Architect**.

I learn in public. Every lab ends up in a repo with evidence, redacted screenshots, and a cleanup checklist, so you can see what I've actually built.

- 🔭 **Working on:** [AWS + SAP Cloud Engineering Portfolio](https://github.com/DenysChavez/aws-sap-cloud-engineering-portfolio), a 13-week plan rebuilding my AWS labs with evidence, then moving to hands-on SAP BTP
- 🌱 **Learning now:** IAM policies, roles and permissions boundaries (Week 2). Next: VPC networking, then my first SAP BTP trial account
- 🤝 **Open to:** internships and entry-level roles, available now. Remote, or hybrid in the Philadelphia / Malvern, PA area
- 🌎 **Languages:** English and Spanish (native)
- 📫 **Reach me:** [LinkedIn](https://www.linkedin.com/in/denyschavez-fuentes/)

---

###  Projects

**[AWS + SAP Cloud Engineering Portfolio](https://github.com/DenysChavez/aws-sap-cloud-engineering-portfolio)** · AWS · SAP BTP · *in progress*
Five planned projects, from AWS infrastructure and SAP BTP administration to Integration Suite and Terraform. Each one is marked verified only once the evidence is in the repo.
- ✅ **Week 1: [Securing a new AWS account](https://github.com/DenysChavez/aws-sap-cloud-engineering-portfolio/blob/main/technical-notes/securing-a-new-aws-account.md).** Root MFA, budgets, an MFA-protected admin user, short-term CLI credentials, and an audit of leftover resources. The audit found a privilege-escalation path in an old IAM policy, which I removed.
- 🟨 **Week 2: least-privilege IAM.** A bucket-scoped read-only policy tested in the Policy Simulator and with real calls, roles, and permissions boundaries.

**[AI Agent Sandbox on AWS](https://github.com/DenysChavez/ai-agent-sandbox)** · Terraform · AWS · *completed and torn down*
A self-hosted sandbox built with modular Terraform: a private VPC, admin access only through Systems Manager (no SSH), encryption at rest, daily AWS Backup with restore tests, and CloudWatch billing alarms.
Lesson learned: when I later reviewed the operator IAM policy, I found it allowed `CreateRole` + `AttachRolePolicy` + `PassRole` with no conditions, which is a path to admin. I now test policies for escalation, not just for whether they work.

---

###  Skills

| Area | Hands-on (with evidence) | Learning now |
|---|---|---|
| **Cloud platforms** | AWS: IAM, EC2, VPC, S3, Systems Manager, AWS Backup, CloudWatch, SNS, CloudTrail, Budgets | SAP BTP: account model, entitlements, role collections, Cloud Foundry |
| **Security** | Root/MFA hardening, least-privilege IAM, IMDSv2, encryption at rest, no-SSH access | Permissions boundaries, IAM Access Analyzer |
| **IaC & tools** | Terraform, AWS CLI, Git/GitHub | Python and Linux (beginner) |

---

###  Roadmap

| Phase | Focus | Status |
|---|---|---|
| Weeks 1–5 | AWS foundations: account security, IAM, VPC, EC2, S3/KMS → **Project 01** | 🟨 In progress |
| Weeks 6–8 | SAP BTP administration: account model, entitlements, role collections, Cloud Foundry → **Project 02** | ⬜ |
| Weeks 9–11 | Integration: Lambda + APIs, SAP Integration Suite, API Management → **Project 03** | ⬜ |
| Weeks 12–13 | Terraform rebuild (**Project 05**) and AWS + SAP hybrid design (**Project 04**) | ⬜ |

---

### 🎓 Education & badges

- **AAS, Cloud Computing**, Delaware County Community College *(expected May 2027)*
- **SAP BTP Fundamentals, Level 1** and **Level 2**: SAP Learning course-completion badges *(June 2026)*

---

<sub>⚡ Favorite debugging story: I spent a day on a server I couldn't shell into. The fix was one line. A Terraform AMI filter was matching the "minimal" image, which ships without the SSM agent. I found it by injecting a diagnostic script through EC2 user data.</sub>
