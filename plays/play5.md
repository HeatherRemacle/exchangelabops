---
title: Play 5
permalink: /play5

layout: post
sidenav: docs
subnav: 
  - text: Transition to Operations
    href: '#transition-to-operations'
  - text: Step 1. Review Your MOU 
    href: '#step-1-review-your-memorandum-of-understanding-see-play-2'
  - text: Step 2. Complete Knowledge Transfer
    href: '#step-2-complete-knowledge-transfer'
  - text: Step 3. Validate Operations Processes
    href: '#step-3-validate-operations-processes-including'
  - text: Guidance to Consider
    href: '#guidance-to-consider'
---
## Transition to Operations
Following successful initial product development and deployment, a new modern application (digital product) is launched. At this stage a decision is made concerning the products lifecycle. Ensure that the Operations team has been involved in the previous plays on a regular basis from team formation to product delivery so that they are aware of, and have been able to provide input into, your delivery pipeline processes. Following formal knowledge transfer from the development team, the product can be transitioned to the operations team. If the initial product (often called a Minimal Viable Product or MVP) requires enhancements, then it typically enters the **Continuous Product Improvement** cycle as described in [Play 6](/CITZ-IMB-playbook/play6). If, however, the product meets the business needs, it will proceed through an operations cycle consisting of product governance and change management.

### Step 1: Review Your Memorandum of Understanding (See [Play 2](/CITZ-IMB-playbook/play2))
- It takes time to resource additional skills (often as long as 6 months), so your transition plan should reflect this

### Step 2: Complete Knowledge Transfer
- Adopt the "Site Reliability Engineer" support model pioneered by Google
- Throughout the development cycle, the product team member who represents the Ministry Operations team should regularly participate in development team meetings and should be cross-functionally trained to understand how product features have been developed, tested, and pushed through the deployment pipeline

### Step 3: Validate Operations Processes Including:
- Change Management procedures
- Monitoring & Logging
  - Application Performance Monitoring ([APM](https://www.ea.oit.va.gov/EAOIT/docs/Oct_2016_Release_Docs/APM-2-2.pdf){:target="_blank"}) metrics have been defined
  - Application logs are generated and maintained in accordance with policy
- Tooling Updates
- Product Triage
  - Define your product triage procedures
- Escalation procedures

### Guidance to Consider
-	The project operations (Ops) team member communicates with colleagues of the Ministry DevOps and technical support team to educate other coworkers about the product’s shared documentation, tooling and outcomes from design review meetings
-	The project’s source code repository (ex: GitHub) has a README file with relevant procedures and links required to recreate the solution installation
-	Make documentation easily locatable (Confluence, SharePoint, GitHub)
-	Create a product "runbook"
-	Integrate your solution into the Ministry logging and monitoring environment 
- [Google’s monitoring & logging patterns](https://cloud.google.com/solutions/hybrid-and-multi-cloud-monitoring-and-logging-patterns){:target="_blank"}
- [Triage best practices](https://dzone.com/articles/agility-meets-process-how-to-triage-requests-to-ef){:target="_blank"}
- Knowledge transfer best practices
- Review your operating commitments:
  - 9’s uptime
  - Performance targets
- Read through and understand the <a target="_blank" href="/CITZ-IMB-playbook/docs/IMB-Application-Transition-Checklist.pdf">IMB Application Transition Checklist</a>

<br/>
[Back to the Top](#)