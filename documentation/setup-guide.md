# Setup Guide

## Step 1: Import the Workflow

Download the workflow JSON file from this repository and import it into n8n.

## Step 2: Connect Google Sheets

Replace the Google Sheets credentials with your own account.

Make sure your spreadsheet contains the following columns:

* Name
* Email
* Business Type
* Budget

## Step 3: Connect OpenAI

Add your OpenAI API credentials.

The AI node is used to review lead information and generate a lead summary.

## Step 4: Connect Telegram

Replace the Telegram Bot credentials and Chat ID with your own values.

## Step 5: Connect Gmail

Connect your Gmail account.

The workflow uses Gmail to send automatic follow-up emails.

## Step 6: Test the Workflow

Submit a test lead using the Google Form.

Verify that:

* The lead is stored in Google Sheets
* The workflow runs successfully
* A Telegram notification is received
* A follow-up email is sent

## Expected Outcome

Every new lead should be captured, analyzed, notified, and followed up automatically.
