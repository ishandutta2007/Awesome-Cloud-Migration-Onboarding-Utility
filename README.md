# Awesome-Cloud-Migration-Onboarding-Utility

## Top Cloud Migration & Onboarding Utility Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Workload Migration, Data Transfer & Cloud Onboarding Automation*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Cloud Migration & Onboarding Utilities**. These tools help organizations move workloads, databases, mailboxes, and file shares from on-premises or legacy environments into the cloud—covering server replication, application migration, and structured data seeding for development and production environments.

**Examples** include AWS Application Migration Service, Azure Migrate, BitTitan MigrationWiz, Carbonite Migrate, Zerto, Quest Migration Manager, RiverMeadow, Turbonomic, CloudEndure, and Zoho Migrate (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted database migration, email migration, and server-to-server transfer tooling—ideal for system administrators, data engineers, and developers seeking transparent, vendor-neutral migration infrastructure without per-host or per-mailbox licensing surprises.

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---------|-------------|-------------------|--------------------------|
| **[AWS Application Migration Service](https://aws.amazon.com/application-migration-service/)** | Lift-and-shift server migration to AWS with continuous block-level replication. Install replication agent on source servers, launch test/cutover instances in AWS. Free for 90 days (2,160 hours) per server from agent installation [citation:2]. | Free for 90 days per server; thereafter billed hourly per server during active replication. Additional AWS infrastructure (EC2, EBS, data transfer) billed separately [citation:2] | **90-day free tier per source server** (2,160 hours), sufficient for most migrations [citation:2] |
| **[Azure Migrate](https://azure.microsoft.com/en-us/products/azure-migrate/)** | Microsoft's migration hub for discovering, assessing, and migrating on-premises servers, databases, and web apps to Azure. Includes Server Migration, Database Migration, and Web App Migration tools [citation:3]. | Free assessment and migration tooling; pay only for Azure resources consumed (VMs, storage, networking) [citation:3] | Free assessment and planning; Azure consumption costs apply [citation:3] |
| **[BitTitan MigrationWiz](https://www.bittitan.com/)** | SaaS-based mailbox, document, and Teams migration platform. Supports Microsoft 365 tenant-to-tenant, Google Workspace, Exchange, and hybrid migrations. User Migration Bundle covers mailbox, archives, OneDrive, and Google Drive [citation:7]. | Mailbox: €16.31 (up to 50 GB); User Migration Bundle: €20.38 (unlimited data); Public Folders: €142.68 [citation:7] | No permanent free tier; trial licenses available via BitTitan sales |
| **[Carbonite Migrate](https://www.carbonite.com/)** | Server migration and disaster recovery tool for moving physical, virtual, and cloud workloads with minimal downtime. Supports cross-hypervisor and cross-cloud migrations. | From ~$219 one-time (per SelectHub analysis; pricing varies by scope) [citation:5] | No free trial per SelectHub listing; demo available [citation:5] |
| **[Zerto](https://www.zerto.com/)** | Continuous data replication for cloud migration and disaster recovery. Supports VMware, Hyper-V, and Azure VMware Solution with journal-based recovery. Enables test migrations without production impact. | Virtual Replication (1-year): ~$599 per VM; Advanced Resilience (1-year): ~$772 per VM  | Trial available via sales; no self-serve free tier |
| **[Quest Migration Manager](https://www.quest.com/)** | Suite for Microsoft 365, Active Directory, and Exchange migrations. Handles coexistence, directory synchronization, and mailbox migration for enterprise environments. | License + 1-year maintenance: ~$8,531 per license (list price; discontinued June 2026) [citation:10] | Free trial available; no permanent free tier |
| **[RiverMeadow](https://www.rivermeadow.com/)** | Fixed-price cloud migration services and platform capabilities for Azure and AVS onboarding. Covers discovery, assessment, migration, validation, and cutover planning [citation:8]. | Fixed-price service packages (quote via marketplace) [citation:8] | No self-serve free tier; assessment via sales |
| **[Turbonomic (IBM)](https://www.ibm.com/products/turbonomic)** | Application resource management and cloud cost optimization platform. Provides visibility and optimization across AWS, Azure, GCP, Kubernetes, and on-premises infrastructure [citation:6]. | Quote-only (percentage of cloud spend or per managed virtual server) [citation:6] | **30-day evaluation**: unlimited AWS, Azure, GCP accounts, unlimited managed virtual servers [citation:6] |
| **[CloudEndure Disaster Recovery (AWS)](https://aws.amazon.com/cloudendure-disaster-recovery/)** | Continuous replication and automated recovery orchestration for physical, virtual, and cloud servers. Acquired by AWS in 2019; now part of AWS Elastic Disaster Recovery [citation:4]. | ~$0.03 per host/per hour [citation:4] | No free trial listed [citation:4] |
| **[Zoho Migrate](https://www.zoho.com/)** | Migration tools within the Zoho ecosystem for email, calendar, contacts, and CRM data. Supports Google Workspace, Microsoft 365, and direct CRM API migrations from Pipedrive, HubSpot, and Insightly [citation:1][citation:14]. | Included with Zoho Workplace/CRM subscriptions | Migration wizard included; trial via Zoho signup |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Bani](https://github.com/banilabs/bani)** | [![Stars](https://img.shields.io/github/stars/banilabs/bani?style=social&color=white)](https://github.com/banilabs/bani/stargazers) | Open-source database migration engine powered by Apache Arrow. Migrates schema, data, and indexes across PostgreSQL, MySQL, MSSQL, Oracle, and SQLite. Declarative BDL config, Python SDK, CLI, and MCP server for AI agents [citation:12]. |
| **[vps-backup-sync](https://github.com/cash602-cmd/vps-backup-sync)** | [![Stars](https://img.shields.io/github/stars/cash602-cmd/vps-backup-sync?style=social&color=white)](https://github.com/cash602-cmd/vps-backup-sync/stargazers) | Zero-dependency VPS backup and server migration tool. Full-stack backup (website dirs + MySQL/MariaDB/PostgreSQL auto-detection), resume-supported rsync over SSH, SHA256 integrity verification, and direct server-to-server migration. MIT licensed [citation:11]. |
| **[imap-migration-tools](https://github.com/bani-tools/imap-migration-tools)** | [![Stars](https://img.shields.io/github/stars/bani-tools/imap-migration-tools?style=social&color=white)](https://github.com/bani-tools/imap-migration-tools/stargazers) | Python scripts for IMAP email migration with OAuth2 support, Gmail mode (All Mail + labels), parallel threads, and delete-from-source option. Includes compare and count utilities for validation [citation:13]. |

### Additional Strong Open-Source Options

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[pgloader](https://github.com/dimitri/pgloader)** | [![Stars](https://img.shields.io/github/stars/dimitri/pgloader?style=social&color=white)](https://github.com/dimitri/pgloader/stargazers) | PostgreSQL-focused data loading and migration tool. Migrates from MySQL, SQLite, MS SQL, and CSV to PostgreSQL with schema conversion and parallel loading. |
| **[Flyway](https://github.com/flyway/flyway)** | [![Stars](https://img.shields.io/github/stars/flyway/flyway?style=social&color=white)](https://github.com/flyway/flyway/stargazers) | Database schema migration and seeding tool. Version-controlled SQL migrations across PostgreSQL, MySQL, Oracle, SQL Server, and more. |
| **[Apache NiFi](https://github.com/apache/nifi)** | [![Stars](https://img.shields.io/github/stars/apache/nifi?style=social&color=white)](https://github.com/apache/nifi/stargazers) | Dataflow automation and migration tool with visual interface. Supports routing, transformation, and mediation between systems with provenance tracking. |

**Frameworks for building custom systems**: Combine **Bani** for cross-database migration with Arrow-based throughput, **vps-backup-sync** for server-to-server file and database transfer, and **imap-migration-tools** for email migration—creating a fully self-hosted migration utility stack without per-host or per-mailbox licensing.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Migration tools handle sensitive production data; enforce encryption in transit, least-privilege source credentials, and audit logging for all migration jobs.
- Pricing models vary widely (per-server, per-mailbox, per-VM, custom quote); model total cost against actual data volume and cutover timeline before committing. AWS Application Migration Service's free tier is time-limited per server—ensure cutover completes within 90 days to avoid replication charges.

---

**Made for system administrators, data engineers, migration architects, and developers building data movement infrastructure.**  
Let's make cloud migration and onboarding more open, verifiable, and cost-predictable.
