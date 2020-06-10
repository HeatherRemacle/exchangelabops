---
title: Modern Application Development IMB's Principles
permalink: /principles

layout: post
sidenav: docs
subnav:
    - text: Guiding Principles
      href: '#guiding-principles-adopted'
    - text: Application Principles
      href: '#application-principles-proposed'
    - text: Architecture Principles
      href: '#architecture-principles-proposed'
    - text: Project Governance Principles
      href: '#project-governance-principles-proposed'
    - text: Technical Principles
      href: '#technical-principles-proposed'
    - text: Infrastructure Principles
      href: '#infrastructure-principles-proposed'
---
Adopting these principles can help to guide your product decisions. Designing and building solutions that are loosely coupled and utilize interfaces for process communication will result in maintainable applications.

The following **proposed** principles offer guiding statements that should be considered in the development of your applications. 
- Guiding Principles
- Application Principles
- Architecture Principles
- Project Governance Principles  
- Technical Principles
- Infrastructure Principles  

IMB is developing a set of guidance patterns to assist Ministry business units in selecting platforms for their line of business solutions as well as a set of engagement patterns for IMB services. This list will evolve over time.

#### Platform & Solution Patterns
- DevExchange Adoption Pattern
- Microsoft PowerBI  Adoption Pattern
- Microsoft Dynamics Adoption Pattern
- Microsoft SharePoint Adoption Pattern
- RHEL OpenShift Adoption Pattern
- Web Application Development Pattern 

### IMB Patterns
- Ministry IMB Business Unit Engagement Pattern
- Ministry IMB Service Desk Pattern
- Ministry STRA & PIA Pattern
- Ministry IMB Infrastructure Support Pattern

## Guiding Principles <span style="color:green">\*adopted\*</span>

### Principle 1: Develop open and innovative partnerships 
We recognize that by developing trusted partnerships and collaborating across teams and the ministry, we create opportunities to find new ways of delivering efficient and effective services to program areas. 

### Principle 2: Service focus
Solutions and services are designed from a client-centered and end-to-end digital service delivery perspective to increase the value they bring to the client. 

### Principle 3: Teamwork and collaboration 
We will create and empower cross-functional, dynamic teams to increase engagement, communi¬cation, talent and opportunities to deliver value and services to clients. 

### Principle 4: Invest wisely 
Through effective governance and financial oversight, we will maximize IM/IT spend and optimize our existing investments to support the ministry. 

### Principle 5: Enable a modern and innovative workplace 
We will support collaboration, create efficiencies, and encourage people to work smarter, greener, healthier and more innovatively so all feel valued and recognized. 

### Principle 6: Continuous improvement 
We believe in testing early and often. We will test processes, services, and technology end-to-end and continuously improve in response to user feedback. 

### Principle 7: Proactive approach to security and privacy 
We are committed to supporting our clients to adopt a proactive approach to ensuring strong information security and privacy protection practices.  By applying a ‘privacy and security by design’ philosophy, we help our clients ensure that privacy and security measures are considered at project initiation and built in to the solution, rather than having to be retrofitted afterwards.

## Application Principles <span style="color:red">\*proposed\*</span>

### Principle 1: Do no harm
Only build what you can't buy and buy what you can't build.

### Principle 2: Build/Buy responsibly
Don't contribute to technical debt.

### Principle 3: Be citizen-centric
Everything you build is for the greater good. Citizens are the real product owners.

### Principle 4: Today's build could be tomorrows burden
Like building responsibly, think about the effort required to maintain and evolve the application.

### Principle 5: Nature vs. Nurture
An application will only be as good as the effort put into its evolution.

### Principle 6: Sharing is caring
Information is a commodity to be shared; build with this in mind.

### Principle 7: Keep it Small
Small code packages, small feature sets make for shorter delivery cycles, fewer changes and overall better software quality.

### Principle 8: Focus on the developer
Select the best environment with the right tooling. Endorse a good set of use of Architecture Principles.

### Principle 9: Develop for Networks
Application communication happens over the network, not in memory. Supports distributed development teams, increase application resiliency, and simplify product deployment. 

## Architecture Principles <span style="color:red">\*proposed\*</span>

### Principle 1: Primacy of Principles
... TOGAF Principles,  OCIO Digital principles, HADF principles

### Principle 2: Adhere to Standards
... OCIO Digital Framework, GCIO and Ministry Standards

### Principle 3: Adopt a set of Software Design Principles
Patterns and practices are the tools used to achieve the desired outcome of the principles. Follow fundamental principles for writing quality software such as:
- KISS  —  Keep it simple, stupid.
- DRY—Don’t repeat yourself.
    - Do not duplicate application this is a frequent source of errors.
- YAGNI—You aren’t gonna need it.
    - Are you going to need that feature? If not: leave it out.
- SoC—Separation of concerns.
    - Minimize tight coupling of code to low-implementation details by separating core business logic from infrastructure and user interface logic so that the module is easy to test and can be evolved. 

### Principle 4: Adopt a [Service Oriented Architecture](https://en.wikipedia.org/wiki/Service-oriented_architecture)
- Single responsibility
    - Objects should have only one reason to change this helps to produce more loosely coupled and modular systems.
- Bounded Context
    - Reduce complexity by reducing a solution into separate conceptual modules where  each module represents a context that is separated from other contexts (ie: bounded), and can be evolved independently of one another. 

### Principle 5: API First
Develop your solution to be used by multiple client applications through a well described API. 

### Principle 6: [Be data driven](https://digitalprinciples.org/wp-content/uploads/PDD_Principle-BeDataDriven_v2.pdf)

### Principle 7: Design to be secure
Design, develop and deliver solutions that [mitigate risks](https://blog.threatpress.com/security-design-principles-owasp/). Ensure security is addressed end to end and considered upfront. 

### Principle 8: Adopt Cloud
Whether public, private or hybrid cloud, adopt a set of [guiding principles for Cloud Computing and Use](https://www.isaca.org/bookstore/bookstore-wht_papers-digital/whpgp) - include enablement, cost/benefit, enterprise risk, capability, accountability and trust.

### Principle 9: DevOps for Agility
DevOps is founded on product delivery.  Agile is founded on the project success. Embrace the  combination of 1) continuous integration (including Build management, test management and automation), 2) continuous delivery (including environment management and deployment management), 3) infrastructure as code and 4) iterative development approach to support successful projects.

## Project Governance Principles <span style="color:red">\*proposed\*</span>
These principles apply to the **ministry governance process for the planning, intake and approval of IM/IT projects**.

#### Goals of Principles
- These principles will help the project governance team ensure that we understand the scope of the work, and stay focused on outcomes.
- The principles should be simple, straightforward and high-level.

### Principle 1: Enable the right people to make the right decisions at the right times.

### Principle 2: Be easy to understand and follow.

### Principle 3: Be simple and efficient, with each stepping adding value.

### Principle 4: Be timely.

### Principle 5: Add value for all stakeholders, while maximizing the benefits to the Ministry.

### Principle 6: Be transparent and enable decisions that are objective and fair.

### Principle 7: Apply a common set of selection criteria to all proposed IM/IT projects.

## Technical Principles <span style="color:red">\*proposed\*</span>

### Principle 1: Prioritize Principles 
Any decision to ignore or reject core principles so as to satisfy project goals must be recorded.

### Principle 2: Adopt Technology Standards that aid the Business
- Make Friends in the Business – if the business understands why a standard needs to be adopted they will be more likely to weigh the implications on impacts to their expected outcomes.
- Stakeholders drive the adoption of Technical Standards – if a standard is seen as an impediment then the natural pattern is to seek an exemption. Ensuring stakeholders are aware early on in the project lifecycle helps to develop adoption strategies.   
- Involve the Architects from start of your project – Architects are central to product viability discussions. Engaging them early will mitigate waste in the product development flow. 

## Infrastructure Principles <span style="color:red">\*proposed\*</span>

### Principle 1: Plan for needed Capacity
Solutions that evolve requirements need to be scalable in order to guarantee performance over the entire product lifecycle. Don’t over commit up front, validate the ability to meet unexpected system demands.

### Principle 2: Design for Scalability
Adoption and feature growth will result in unforeseen system demands. Ensure that the solution architecture is able to scale. 

### Principle 3: Achieve User Happiness through System Performance
User expectations will change over time. Ensure that the architecture is adaptable and can satisfy performance demands. Assess how the solution is hosted and its portability.

### Principle 4: Monitoring enables your team
Understand what to monitor. Ensure that the available monitoring system can provide actionable metrics in order to provide the necessary information needed to resolve any issues that can arise. Knowing what can cause performance issues and monitoring for those scenarios will feed the product continuous lifecycle with data.