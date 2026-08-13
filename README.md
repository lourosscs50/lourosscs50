Lou Carron

Founder & Software Developer building financial systems, platform infrastructure, and production software.

I’m currently building AxleLedger — financial operations and intelligence software for owner-operators and small trucking fleets.

My work spans full-stack development, backend systems, financial data modeling, workflow orchestration, event processing, AI infrastructure, APIs, and modular system architecture.

I approach software with a strong emphasis on clear boundaries, deterministic behavior, testable workflows, operational visibility, and systems that can evolve without losing control.

⸻

🚛 Currently Building — AxleLedger

AxleLedger

AxleLedger is a financial operations platform designed for owner-operators and small trucking fleets.

The product grew from firsthand exposure to trucking operations and the difficulty of answering seemingly simple questions:

* Is this load actually profitable?
* What did the truck really earn this week?
* How much is fuel affecting margin?
* Are fixed costs being fully covered?
* What should a carrier settlement have paid?
* Were deductions applied correctly?
* What financial or operational issue needs attention next?

AxleLedger is being built to turn fragmented trucking records into structured financial intelligence.

Current product areas

* Financial command center and business-performance dashboard
* Load creation, tracking, and profitability visibility
* Diesel and DEF transaction management
* Operating-expense tracking
* Fixed-cost management
* Settlement lifecycle and reconciliation
* Maintenance lifecycle tracking
* Driver, truck, and assignment management
* Reporting-period controls
* Responsive mobile and desktop workflows
* Secure authentication and user-scoped data
* Production deployment

Current product direction

AxleLedger is evolving beyond recordkeeping into a decision and audit platform.

Current and upcoming development includes:

* Profitability & Decision Engine
    Evaluate load economics, break-even points, expected net revenue, fuel requirements, overhead absorption, and Accept / Counter / Decline decisions.
* Document Pipeline
    Process rate confirmations, BOLs, PODs, settlements, fuel receipts, repair invoices, tolls, and other business evidence while preserving document provenance.
* Settlement Audit Engine
    Independently calculate what an owner-operator should have been paid and compare that expected result with the carrier’s actual settlement.
* Exception & Alert Intelligence
    Surface short-payments, abnormal fuel burn, maintenance deadlines, missing documents, profitability issues, reserve concerns, and other operational exceptions.
* AI-Assisted Workflows
    Use artificial intelligence for extraction, reasoning, recommendations, and exception analysis while keeping authoritative financial calculations deterministic.

AxleLedger technology

* Next.js
* TypeScript
* React
* Supabase
* PostgreSQL
* Tailwind CSS
* Vercel

Core architecture principle: AI can assist the system, but it does not become the financial source of truth.

⸻

🧠 Engineering Principles

The systems I build are guided by a few consistent principles:

* Artificial intelligence is a dependency, not the core
* Domain logic should remain authoritative and deterministic
* System boundaries should be explicit
* Detection and orchestration are separate responsibilities
* Business logic should not leak across architectural boundaries
* Important decisions should be observable and explainable
* Reliability should be designed, not assumed
* Test behavior before expanding complexity
* Prefer systems over disconnected scripts
* Preserve provenance when transforming data
* Automate repeatable work without hiding consequential decisions
* Build for change without sacrificing control

Evolution isn’t deviation. It’s convergence.

⸻

🏗 Selected Systems & Architecture Work

Alongside AxleLedger, I build systems focused on orchestration, AI infrastructure, multi-tenancy, event processing, workflow reliability, and platform architecture.

A.I.L. — AI Intelligence Layer

A modular intelligence layer for controlling how AI capabilities are used inside larger software systems.

A.I.L. is designed as infrastructure rather than a chatbot wrapper.

Key areas include:

* Prompt registry and versioning
* Prompt lifecycle management
* AI provider registration and selection
* Provider fallback strategies
* Replaceable agent execution
* Memory storage and retrieval
* Memory filtering and ranking
* Reliability telemetry
* Execution tracing
* Decision explanations
* Repository-backed persistence
* Separation between AI behavior and domain logic

The goal is to make AI usage controlled, replaceable, observable, and explainable.

⸻

ChronoFlow

A workflow orchestration engine for structured execution pipelines.

Designed around:

* Workflow intake
* Validation
* Deduplication
* Routing
* Execution-instance tracking
* Execution history
* Correlation
* Traceability
* Deterministic workflow behavior

ChronoFlow explores how complex workflows can be executed without allowing orchestration concerns to leak into domain systems.

⸻

SignalForge

A rules-based signal detection and alerting platform.

Capabilities include:

* Signal evaluation
* Rule lifecycle management
* Alert creation
* Alert enrichment
* Acknowledgement
* Resolution
* Reopening
* Alert metrics
* Audit history
* Automation triggers
* Decision visibility

SignalForge separates detection from execution, allowing alerts and downstream automation to evolve independently.

⸻

BeaconFlow

An event-ingestion foundation designed for reliable system integration.

Focus areas include:

* Event intake
* Validation
* Processing boundaries
* Reliable integration
* Traceability
* Extensible event handling
* Clean separation between transport and domain logic

⸻

ClientForge

A multi-tenant platform foundation focused on identity and system boundaries.

Core areas include:

* Users
* Tenants
* Authentication
* Authorization
* Tenant isolation
* JWT-based identity
* Multi-tenant application boundaries

⸻

Closeoutflow

A modular closeout workflow platform built around strict lifecycle rules and concurrency guarantees.

Built with:

* ASP.NET Core Minimal APIs
* SQLite
* Swagger / OpenAPI
* xUnit
* GitHub Actions

The project includes contract and concurrency testing designed to prove that duplicate closeout operations cannot create inconsistent state.

⸻

Clip & Cast

A production-oriented media workflow product covering:

* Media assets
* Clips
* Advertising workflows
* Scheduling
* Publishing intent
* Analytics visibility
* YouTube publishing workflows

⸻

🔧 What I Build

My primary areas of engineering interest include:

* Financial software
* Full-stack applications
* Backend services
* REST APIs
* Modular monoliths
* Clean Architecture
* Workflow orchestration
* Event-driven systems
* Artificial intelligence infrastructure
* Multi-tenant platforms
* Authentication and authorization
* Financial data modeling
* Decision-support systems
* Relational database applications
* Integration testing
* Contract testing
* Concurrency guarantees
* Production-focused business software
* Operational and decision visibility

⸻

🛠 Technical Focus

Languages

* C#
* TypeScript
* SQL
* Python
* C++

Application Development

* .NET
* ASP.NET Core
* Minimal APIs
* Next.js
* React
* Tailwind CSS

Data

* PostgreSQL
* Supabase
* Entity Framework Core
* SQL Server
* SQLite

Architecture

* Clean Architecture
* Modular Monoliths
* REST APIs
* Event-Driven Design
* Workflow Orchestration
* Multi-Tenant Systems
* Domain Boundaries
* Financial Data Modeling

Testing & Delivery

* xUnit
* Integration Testing
* Contract Testing
* Concurrency Testing
* GitHub Actions
* Docker
* Git
* GitHub

Systems

* Linux
* Nginx
* SSH
* Networking
* Virtualization
* API diagnostics
* Production troubleshooting

⸻

🖥 Systems & Homelab Development

I use Linux and Windows environments to strengthen the infrastructure knowledge behind the applications I build.

Hands-on areas include:

* Linux command-line administration
* Users and permissions
* Filesystems
* Services and processes
* Nginx configuration
* Networking
* SSH
* Secure file transfer
* Virtualization
* Break/fix exercises
* Application deployment
* Cybersecurity fundamentals
* Cloud and systems concepts

I believe application developers benefit from understanding what happens below the framework layer.

⸻

🎓 Background

I’m currently completing a Bachelor of Science in Computer Science with a concentration in Software Engineering at Southern New Hampshire University.

My path into software also includes extensive firsthand experience in trucking and logistics.

Working in transportation exposed me to the realities of:

* Time-sensitive operations
* Fuel economics
* Equipment costs
* Settlements
* Load profitability
* Operational risk
* Recordkeeping
* Financial uncertainty
* Systems that fail when people need them most

That experience became part of the reason I started building AxleLedger.

Rather than treating trucking and software as unrelated careers, I use my industry experience as domain knowledge for designing technology around real operational problems.

The same mindset carries into my engineering work:

Understand the workflow. Protect the boundaries. Test the behavior. Build systems people can trust.

⸻

📫 Connect

* Portfolio: loucarron.dev
* AxleLedger: axleledger.com
* GitHub: github.com/lourosscs50
* LinkedIn: Lou Carron
* Email: louross101@gmail.com

⸻

⚡ Philosophy

Evolution isn’t deviation. It’s convergence.
