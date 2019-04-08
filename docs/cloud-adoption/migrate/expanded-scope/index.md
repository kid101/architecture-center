---
title: "CAF: Cloud migration expanded scope checklist"
description: Cloud migration expanded scope checklist
author: BrianBlanchard
ms.date: 4/4/2019
---

# Expanded scope for cloud migration

The [baseline migration guide](../baseline-migration-guide/overview.md) in the Cloud Adoption Framework is the suggested starting point for readers who are interested in a re-host migration to Azure, also known as a Lift and Shift migration. That guide will walk the reader through a series of prerequisites, tools, and approaches to migrating virtual machines to the cloud.

While the [baseline migration guide](../baseline-migration-guide/overview.md) is effective at getting the reader familiar with this style of migration, it is based on a number of assumptions. Those assumptions ensure that the guide aligns to a large percentage of the readers of the Cloud Adoption Framework, by providing a simplified approach to migrations. This section of the Cloud Adoption Framework addresses a number of scope changes, which could help guide efforts when those assumptions do not apply.

## Cloud migration expanded scope checklist

The following checklist outlines the common areas of complexity which could require the scope of the migration to be expanded beyond the [baseline migration guide](../baseline-migration-guide/overview.md).

- **Business-driven scope changes**
    - [Balancing the portfolio](./balance-the-portfolio.md)
    - [Support global markets](./multiple-regions.md)
- **Culture-driven scope changes**
    - Change management and approval processes *(Coming Summer 2019)*
    - Executive readiness *(Coming Summer 2019)*
    - [Skills readiness](./skills-readiness.md)
    - Aligning support (Partner, services, and support) *(Coming Summer 2019)*
- **Technical Strategy-driven scope changes**
    - Existing data center constraints *(Coming Summer 2019)*
    - Migrating at scale - High volume or velocity of migrations *(Coming Summer 2019)*
    - [Multiple data centers](./multiple-data-centers.md)
    - Change management and solution documentation *(Coming Summer 2019)*
    - [Governance or compliance strategy](./governance-or-compliance.md)
- **Workload-specific scope changes**
    - Architect workloads for resiliency *(Coming Summer 2019)*
    - Align migration to application patterns *(Coming Summer 2019)*

If any of these complexities align with the reader's scenario, then this section of the Cloud Adoption Framework will likely provide the type of guidance needed properly align scope in the migration processes.

Each of these scenarios is addressed by the various articles in this section of the Cloud Adoption Framework.

## Scope options explained

The following expand on the short checklist above to aid the reader's understanding of each scope expansion. These brief statements are designed to add clarity beyond the brief titles above.

### Business-driven scope changes

- **Balancing the portfolio:** The cloud strategy team is interested in investing more heavily in migration or innovation. Often times a balance between the two priorities is the key to success. In this guide, the topic of balancing the cloud adoption portfolio is a common topic, addressed in each of the migrate processes.
- **Support global markets:** The business operates in multiple geographic regions with disparate data sovereignty requirements. To meet those requirements, additional considerations should be factored into the prerequisite review and distribution of assets during migration.

### Culture-driven scope changes

- **Change management and approval processes:** When the culture is complex, highly matrixed, or siloed the processes related to change management and approvals becomes challenging. Guidance on managing this complexity can be found in assess, migrate, and optimize processes.
- **Executive readiness:** Proper levels of executive support and leadership are critical to the success of a migration effort. If the executive team is not ready to engage, then support is unlikely to follow. This complexity is addressed during the prerequisite and assess processes.
- **Skills readiness:** When the Cloud Adoption Team or other supporting teams are not ready to execute, it can quickly inject complexity throughout the migration effort. This challenge is addressed during each of the migration processes in a specific page on skills readiness.
- **Aligning support (Partner, service, and support options):** Within each of the the processes outlined, there are ways in which a partner, services from the cloud vendor, and/or support from the cloud vendor can aid in execution. In each of the processes sections a page on support alignment will discuss the options further.

### Technical Strategy-driven scope changes

- **Existing data center constraints:** Often times companies choose to migrate to the cloud because the capacity, speed, and stability of an existing data center is no longer satisfactory. Unfortunately, those same constraints add complexity to the migration process, requiring additional planning during the assessment and migration processes.
- **Migrating at scale:** Migrations exceeding 2,000 assets are likely to run into constraints that require additional planning and a disciplined approach to execution. The Assess and Migrate processes are adjusted to account for scale complexity.
- **Multiple data centers:** Migration of multiple data centers adds a great deal of complexity. During Assess, Migrate, Optimization, and Manage processes, additional considerations will be discussed.
- **Change management and solution documentation:** Large digital estate inventories, complex solution architectures, long standing technical debt, and interdependencies can create a complexity that should be addressed during assess, migrate, and optimize processes.
- **Governance or compliance strategy:** When governance and compliance are vital to the success of a migration, additional alignment between IT Governance teams and the Cloud Adoption team is required.

### Workload-specific scope changes

- **Architect workloads for resiliency:** Common cloud design principles can help prepare mission-critical workloads for improved resiliency. This article will explain the impact on a migration process when resiliency is a workload requirement. It also shares a few common principles to include in the general environment configuration to improve resiliency for the environment.
- **Align migration to application patterns:** The migration pattern of a workload can affect the migration path chosen. This article outlines a few scope changes that would be integrated into the work item level of a migration backlog to reflect different approaches to migration per workload.

## Next steps

Browse the TOC to the left to address specific needs or scope changes. Alternatively, the first scope enhancement on the list, [Balancing the Portfolio](./balance-the-portfolio.md) could be a good enhancement to review first.

> [!div class="nextstepaction"]
> [Balancing the Portfolio](./balance-the-portfolio.md)