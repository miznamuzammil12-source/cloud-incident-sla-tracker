# Cloud Support Incident Management and SLA Tracking System

## Overview

Cloud Support Incident Management and SLA Tracking System is an advanced support operations dashboard designed for cloud support, application support, and CloudOps teams.

The system helps support teams track cloud incidents, monitor SLA deadlines, identify breached tickets, manage escalations, analyze root causes, and generate support reports. It simulates a real-world support environment where teams handle production issues, customer tickets, service outages, security incidents, and SLA-based responsibilities.

## Features

- Cloud incident ticket tracking
- SLA deadline monitoring
- SLA status classification
- Priority levels: Low, Medium, High, Critical
- Ticket status tracking
- Escalation queue
- Automated support recommendations
- Team workload analytics
- Incident category analysis
- Root cause analysis
- Average resolution time calculation
- Customer impact tracking
- Downloadable SLA incident report
- Interactive filters by status, priority, team, and SLA status

## Tech Stack

- Python
- Streamlit
- Pandas
- Plotly
- Mock cloud support incident dataset

## Dataset

The dataset contains simulated cloud support incident tickets with:

- Ticket ID
- Created date and time
- SLA due date and time
- Resolved date and time
- Incident title
- Category
- Priority
- Status
- Assigned team
- Customer
- Impact
- Root cause
- Resolution notes

## How It Works

1. Loads cloud incident ticket data.
2. Calculates ticket age and SLA status.
3. Detects tickets that are breached, at risk, critical, or escalated.
4. Displays key support metrics such as active tickets, critical tickets, SLA breaches, and average resolution time.
5. Shows dashboards for ticket priority, SLA performance, incident categories, team workload, and root causes.
6. Creates an escalation queue for urgent tickets.
7. Generates automated support recommendations.
8. Allows users to download the full SLA incident report.

## Project Structure

```text
cloud-incident-sla-tracker/
│
├── app.py
├── generate_incident_data.py
├── requirements.txt
├── README.md
│
├── data/
│   └── cloud_incidents.csv
│
├── reports/
│   └── sample_sla_incident_report.csv
│
├── screenshots/
│
├── portfolio_description.txt
└── cv_description.txt
