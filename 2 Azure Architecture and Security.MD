# ☁️ Azure Architecture and Security

- [☁️ Azure Architecture and Security](#️-azure-architecture-and-security)
  - [📐 Understand Azure Architecture](#-understand-azure-architecture)
    - [🌎 Azure Global Infrastructure Overview](#-azure-global-infrastructure-overview)
  - [📁 Azure Active Directory](#-azure-active-directory)
  - [🔒 Azure Security](#-azure-security)
  - [🎯 Conclusion](#-conclusion)

## 📐 Understand Azure Architecture

### 🌎 Azure Global Infrastructure Overview

![Azure Infrastructure](images/azure-topology.jpg)

1. **Geography**: typically a country. Has a boundary, government, and national laws. Contains one or more Azure Regions.
2. **Region**: is a part within the geography. Contains one or more Availability Zones (AZ). When region has >= 3 AZ, it is said to be Availability Zone-enabled. Microsoft may tie regions into a **regional pair**, linked with dedicated low-latency WAN links (<20ms). It facilitates cross-region data replication for High Resiliency. Pairing can be uni (rarer) or bi-directional (because of size).
3. **Availability Zones**: AZ are areas within a region. Its role is to provide redundancy within a region. Dedicated high-performance networks (<2ms). Zonal (< 3 AZ) or zone-redundant replication. Contains 1 or more Datacenters.
4. **Datacenters**: Physical building.

## 📁 Azure Active Directory

## 🔒 Azure Security

## 🎯 Conclusion