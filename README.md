# Awesome-Usage-Based-Billing-Platform

## Top Usage-Based Billing Platforms Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Metering, Usage-Based Pricing, Event Ingestion, Hybrid Billing, Invoicing & Revenue Infrastructure*  

**Last updated: August 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Usage-Based Billing**. These tools ingest high-volume usage events, apply flexible pricing models (pay-as-you-go, tiers, commitments, credits), generate invoices, and support modern SaaS, API, AI, and cloud monetization strategies.



**Examples** include Metronome, m3ter, Sequence, Amberflo, Zenskar, Lago, Orb, BillingPlatform, Ordway, Togai, Gotransverse, Chargebee, and Kill Bill (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for metering, usage-based billing engines, subscription platforms, and related open tools — ideal for engineering teams, AI/cloud companies, and organizations seeking full data ownership, self-hosting, and freedom from revenue-share pricing models.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Metronome](https://metronome.com/)**  

  Enterprise-grade usage-based billing platform specializing in high-volume metering, complex contracts, commitments, credits, and real-time rating (now closely integrated with Stripe).



- **[m3ter](https://m3ter.com/)**  

  Usage metering and billing platform focused on accurate event aggregation, flexible pricing, and revenue operations (acquired/integrated with Salesforce ecosystem).



- **[Sequence](https://www.sequencehq.com/)**  

  Modern billing infrastructure for usage-based and hybrid pricing models with strong developer experience.



- **[Amberflo](https://www.amberflo.io/)**  

  Cloud-native metering and usage-based billing platform designed for real-time usage tracking and flexible monetization.



- **[Zenskar](https://www.zenskar.com/)**  

  Usage-based billing and revenue management solution supporting complex pricing and invoicing workflows.



- **[Orb](https://www.withorb.com/)**  

  Developer-friendly usage-based billing platform with powerful metrics, real-time visibility, and flexible pricing simulation (now part of the Adyen ecosystem).



- **[BillingPlatform](https://billingplatform.com/)**  

  Enterprise billing and revenue management system supporting usage, subscription, and hybrid models.



- **[Ordway](https://ordwaylabs.com/)**  

  Revenue and billing platform with strong support for usage-based and recurring revenue scenarios.



- **[Togai](https://www.togai.com/)**  

  Metering and usage-based pricing engine focused on flexible event processing and billing automation.



- **[Gotransverse](https://www.gotransverse.com/)**  

  Enterprise billing platform capable of handling complex usage, subscription, and hybrid pricing at scale.



- **[Chargebee](https://www.chargebee.com/)**  

  Popular subscription billing platform that also supports metered/usage-based charges and hybrid pricing models.



- **[Kill Bill (Cloud / Hosted options)](https://killbill.io/)**  

  Hosted and commercial offerings built on the open-source Kill Bill subscription and billing platform.



## Open-Source GitHub Projects



- **[Lago](https://github.com/getlago/lago)**  

  Leading open-source metering and usage-based billing platform supporting event ingestion, flexible pricing (subscription + usage + hybrid), invoicing, entitlements, and payment orchestration. Fully self-hostable.



- **[Kill Bill](https://github.com/killbill/killbill)**  

  Mature open-source subscription billing and payments platform with extensive plugin architecture, analytics, and support for complex recurring and usage scenarios.



- **[BillRun](https://github.com/BillRun/system)**  

  Open-source enterprise billing and rating system designed for high-volume usage (originally telecom/CDR-focused) with real-time processing, mediation, and invoicing capabilities.



- **[Lago API & Front-end Components](https://github.com/getlago)**  

  Core API, front-end, SDKs, and Helm charts that make up the complete Lago open-source billing stack.



- **[OpenMeter](https://github.com/openmeterio/openmeter)**  

  Open-source usage metering and event aggregation platform that pairs well with billing engines for accurate consumption tracking.



- **[Meteroid / similar metering projects](https://github.com/)**  

  Emerging open-source metering and usage-tracking tools focused on developer-friendly event pipelines.



- **[Flexprice / Autumn-style open billing experiments](https://github.com/)**  

  Community and early-stage open-source projects exploring flexible pricing and usage-based invoicing.



- **[Custom Rating Engines & Event Processors](https://github.com/)**  

  Open-source libraries and frameworks for building custom usage aggregation, rating, and invoice generation pipelines.



- **[Stripe Billing + Open Components](https://github.com/)**  

  While Stripe itself is proprietary, many open-source tools and examples extend or integrate with usage-based billing flows.



- **[Invoice & PDF Generation Libraries](https://github.com/)**  

  Open-source tools commonly paired with metering engines to produce professional invoices and statements.



- **[Payment Orchestration & Dunning Tools](https://github.com/)**  

  Open-source components for retries, dunning, and multi-gateway payment handling that complement usage-based systems.



- **[Revenue Analytics Dashboards](https://github.com/)**  

  Open-source analytics projects that visualize usage, MRR, and revenue metrics from billing data.



### Additional Strong Open-Source Options



- **Primary platforms**: Lago (most complete modern usage-based solution) and Kill Bill (mature subscription + extensibility).

- **High-volume rating**: BillRun for telecom-style or high-throughput usage scenarios.

- **Metering layer**: OpenMeter and similar event aggregation tools.

- **Supporting stack**: Self-hosted databases, message queues (Kafka, etc.), and invoice generators.

- Many internal and community **usage metering** and **hybrid billing** implementations continue to appear on GitHub.



**Frameworks for building custom systems**: Combine **Lago** (or Kill Bill) as the core billing engine, an open metering layer for event ingestion, payment gateway integrations, and analytics tools to create a fully self-hosted, transparent usage-based billing platform.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Usage-based billing systems handle financial transactions and customer usage data; they must comply with tax, revenue recognition (ASC 606 / IFRS 15), and data privacy requirements.

- Self-hosted open-source solutions require careful attention to event accuracy, idempotency, audit trails, and operational reliability at scale.



---



**Made for SaaS founders, AI/cloud companies, billing engineers, and revenue teams.**  

Let's make usage-based billing more open, flexible, and under your control.
