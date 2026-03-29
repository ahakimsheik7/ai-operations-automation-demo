# AI Operations Automation System

## Overview
This project demonstrates how AI and workflow automation can streamline business operations, specifically in wholesale invoice processing.

It simulates a real-world system where invoice data is processed, structured, stored, and reported automatically using n8n.

---

## Business Problem
Organizations often rely on manual processes to handle invoices and operational data. This leads to:

- repetitive data entry
- slow reporting
- human errors
- lack of real-time visibility

---

## Solution
This project builds an automated workflow that:

- processes invoice data
- converts unstructured content into structured format
- stores results in Google Sheets
- sends real-time email notifications

---

## Workflow Architecture

Manual Trigger  
→ Invoice Data Input  
→ Data Structuring (Mock AI Layer)  
→ Google Sheets (Data Storage)  
→ Gmail (Notification)

---

## Key Features

- Automated invoice data processing
- Structured data pipeline using n8n
- Google Sheets integration for reporting
- Email notification system
- Scalable workflow design

---

## Tech Stack

- n8n (workflow automation)
- Google Sheets (data storage)
- Gmail API (notifications)
- JSON data structuring
- Node-based automation logic

---

## Folder Structure

---

## Example Output

```json
{
  "invoice_id": "WS-INV-2026-0001",
  "vendor_name": "Midwest Auto Supply Co",
  "invoice_date": "2026-03-25",
  "due_date": "2026-04-10",
  "total_amount": "8920.00",
  "currency": "USD",
  "status": "Extracted"
}