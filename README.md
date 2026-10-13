# Awesome-Enterprise-SaaS-Marketplace

# Top Enterprise SaaS Marketplace Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on App Distribution, Extension Registries & Partner Ecosystems*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Enterprise SaaS Marketplaces**. These tools enable organizations to distribute, discover, and manage third-party applications, extensions, and integrations—fostering partner ecosystems and extending platform capabilities.

**Examples** include Salesforce AppExchange, AWS Marketplace, Microsoft Azure Marketplace, Google Cloud Marketplace, ServiceNow Store, HubSpot App Marketplace, Atlassian Marketplace, Workday App Gateway, Shopify App Store, and Zendesk Marketplace (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, vendor-neutral extension registries, and open marketplace infrastructure—ideal for platform teams, ISVs, and developers seeking transparent, vendor-independent marketplace solutions.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Salesforce AppExchange](https://appexchange.salesforce.com/)**  
  The world's leading enterprise cloud marketplace with 7,000+ apps, 1,000+ consulting partners, and 100,000+ peer reviews. Enables ISVs to distribute Salesforce-native applications with security review, managed packaging, and revenue sharing.

- **[AWS Marketplace](https://aws.amazon.com/marketplace)**  
  Digital catalog for finding, buying, and deploying software on AWS. Features SaaS contracts, AMI-based listings, container listings, and private offers. Includes AWS Marketplace Vendor Insights for security and compliance assessment.

- **[Microsoft Azure Marketplace](https://azuremarketplace.microsoft.com/)**  
  Online store for Azure-optimized applications and services. Features virtual machine images, managed applications, SaaS offers, and consulting services. Integrated with Azure Portal for streamlined procurement.

- **[Google Cloud Marketplace](https://cloud.google.com/marketplace)**  
  Catalog for deploying third-party software on Google Cloud. Features Kubernetes apps, SaaS integrations, and VM images. Integrated billing with committed use discounts.

- **[ServiceNow Store](https://store.servicenow.com/)**  
  Marketplace for ServiceNow applications and integrations. Features certified apps, scoped apps, and store app publishing. Supports both free and paid listings with revenue sharing.

- **[HubSpot App Marketplace](https://ecosystem.hubspot.com/marketplace/apps)**  
  Marketplace for HubSpot integrations with 1,500+ apps. Features CRM extensions, marketing tools, and sales enablement apps. Requires app certification for listing.

- **[Atlassian Marketplace](https://marketplace.atlassian.com/)**  
  Marketplace for Jira, Confluence, and other Atlassian products with 5,000+ apps. Features cloud and data center apps, Forge platform, and Connect framework. Supports both free and paid listings.

- **[Workday App Gateway](https://www.workday.com/)**  
  Curated catalog of Workday-approved integrations. Features pre-built connectors, partner applications, and custom API integrations. Requires Workday certification for listing.

- **[Shopify App Store](https://apps.shopify.com/)**  
  Marketplace for Shopify merchants with 8,000+ apps. Features public and custom apps, embedded app SDK, and Shopify Functions for extensibility. Revenue sharing model for paid apps.

- **[Zendesk Marketplace](https://www.zendesk.com/marketplace/)**  
  Marketplace for Zendesk apps and integrations with 1,500+ listings. Features Support, Chat, Guide, and Sell apps. Supports both free and paid listings.

## Open-Source GitHub Projects

- **[Open VSX](https://github.com/eclipse/openvsx)**  
  Vendor-neutral, open-source alternative to the Visual Studio Marketplace (EPL-2.0). Serves 600+ million extension downloads per month across VS Code-compatible tools including Salesforce Code Builder, Google Cloud Workstations, Gitpod, and SAP Business Application Studio. 1.0.0 released June 2026 with read-only mode, TLS-secured Redis, and security hardening. Provides server application, web interface, and CLI publishing tool . Managed Registry available for enterprises needing private extension distribution .

- **[Backstage](https://github.com/backstage/backstage)**  
  Open-source developer portal framework (Apache-2.0) created at Spotify, now a CNCF Incubation project. 30,000+ GitHub stars. Features centralized Software Catalog, Software Templates for golden paths, TechDocs, and a rich plugin ecosystem. Organizations build internal marketplaces of approved tools and services. Zalando's Sunrise portal manages 40,000+ entities with 30 plugins across 27 tools .

- **[ChartMuseum](https://github.com/helm/chartmuseum)**  
  Open-source Helm Chart Repository server (Apache-2.0) written in Go. Supports cloud storage backends including AWS S3, Google Cloud Storage, Azure Blob, Alibaba OSS, Minio, and more. Used by Wikimedia for production Helm chart distribution with multi-region Swift storage and automated chart publishing every 2 minutes. Can serve as addon registry for KubeVela .

- **[OpenTofu Registry](https://github.com/opentofu/registry)**  
  Open-source infrastructure registry (MPL-2.0) for Terraform/OpenTofu-compatible providers and modules. Inspired by Homebrew for easy access. Features search UI at search.OpenTofu.org, provider documentation, module documentation with inputs/outputs/dependencies, and version history. Providers hosted at registry.opentofu.org .

- **[CARE AppStore Registry](https://github.com/ohcnetwork/care_apps_registry)**  
  Open-source App Store for CARE plugins (license varies). Served as static JSON with canonical app definitions in `apps/`. Features generated indexes for featured apps, categories, and developers. Contributors open PRs adding app JSON files aligned with schema. Pre-commit hook auto-generates indexes. CARE fetches canonical app JSON during installation .

- **[Eclipse Open VSX Managed Registry](https://open-vsx.org/)**  
  Enterprise managed version of Open VSX for organizations needing private extension distribution. Same vendor-neutral governance and open-source foundation, with managed hosting and support from Eclipse Foundation .

- **[KubeVela Addon Registry](https://kubevela.io/)**  
  Addon registry system for KubeVela (Apache-2.0) enabling distribution of platform extensions. Can use ChartMuseum or any Helm chart repository as backend. Features addon enable/disable, version management, and dependency resolution .

### Additional Strong Open-Source Options

- **[CNCF Landscape](https://github.com/cncf/landscape)** — Interactive map (Apache-2.0) of cloud native ecosystem with 5,000+ GitHub stars, serving as a discovery layer for open-source projects .
- **[PyPI](https://github.com/pypi/warehouse)** — Python Package Index (Apache-2.0) serving as the canonical registry for Python packages.
- **[npm Registry](https://github.com/npm/cli)** — Node package manager registry infrastructure for JavaScript packages.
- **[Harbor](https://github.com/goharbor/harbor)** — Open-source container registry (Apache-2.0) with vulnerability scanning and role-based access control .
- **[Homebrew](https://github.com/Homebrew/brew)** — Package manager for macOS/Linux with formula and cask distribution infrastructure .
- Community **n8n** workflows for marketplace automation and partner onboarding.

**Frameworks for building custom systems**: Combine **Open VSX** for vendor-neutral extension distribution with **Backstage** for internal developer portal and catalog, **ChartMuseum** for Helm chart registry, **OpenTofu Registry** for infrastructure module distribution, and **Harbor** for container image registry—creating a fully self-hosted, enterprise-grade SaaS marketplace platform.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- SaaS marketplaces handling transactions and partner data must comply with data protection regulations (GDPR, CCPA, etc.) and financial regulations.
- Self-hosted open-source solutions require proper security hardening, supply chain security controls, and ongoing maintenance. Extension registries are popular targets for supply chain attacks—the GlassWorm attack in October 2025 affected both Open VSX and Microsoft's Marketplace .

---

**Made for platform teams, ISVs, partner managers, and developers building transparent marketplace solutions.**  
Let's make Enterprise SaaS Marketplaces more open, data-driven, and interoperable.
