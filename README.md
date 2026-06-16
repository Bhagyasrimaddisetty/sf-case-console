Set-Content -Path "README.md" -Value @'
# Salesforce Case Management Console

A Lightning Web Component (LWC) built on Salesforce Developer Edition that displays a real-time case management dashboard inside the Sales app.

## Screenshot
(Screenshot%2026-06-16%111424.png)

## Features
- Live case data table using lightning-datatable
- Columns: Case Number, Subject, Status, Priority, Created Date
- Apex controller with SOQL query ordered by date
- Deployed via Salesforce CLI to a Developer Edition org
- Added to Lightning Experience via App Builder

## Tech Stack
- Lightning Web Components (LWC)
- Apex (CaseController.cls)
- Lightning Design System (LDS)
- Salesforce CLI (sf)
- SFDX Project Structure

## Setup
1. Install Salesforce CLI from https://developer.salesforce.com/tools/salesforcecli
2. Authorise your org: sf org login web --alias myorg
3. Deploy: sf project deploy start --target-org myorg --api-version 59.0
4. Open: sf org open --target-org myorg --path /lightning/n/Case_Console

## Built By
Maddisetty Bhagya Sri — Salesforce Developer Intern, SmartBridge and Salesforce, 2025
'@
