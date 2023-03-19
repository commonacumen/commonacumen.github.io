---
title: "Data Mesh Architecture: Extend an existing operational COTS application using cloud-based HA/DR to build analytics platforms"
date: 2023-03-18T16:10:30-04:00
categories:
  - blog
tags:
  - architecture
---

## Abstract

Data Mesh seems most aligned with principles dirived from Cloud Native Apps and Microservices. What about existing applications and databases?  Can you embrace Data Mesh fundamentals to extend an existing operational Commercial off-the-shelf (COTS) application using cloud-based High Availability and Disaster Recovery (HA/DR) features to replicate operational databases and build analytics platforms?  How can a source-alligned data domain that is not custom built feed into your data architecture? It a buy vs build world that is never a green field.

## Introduction
Organizations have many COTS and custom built apps that are backed by relational database management systems (RDBMS) from commerial vendor products like Microsoft SQL Server, and Oracle Database, as well as open source RDBMS like PostgreSQL, and MySQL.  I am going to focus on SQL Server and Oracle in this post and look at using HA/DR capabilities and architectures not only for business continuity, but to support read-only secondary replicas for analytical purposes.  I will also focus on Azure examples but their is not reason these ideas can not be used in on premise data centers as well as in public cloud datacenters like Amazon Web Services (AWS), Goggle Cloud Platform (GCP), and Oracle cloud infrastructure (OCI).  In fact these could be hybrid scenarios where the primary application and database are on premise and the secondary application and database is on a public cloud.  Or where two Azure availability zones are used for failovers and another Azure region are used for an analytical read-only secondary.

## SQL Server and Azure SQL Managed Instance

![sqlmilink](https://phx02pap001files.storage.live.com/y4mgXmo4zvINHp-Ky9yHeRALox7emgiLDjgx1DfOspkS8YrjFS8YC_c85q4W8sr8DCeCkjRn1ojgSkX0pmWbE5JljuhoSylGzpfat45VrZEIrOUVFuhsAPtZgORQXxx4KNzpe52N60JmfDRhXNRtwA9yySN7ZNuADnyeWqIEWVZWjZJQ7IxcWOe8hfeJIL2ERCl?width=990&height=549&cropmode=none)


## Oracle Database and Oracle Active Data Guard

![oracledataguard](https://phx02pap001files.storage.live.com/y4mxi04-JfAMkyoSGfDBBg3thKdrrdT8rOso9AkMLzcxrEhzc4WE4zhG-HS0M1dCTMyRjR8oqMCPzfN8rAlZzTvFKK877EbjxuZUTvAsa8H5VOMC7JAtOLIDALj6uRUkdGTaeOshvlZf8V4o21vdRqzDv9Xq8JgdM2D5mjwsWGC8sNAmXK-ObySlR2bnmvXQ_6G?width=987&height=546&cropmode=none)

## Azure Data Factory Change Data Capture (CDC)

Take a look at Mark Kromer's demo of the the CDC feature in Azure Data Factory [Change data capture resource overview](https://learn.microsoft.com/en-us/azure/data-factory/concepts-change-data-capture-resource)

Or checkout `Change Data Capture and Managed Airflow in Azure Data Factory | Azure Friday`

{% include youtube.html id="GaWlhlReoA8" %}

### ADF CDC

![adfcdc](https://phx02pap001files.storage.live.com/y4mbh6lkungQGXWYB05oe5gjKvNltwNCcMkuTmQxGCc0G0RzYDWGmXDuj6-pvkjL-e7-S_h25cdpjw2dTQAd9c7ViimkuUN1qPS5h4-s_q-zkjrZQRHojzHVChJOdW4Nexu5ayU6LXSEsdu_IHjMcOvOdZhC5Q77s1-gmHS_Wciijqk9QlSBqrd-0p1oom_RkZL?width=1433&height=501&cropmode=none)

