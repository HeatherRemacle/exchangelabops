---
title: Play 5
permalink: /play5

layout: post
sidenav: plays
subnav: 
  - text: Transition to Ops
    href: '#transition-to-ops'
  - text: Step 1. Review your operations MOU 
    href: '#step-1-review-your-operations-mou-that-was-part-of-play-2-with-the-ministry-it-operations-branch-or-outsourced-provider'
  - text: Step 2. Complete knowledge transfer
    href: '#step-2-complete-knowledge-transfer'
  - text: Step 3. Validate Ops processes
    href: '#step-3-validate-ops-processes-including'
  - text: Guidance to consider
    href: '#guidance-to-consider'
---
## Transition to Ops
Following a successful initial product development and deployment a new modern application (digital product) is launched. At this stage a decision is made  concerning the products lifecycle. Ensure that the Operations team has been involved in the previous plays on a regular basis from team formation product delivery so that they are aware and have been able to provide input into your delivery pipeline processes. Following formal  knowledge transfer from the development team the product can be transitioned to the operations team. If the initial product (often called a Minimal Viable Product or MVP) will require enhancements, then it typically enters the **Continuous Product Improvement** cycle as described in [Play 6](/CITZ-IMB-playbook/play6). If however, the product meets the business needs, it will proceed through an operations cycle consisting of product governance and change management. 

### Step 1: Review your operations MOU (that was part of [Play 2](/CITZ-IMB-playbook/play2) with the Ministry IT Operations branch (or outsourced provider)
- It takes time to resource additional skills, often as long as 6 months, plan accordingly in your transition plan

### Step 2: Complete knowledge transfer
- adopt the [‘Site Reliability Engineer’ support model](https://landing.google.com/sre/) pioneered by Google
- throughout the development cycle the product team member who represents the Ministry Ops team should be regularly participating in the development team meetings and ideally is cross functionally trained to understand how product features have been developed, tested and pushed through the deployment pipeline

### Step 3: Validate Ops processes including:
- [Change Management](https://en.wikipedia.org/wiki/Change_management) procedures
- Monitoring & Logging
  - Application Performance Monitoring ([APM](https://www.ea.oit.va.gov/EAOIT/docs/Oct_2016_Release_Docs/APM-2-2.pdf)) metrics have been defined
  - Application logs are generated and maintained in accordance with policy. 
- Tooling Updates
- Product Triage
  - Define your product triage procedures
- Escalation

### Guidance to consider:
- The Ops  team member should communicate  with colleagues of the Ministry Ops team to educate other team members on the product shared documentation, its tooling and design review meetings
- Source Code Repository (such as the projects GitHub repo) has a readme file with relevant procedures and  links required to recreate the solution installation  
- Make documentation easily locatable (Confluence, SharePoint, GitHub)
- Create a Product “Runbook”
- Monitoring Environment ([ELK stack](https://logz.io/learn/complete-guide-elk-stack/), Splunk, Nagios)
- [Google’s monitoring & logging patterns](https://cloud.google.com/solutions/hybrid-and-multi-cloud-monitoring-and-logging-patterns)
- [Triage best practices](https://dzone.com/articles/agility-meets-process-how-to-triage-requests-to-ef)
- Knowledge Transfer best practices
- Review your operating commitments
  - 9’s uptime
  - Performance targets

<br/>
[Back to the Top](#)