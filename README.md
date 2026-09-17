
# Gmail to Google Sheets Multi-Step Zap

## Overview
Automated workflow that transfers data from Gmail emails labeled "Invoices" 
to a Google Sheets spreadsheet.

## How It Works

### Trigger (Gmail)
- Watches for new emails labeled "Invoices"
- Extracts: Date, Sender, Subject, Body
- Polls every 15 minutes (free plan)

### Action (Google Sheets)
- Creates new row in spreadsheet
- Maps Gmail data to columns: Date, Sender, Subject, Body
- Automatic data logging

## Setup

### Prerequisites
- Zapier account (free trial works)
- Gmail account with "Invoices" label
- Google Sheets access

### Steps Completed
1. ✅ Created Google Sheets with columns: Date, Sender, Subject, Body
2. ✅ Connected Gmail account to Zapier
3. ✅ Configured "New Labeled Email" trigger for "Invoices" label
4. ✅ Connected Google Sheets account
5. ✅ Mapped Gmail data to spreadsheet columns
6. ✅ Tested successfully - row created with sample email data
7. ✅ Turned on Zap - now live!

## Results

### Test Run Successful
- Trigger: Gmail email with "Invoices" label
- Action: Row added to Google Sheets
- Data: Date, Sender, Subject, Body all populated correctly

### Active Status
Zap is currently ON and monitoring for new "Invoices" emails.

## Files

- `zap-editor-screenshot.png` - Full Zap setup showing trigger + action
- `google-sheets-result.png` - Spreadsheet with test data row
- `zap-status-screenshot.png` - Zap status showing it's active

## Zap Details

**Name:** First-Multi-Step-Zap

**Trigger:** Gmail - New Labeled Email
- Label: Invoices

**Action:** Google Sheets - Create Spreadsheet Row
- Spreadsheet: [Your Sheet Name]
- Worksheet: Sheet1
- Columns: Date, Sender, Subject, Body

**Data Mapping:**
- Date ← Date (from Gmail)
- Sender ← From Email (from Gmail)
- Subject ← Subject (from Gmail)
- Body ← Body Plain (from Gmail)

## Public Zap URL
https://zapier.com/shared/first-multi-step-zap/[your-id]

## Automation Benefits
- No manual copying emails to spreadsheet
- Automatic data extraction
- Instant logging of invoice emails
- Reduces manual work by ~20 min/day

## Future Improvements
- Add search step to prevent duplicate rows
- Add filter for specific sender
- Add email notification when row created
- Add delay before creating row (batch processing)

## Author
Mussab Arshad

## Date Created
September 2026
