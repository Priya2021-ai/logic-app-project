# logic-app-project
# Azure Logic App Project

## Overview
This project demonstrates how to trigger an Azure Data Factory pipeline using an Azure Logic App.

The Logic App is designed to receive an HTTP request and automatically start a pipeline run.

---

## Architecture

HTTP Request ➝ Logic App ➝ Azure Data Factory Pipeline

---

## Components Used

- Azure Logic App
- Azure Data Factory
- HTTP Trigger
- ARM Template (template.json)

---

## Files

- template.json → Contains Logic App configuration (exported ARM template)

---

## How It Works

1. Logic App listens for an HTTP request
2. When request is received → trigger fires
3. Logic App calls Azure Data Factory
4. Pipeline execution starts automatically

---

## Use Case

- Automating data pipelines
- Triggering workflows from external systems
- Event-based data processing

---

## Deployment

You can deploy this Logic App using the ARM template:

- Upload template.json in Azure
- Deploy via Azure Portal or CLI

---
