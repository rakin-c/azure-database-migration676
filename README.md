# Azure Database Migration
## Introduction
Cloud migration is the process of migrating IT resources from physical servers and computing facilities to cloud architechture. As a business or other organization grows, it may be beneficial to transfer data from local data centres to the cloud for a variety of reasons:
- Cloud infrastructure is easily scalable to meet demands,
- Cost reduction - no need for physical infrastructure and in-house IT staff,
- Easy disaster recovery via geo-replication and failover groups,
- High reliability and uptime.

A database hosted in the cloud can offer increased flexibility and efficiency while keeping costs low.

This project aims to migrate a Microsoft SQL Server database hosted on an Azure virtual machine to an Azure SQL Database. The database will be backed up, and regularly snapshots will be saved to Azure Blob Storage to provide an additional layer of redundancy.

A crucial step is simulating a disaster recovery scenario, where critical data is lost or corrupted and the database needs to be restored from a backup. This is to ensure data can be recovered in the event of destruction or corruption.

To supplement this, geo-replication will be implemented as an additional safety net and to ensure availability when the database is undergoing planned maintenance or unexpected conditions. Microsoft Entra ID will be integrated to define access roles, adding extra control and protection.

This project is part of the AiCore Cloud Engineering Pathway.

Tools used: Microsoft Azure (VMs, SQL Database, Blob Storage, Database Migration Service), Microsoft SQL Server, SQL Server Management Studio, Azure Data Studio, Microsoft Entra ID.

## Steps Taken
1. [Production Environment Setup](#1-production-environment-setup)
2. [Migration to Azure SQL Database](#2-migration-to-azure-sql-database)
3. [Data Backup and Restoration](#3-data-backup-and-restoration)
4. [Disaster Recovery Simulation](#4-disaster-recovery-simulation)
5. [Geo-Replication and Failover](#5-geo-replication-and-failover)
6. [Microsoft Entra ID Integration](#6-microsoft-entra-id-integration)

### 1. Production Environment Setup

https://www.microsoft.com/en-GB/sql-server/sql-server-downloads
https://learn.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms?view=sql-server-ver16

### 2. Migration to Azure SQL Database
https://www.microsoft.com/en-us/download/details.aspx?id=39717

### 3. Data Backup and Restoration

### 4. Disaster Recovery Simulation

### 5. Geo-Replication and Failover

### 6. Microsoft Entra ID Integration
