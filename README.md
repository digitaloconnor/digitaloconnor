# Tony O’Connor

** Automation Engineer · IT Infrastructure · Cork, Ireland **  
 16 years in IT. 3 years building production automation.  
 I connect systems, eliminate manual work, and get AI to do the boring stuff.

---

##  What I Actually Build

**n8n Workflow Automation**  
150+ production workflows across GCP, Azure, and Docker.  
Event-driven orchestration, scheduled jobs, human-in-the-loop approvals — built to the standard where something breaking at 2am is diagnosable in under 5 minutes.

Real example: AI-assisted ticket triage (n8n + GPT-4 + Freshdesk) — 
**90% reduction in resolution time**. Human agent reads the AI draft and decides. The workflow cannot bypass the human. That's structural, not a rule.

**Security Automation**  
Email header analysis (SPF/DKIM/DMARC) delegated to GPT-4, plain English risk verdict out. Alert only on HIGH/CRITICAL. Tested against KnowBe4 until false positive rate hit zero. Security+ certified.

**Integration Work**  
Microsoft 365 · Google Workspace · Slack · Telegram · Freshdesk · GitHub · OpenAI/GPT-4 · Claude · Whisper · Pinecone · Veeam · N-able RMM · DattoRMM
---

##  How I Build

- Under 20 nodes per workflow — then sub-workflows
- Named nodes, section-level sticky notes, no mystery JSON
- Secrets in `.env` files — never hardcoded, never committed
- Error alerts only for business-critical failures (alert fatigue is a real cost)
- Self-heal pattern: retry 3× → fallback → *then* escalate
- Every production workflow ships with README, changelog, `.env.example`, test data, and SECURITY.md

---

##  Certifications

- CompTIA Security+ ce
- Microsoft 365 Certified: Fundamentals
- Microsoft Certified: Azure Fundamentals
- Microsoft Certified: Security, Compliance, and Identity Fundamentals
- Google Cybersecurity Specialization  

---

## Currently Building

- Structured error log sub-workflow (queryable, pattern detection across failures)
- API changelog monitor (RSS/GitHub releases → Claude classification → Telegram alert on breaking changes only)
- First autonomous AI agent (real problem, not a tutorial) 

---



