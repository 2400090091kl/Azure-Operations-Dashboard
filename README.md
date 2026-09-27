# Azure Operations Dashboard

## VM Health & Performance Monitoring

A centralized Azure monitoring dashboard designed to monitor the health, availability, and performance of an Azure Virtual Machine from one place.

## 🎯 Project Objective

The objective of this project is to build an operational monitoring dashboard that helps users quickly understand the status and performance of an Azure VM.

The dashboard displays important monitoring information such as:

- CPU utilization
- Available memory
- Network traffic
- Disk read and write activity
- Disk operations
- VM availability
- Active metric alerts
- Resource health

## ☁️ Azure Services Used

- Azure Virtual Machine
- Azure Monitor
- Log Analytics Workspace
- Azure Monitor Workbook
- Azure Monitor Agent (AMA)
- Data Collection Rule (DCR)
- Azure Monitor Metric Alerts
- Action Group
- Azure Resource Health

### Tools Used

- Azure CLI
- KQL (Kusto Query Language)
- GitHub

## 🏗️ Architecture

```text
Azure Virtual Machine
        ↓
Azure Monitor Agent
        ↓
Data Collection Rule
        ↓
Azure Monitor / Log Analytics
        ↓
Azure Monitor Workbook
        ↓
Operations Dashboard
| Team Member | Role                            |
| ----------- | ------------------------------- |
| 2400090194  | Azure Infrastructure Engineer   |
| 2400090187  | Data & KQL Engineer             |
| 2400090091  | Workbook & Dashboard Engineer   |
| 2400090189  | UX, Testing & Presentation Lead |
🏁 Outcome

The project provides a centralized operational view of an Azure VM, allowing users to monitor system performance, availability, resource health, and alerts from a single dashboard.
