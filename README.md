# Hi, I'm Jim de Vries

I'm a senior cloud architect, tech lead, and builder working at the intersection of distributed systems, modern cloud platforms, applied AI, and pragmatic product development.

My core stack is **.NET**, **Azure**, **Kubernetes**, **DevOps/GitOps**, and increasingly **agentic AI**. I like building systems that are technically serious without becoming over-engineered: observable, maintainable, automated where it matters, and designed around real user needs instead of architectural vanity.

I have worked on scalable SaaS platforms, event-driven systems, cloud-native infrastructure, AI-assisted workflows, and developer platforms. My work often sits between infrastructure, backend engineering, product direction, and technical leadership. I enjoy that space: translating messy real-world problems into systems that teams can actually build, operate, and evolve.

My contributions have been recognized through the **TNW T500** and the **Dutch Championships for software development**.

## Current projects

### [Tuesday](https://tuesdayapp.nl)

Tuesday is my main mission-driven project: a non-profit-oriented platform for daily mental support, designed for people in care, recovery, or waiting-list situations.

The goal is to make eHealth feel less like a portal and more like a usable support layer: low-threshold, adaptive, practical, and grounded in the reality of Dutch mental healthcare. Tuesday combines check-ins, state-aware guidance, personal operating models, and AI-assisted support patterns to help people move through difficult days without pretending software can replace human care.

Technically, Tuesday is where many of my interests converge:

- applied AI for real-world support
- state-aware user experiences
- scalable SaaS architecture
- privacy-conscious product design
- accessible mental-health tooling
- pragmatic automation for care workflows

### [TimeKeeper](https://chromewebstore.google.com/detail/timekeeper/afmpffpnhbfcdadpghldeccnjknlmnke)

TimeKeeper is a browser extension that makes timezone differences easier to understand while reading news articles, live blogs, event announcements, and other time-sensitive pages.

It detects recognizable date and time mentions, infers the source timezone from nearby context, and adds an inline conversion to the user’s local or configured timezone. It also includes a manual converter for times copied from outside the browser.

Technically, TimeKeeper is a lightweight, privacy-conscious Manifest V3 extension combining:

- client-side date and time parsing
- timezone inference from abbreviations, offsets, locations, metadata, and page context
- inline conversions directly within article text
- configurable target timezones, date formats, and display styles
- page blacklists and fallback source timezones
- a manual conversion popup
- automated parser, DOM, content-script, and popup tests

TimeKeeper is a small but practical example of building focused browser tooling around a deceptively difficult problem: making global time information understandable without interrupting the reading experience.

### [Kafkaesk](https://github.com/TheAnarchoX/kafkaesk)

Kafkaesk is an OSINT research workbench for structuring public information about right-wing extremism in the Netherlands.

It started from my work around the Dutch antifascist research archive Kafka, but the goal is broader: turn scattered public sources into an evidence-first research environment where articles, feeds, entities, relationships, timelines, claims, and research tasks can be explored without losing sight of source traceability or human review.

Kafkaesk is not meant to be a magic “AI finds extremists” machine. It is deliberately built around a stricter idea: every claim should be connected to source material, every inferred relationship should remain unverified until reviewed, and politically sensitive data should be handled with care. The platform is designed for public-interest research, not doxxing, harassment, or automated accusation.

Technically, Kafkaesk is a full-stack research platform combining:

* responsible sitemap and RSS/Atom ingestion
* robots-aware crawling and source monitoring
* PostgreSQL-backed document storage and search
* entity and relationship extraction with review states
* evidence trails, timelines, and research task workflows
* multi-source querying across scraped and live public sources
* future support for real-time incident workspaces and ML-assisted analysis

For me, Kafkaesk sits at the intersection of activism, OSINT, data engineering, and software architecture: building tools that help researchers make sense of public information while keeping the system accountable, explainable, and careful by design.

### [SectorForge](https://github.com/TheAnarchoX/sectorforge)

SectorForge is a Windows-first, local-first telemetry and race analysis app for sim racing.

It started from a simple frustration: most telemetry tools either feel too clunky, too expensive, too closed, or too disconnected from how sim racers actually want to improve. SectorForge is my attempt to build a better local telemetry stack for games like **F1 25**, **Le Mans Ultimate**, **Assetto Corsa Competizione**, and **Automobilista 2**.

The current architecture combines a native .NET backend, local telemetry collection, SignalR streaming, SQLite session storage, replay flows, and a React/Vite dashboard. The project is also a useful playground for local-first application design, protocol adapters, real-time dashboards, and AI-assisted development workflows.

## What I care about technically

I care about systems that survive contact with reality.

That usually means:

- clear boundaries over accidental complexity
- automation where it removes toil, not where it adds ceremony
- GitOps and infrastructure-as-code for repeatable operations
- strong observability before production pain forces it
- pragmatic security as part of the design, not an afterthought
- event-driven architecture when the domain actually benefits from it
- AI as a force multiplier, not a magic layer sprinkled over bad design

I am especially interested in platforms that combine **distributed systems**, **developer experience**, **human-centered product thinking**, and **AI-driven automation**.

## Tools and ecosystems

I mostly work with:

- **Languages:** C#, TypeScript, Python
- **Backend:** ASP.NET Core, Minimal APIs, SignalR, event-driven services
- **Frontend:** React, Vue/Nuxt, Tailwind, shadcn/ui
- **Cloud & infra:** Azure, Kubernetes, Docker, Terraform, GitHub Actions, ArgoCD
- **Data & messaging:** PostgreSQL, SQL Server, SQLite, Redis, RabbitMQ, NATS
- **AI:** LLM applications, agents, retrieval systems, workflow automation
- **Operating environment:** Windows, WSL2, Linux, JetBrains Rider, VS Code, Neovim

## How I work

I value directness, autonomy, and technical honesty.

I prefer small teams with high trust, clear ownership, and enough taste to avoid both chaos and needless process. I like working across boundaries: helping product people understand technical trade-offs, helping engineers see the product shape, and helping teams build systems they can actually maintain.

I do not believe architecture is a diagramming exercise. Architecture is the set of decisions that make future work easier or harder.

## Open source and software philosophy

I care deeply about freedom, extensibility, and user sovereignty in software.

That does not mean every project has to be permissively licensed or infinitely configurable. It means software should respect the people using it and the people maintaining it. Good systems should be understandable, adaptable, inspectable where possible, and honest about their constraints.

A lot of my personal work explores that idea: tools that people can run locally, adapt to their own workflow, or use as a foundation for something larger.

## Beyond work

Outside of software, I spend a lot of time around music, games, philosophy, sim racing, and creative writing.

I like systems in the broadest sense: racing telemetry, RPG builds, automation workflows, political structures, mental-health support models, and the strange machinery of being human.

## Get in touch

You can find me on **X** at [@TheAnarchoX](https://twitter.com/TheAnarchoX).

I am usually open to discussing distributed systems, applied AI, eHealth, developer tooling, sim-racing telemetry, technical leadership, or serious attempts to build software that matters.
