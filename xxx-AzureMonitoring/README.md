# What The Hack - Azure Monitor v2.0

## Introduction

The Azure Monitoring v2.0 What the Hack (WTH) provides hands on experience on how to monitor Azure workloads using Azure Monitor, Log Analytics, Insights, Workbooks and Grafana. This hack was designed specifically for Infrastructure engineers, DevOps engineers, administrators and IT architects who want to build their knowledge on Azure Monitor. However, anyone with a passion around Monitoring is welcome!  

![Hack Intro](./Images/header.png) 

## Learning Objectives

In this hack, you will be getting hands on experience with monitoring resources (VMs, applications, containers) using Azure Monitoring capabilities such as log analytics, dashboards, and KQL. Additionally, Grafana has been introduced to add additional visualization tools.

## Challenges

- Challenge 1: **[Getting Started](Student/Challenge-01.md)**
- Challenge 2: **[Alerts, Activity Logs and Service Health](Student/02-Alerts-Activity-Logs-And-Service-Health.md)**
- Challenge 2: **[Monitoring Basics and Dashboards](Student/03-Monitoring-Basics-And-Dashboards.md)**
- Challenge 3: **[Azure Monitor for Virtual Machines](Student/04-Azure-Monitor-For-Virtual-Machines.md)**
- Challenge 5: **[Azure Monitor for Applications](Student/05-Azure-Monitor-For-Applications.md)**
- Challenge 6: **[Azure Monitor for Containers](Student/06-Azure-Monitor-For-Containers.md)**
- Challenge 7: **[Log Queries with KQL and Grafana](Student/07-Log-Queries-With-KQL-And-Grafana.md)**
- Challenge 8: **[Visualizations](Student/08-Visualizations.md)**

## Technologies

- Azure Monitor
- KQL
- Grafana

## Prerequisites

1. Please review the following docs before or during the event when necessary

    - [View and Manage Alerts in Azure Portal](https://docs.microsoft.com/en-us/azure/azure-monitor/platform/alerts-metric#view-and-manage-with-azure-portal)
    
    - [Create metric alerts with ARM templates](https://docs.microsoft.com/en-us/azure/azure-monitor/platform/alerts-metric-create-templates)
    
    - [Send Guest OS metrics to the Azure Monitor metric store](https://docs.microsoft.com/en-us/azure/azure-monitor/platform/collect-custom-metrics-guestos-resource-manager-vm)

    - [Get Started with Metrics Explorer](https://docs.microsoft.com/en-us/azure/azure-monitor/platform/metrics-getting-started)

    - [Create Action Rules](https://docs.microsoft.com/en-us/azure/azure-monitor/platform/alerts-action-rules)

    - [Monitor your Kubernetes Cluster](https://docs.microsoft.com/en-us/azure/azure-monitor/insights/container-insights-analyze)

    - [View Kubernetes logs, events, and pod metrics in real-time](https://docs.microsoft.com/en-us/azure/azure-monitor/insights/container-insights-livedata-overview)

    - [Start Monitoring Your ASP.NET Core Web Application](https://docs.microsoft.com/en-us/azure/azure-monitor/learn/dotnetcore-quick-start)

    - [What does Application Insights Monitor](https://docs.microsoft.com/en-us/azure/azure-monitor/app/app-insights-overview#what-does-application-insights-monitor)

    - [Grafana Integration](https://grafana.com/grafana/plugins/grafana-azure-monitor-datasource)

    - [Create interactive reports with workbooks](https://docs.microsoft.com/en-us/azure/azure-monitor/app/usage-workbooks)

2. Attendees have access to an Azure Subscription where they can each deploy the provided ARM template that will build a very detailed infrastructure to monitor.  This includes the Vnet, subnets, NSG(s), LB(s), NAT rules, scales set and a fully functional .NET Core Application (eShopOnWeb) to monitor.
3. Attendees should have a level 200-300 understanding of the Azure platform.  Understand concepts like PowerShell, Azure Cli, ARM, resource groups, RBAC, network, storage, compute, scale sets, virtual machines and security.  Previous experience working with ARM templates is recommended.
4. Access to a machine with Visual Studio Code and the Azure PowerShell Modules loaded or Azure CLI. VS Code ARM and PowerShell extensions should be configured.
