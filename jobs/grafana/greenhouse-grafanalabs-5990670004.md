<!--
id: greenhouse-grafanalabs-5990670004
company: Grafana
title: Senior Backend Engineer - Application Core Services, Stacks | USA | Remote
source: greenhouse
location: United States (Remote)
remote: Remote
hybrid: no
posted_at: Unknown
first_seen: 2026-05-13
first_seen_at: 2026-05-13T21:39:33+00:00
url: https://job-boards.greenhouse.io/grafanalabs/jobs/5990670004
summary: Design and operate reconciliation systems and control-plane services that manage Grafana Cloud stack lifecycle, state alignment, and configuration across distributed infrastructure. You will work on stateful systems involving eventual consistency, multi-region operations, and incident recovery at scale across a SaaS platform serving thousands of customers.
skills: Go, Kubernetes, Terraform, TypeScript, AWS, GCP, Azure, Helm
level: senior
comp: $154,445-$185,334
comp_extras: equity, bonus
render_hash: 4cb68170
-->

# Senior Backend Engineer - Application Core Services, Stacks | USA | Remote

<img src="https://www.google.com/s2/favicons?domain=grafana.com&sz=32" width="16" height="16" align="absmiddle">&ensp;**Grafana**  
United States · `Senior` · `Remote` · `$154,445-$185,334` · `Equity` · `Bonus`

> Grafana builds an open-source observability platform that unifies metrics, logs, traces, profiles, and business data.

_Design and operate reconciliation systems and control-plane services that manage Grafana Cloud stack lifecycle, state alignment, and configuration across distributed infrastructure. You will work on stateful systems involving eventual consistency, multi-region operations, and incident recovery at scale across a SaaS platform serving thousands of customers._

![Go](https://img.shields.io/badge/Go-3B82F6?style=flat-square) ![Kubernetes](https://img.shields.io/badge/Kubernetes-3B82F6?style=flat-square) ![Terraform](https://img.shields.io/badge/Terraform-3B82F6?style=flat-square) ![TypeScript](https://img.shields.io/badge/TypeScript-3B82F6?style=flat-square) ![AWS](https://img.shields.io/badge/AWS-3B82F6?style=flat-square) ![GCP](https://img.shields.io/badge/GCP-3B82F6?style=flat-square) ![Azure](https://img.shields.io/badge/Azure-3B82F6?style=flat-square) ![Helm](https://img.shields.io/badge/Helm-3B82F6?style=flat-square)

<sub>First seen May 13, 2026 at 21:39 UTC</sub>

**[→ Apply](https://job-boards.greenhouse.io/grafanalabs/jobs/5990670004)**

---

Grafana Labs is a remote-first, open-source powerhouse. There are more than 20M users of Grafana, the open source visualization tool, around the globe, monitoring everything from beehives to climate change in the Alps. The instantly recognizable dashboards have been spotted everywhere from a NASA launch and Minecraft HQ to Wimbledon and the Tour de France. Grafana Labs also helps more than 3,000 companies -- including Bloomberg, JPMorgan Chase, and eBay -- manage their observability strategies with the Grafana LGTM Stack, which can be run fully managed with Grafana Cloud or self-managed with the Grafana Enterprise Stack, both featuring scalable metrics (Grafana Mimir), logs (Grafana Loki), and traces (Grafana Tempo).

We’re scaling fast and staying true to what makes us different: an open-source legacy, a global collaborative culture, and a passion for meaningful work. Our team thrives in an innovation-driven environment where transparency, autonomy, and trust fuel everything we do.

You may not meet every requirement, and that’s okay. If this role excites you, we’d love you to raise your hand for what could be a truly career-defining opportunity.

This is a remote opportunity and we would be interested in applicants located in USA time zones (EST + CST only at this time).&nbsp;

Senior Backend Engineer - Application Core Services, Stacks

The Opportunity:&nbsp;

Application Core Services (AppCore) is a group within Platform, in the Foundations department. Foundations produces the Internal Engineering Platform (IEP) and partners closely with our Cloud, Enterprise, and Grafana teams. Our team develops the essential systems driving Grafana's business operations. We utilize the grafana.com platform to engineer bespoke integrations and solutions that unify the diverse technical ecosystem of a modern software enterprise.

The team owns important domain areas that help keep both our customer workflows and internal business processes running smoothly. AppCore is made up of multiple squads, each focused on one or more of these domains. Our work includes maintaining the billing engine responsible for customer usage calculation, automating provisioning after a customer signs a contract, integrating with cloud marketplaces such as AWS, Azure, and GCP, and building and maintaining the user portal our customers rely on to manage their accounts.

This is a team working at the intersection of product, platform, and business operations. The systems we build are critical to how Grafana scales. We are looking for engineers who enjoy solving complex workflow and systems problems, improving reliability and developer experience, and building software that directly supports both customers and internal stakeholders.

As a company we are remote-first and global, we embrace people of different experiences and backgrounds to build diverse teams where every person brings a unique perspective to the software. Engineers at Grafana also have the opportunity to contribute to Open Source communities and collaborate across teams beyond their immediate scope.

What You’ll Be Doing:

The AppCore Stacks squad owns the systems that create, configure, reconcile, migrate, and operate Grafana Cloud stacks at scale. A stack is the customer-facing Grafana Cloud environment that connects an organization to Grafana and the backend services it uses, including Mimir, Loki, Tempo, plugins, dashboards, data sources, and stack-level configuration.

Our work sits at the intersection of product, platform, and operations. We build the control-plane services and workflows that keep stack state aligned across grafana.com, Stack State Service (SSS), Hosted Grafana, cloud regions, and the underlying Grafana Cloud infrastructure. When this domain works well, customers get reliable stack creation, safe configuration rollout, predictable migrations, and fewer manual operational interventions.

Design, build, and operate reconciliation systems, including the SSS backend, to track desired stack state, detect and repair drift across stack templates, grafana.com state, Hosted Grafana, and actual customer stack configuration

Collaborate across SSS, grafana.com, and deployment configurations to ensure stack lifecycle workflows remain reliable, observable, and resilient

Improve operational efficiency by reducing deployment complexity (e.g., aiming for single PR regional SSS deployment) and contributing to the Stack Config Reconciliation project

Manage rollout mechanisms for provisioned plugins, dashboards, data sources, Grafana versions, release channels, and stack-level configuration

Support new region and cluster rollouts, including the operational paths required to bring stacks online safely in new Grafana Cloud regions

Improve incident response and recovery paths for stack misalignment, reconciliation failures, plugin rollout issues, and Hosted Grafana integration failures

Partner with Product, Hosted Grafana, Infrastructure, Support, and adjacent AppCore squads on customer-impacting stack lifecycle work

Contribute to roadmap planning, technical design, OnCall improvements, and long-term simplification of stack operations

You will help own the production behavior of the systems you build. That includes improving runbooks, dashboards, alerts, reconciliation safety, rollout controls, and recovery procedures. You should be comfortable debugging across service boundaries and making careful changes in systems that affect customer stacks

Of course, there is an on-call component to this role and one that we take seriously. As a company, we hire globally (remote-first) to ensure our on-call remains healthy and aligned to approximately 12 daylight hours per day. You will work closely with counterparts in other regions to provide balanced coverage and shared ownership.

We invest heavily in developer productivity. You can use modern AI coding assistants as part of your daily workflow (your choice of tools, within security guidelines), backed by a company-funded usage budget so you can iterate quickly without unnecessary friction.&nbsp;We encourage pragmatic AI-assisted development: faster prototyping, test generation, refactors, documentation, and incident follow-ups—always paired with strong code review and quality standards.&nbsp;You’ll also have access to frontier models (e.g., GPT-Codex 5/3, Claude Opus 4.6, Gemini 3 Pro).

What Makes You a Great Fit:

At Grafana, we actively embrace AI-assisted and agentic development practices, integrating these technologies into both our engineering workflows and the systems we deliver. We encourage our engineers to thoughtfully leverage AI tools to enhance every stage of the lifecycle, from design and implementation to testing, documentation, and operations. We also look for strategic opportunities to embed agentic capabilities within our services to eliminate toil, bolster reliability, and ensure that complex customer workflows remain resilient and safe.

We are seeking a Senior Backend Engineer who thrives on building production systems where correctness, scalability, and operational clarity are paramount. As a remote-first organization, you should be comfortable collaborating asynchronously across time zones and taking full ownership of the critical systems powering Grafana Cloud. Our team is small and operates with a high degree of independence; you will be expected to lead major projects, coordinate across service boundaries, and help define the technical direction for our domain.

You will be particularly successful in this role if you enjoy solving challenges related to stateful systems, eventual consistency, and reconciliation loops. We value engineers who can take ambiguous lifecycle requirements and transform them into explicit, modular solutions. You should be adept at breaking down complex systems work into safe, iterative increments while clearly communicating technical tradeoffs to both internal stakeholders and adjacent product teams.

Some things you might be expected to do could include:

Writing efficient, readable, and easy to maintain code

Designing new microservices or systems

Collaborating with teammates and other departments to reach consensus on proposed solutions

Coordinating with product and UX when needed

Responding to customer requests and feedback

When ready, participating in our follow-the-sun OnCall rotation

Participating in team decisions, such as roadmap planning and prioritization

Requirements:

You have at least 1 year of fully remote work experience

You have worked on a big SaaS platform and dealt with common distributed systems problems (e.g. scalability, multi-tenancy, data isolation, HA, …)

Have professional experience with Golang and be willing to work across both backend service and application code

Care deeply about developer and user experience and the quality of the products that you work on

Have some experience with delivering projects from gathering requirements, and brainstorming ideas to shipping a product to the customer’s hands in a self-driven way

You write clean, robust, well-tested software that other engineers can understand, operate, and maintain

Can take on complex challenges and break them down to achieve tight learning loops: to analyze, design, and build modular solutions, deliver MVPs, gather data and feedback, and then progress iteratively

You are willing to work across teams. Your work has to be aligned with the needs of other squads and external stakeholders. You make your plans transparent, bring stakeholders on board, and are open to feedback and suggestions

Strong Kubernetes experience in AWS, GCP, or Azure, and familiarity with infrastructure-as-code tooling (Helm, Terraform, Jsonnet, etc.)

Experience participating in blameless incident response and writing high-quality post-incident reviews

Bonus Points For:

Experience with TypeScript/Node.js

Experience with Kubernetes control-plane patterns, operators, reconcilers, or desired-state systems

Experience with Jsonnet/Tanka, Terraform, Flux, Argo, or similar deployment/configuration tooling

Experience working on SaaS provisioning, tenancy, regional expansion, plugin rollout, or customer lifecycle systems

Experience with incident response involving configuration drift, partial failure, or cross-service state mismatch

Compensation &amp; Rewards:

In the United States, the Base compensation range for this role is USD 154,445&nbsp;- USD 185,334. Actual compensation may vary based on level, experience, and skillset as assessed in the interview process. Benefits include equity, bonus (if applicable) and other benefits listed here.

All of our roles include Restricted Stock Units (RSUs), giving every team member ownership in Grafana Labs' success. We believe in shared outcomes—RSUs help us stay aligned and invested as we scale globally.

*Compensation ranges are country specific. If you are applying for this role from a different location than listed above, your recruiter will discuss your specific market’s defined pay range &amp; benefits at the beginning of the process.

Why You’ll Thrive at Grafana Labs:

100% Remote, Global Culture -&nbsp;As a remote-only company, we bring together talent from around the world, united by a culture of collaboration and shared purpose.

Scaling Organization – Tackle meaningful work in a high-growth, ever-evolving environment.

Transparent Communication – Expect open decision-making and regular company-wide updates.

Innovation-Driven – Autonomy and support to ship great work and try new things.

Open Source Roots – Built on community-driven values that shape how we work.

Empowered Teams – High trust, low ego culture that values outcomes over optics.

Career Growth Pathways – Defined opportunities to grow and develop your career.

Approachable Leadership – Transparent execs who are involved, visible, and human.

Passionate People – Join a team of smart, supportive folks who care deeply about what they do.

In-Person onboarding - We want you to thrive from day 1 with your fellow new ‘Grafanistas’ to learn all about what we do and how we do it.&nbsp;

Balance is Key - We operate a global annual leave policy of 30 days per annum. 3 days of your annual leave entitlement are reserved for Grafana Shutdown Days to allow the team to really disconnect. *We will comply with local legislation where applicable.

Equal Opportunity Employer: We will recruit, train, compensate and promote regardless of race, religion, color, national origin, gender, disability, age, veteran status, and all the other fascinating characteristics that make us different and unique. We believe that equality and diversity builds a strong organization and we’re working hard to make sure that’s the foundation of our organization as we grow.

Grafana Labs may utilize AI tools in its recruitment process to assist in matching information provided in CVs to job postings. The recruitment team will continue to review inbound CVs manually to identify alignment with current openings.

#LI-Remote

For information about how your personal data is used once you’ve applied to a job, check out our privacy policy.&nbsp;

&nbsp;

---

**[→ Apply](https://job-boards.greenhouse.io/grafanalabs/jobs/5990670004)**
