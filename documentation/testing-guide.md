# Testing Guide

## Purpose

This guide explains how to verify that the workflow is working correctly after setup.

## Test Lead Data

Use the following sample information:

* Name: Mim
* Email: [realrahman12@gmail.com](mailto:realrahman12@gmail.com)
* Business Type: Food
* Budget: 7000

## Testing Steps

### Step 1

Submit a new lead using the Google Form.

### Step 2

Check Google Sheets.

Expected Result:

The lead information should appear in a new row.

### Step 3

Check the Google Sheets Trigger node.

Expected Result:

The workflow should start automatically.

### Step 4

Check the AI Analysis node.

Expected Result:

A lead summary should be generated.

### Step 5

Check Telegram.

Expected Result:

A new lead notification should be received.

### Step 6

Check Gmail.

Expected Result:

A follow-up email should be delivered successfully.

## Final Verification

The workflow is considered successful if all steps above complete without errors.

## Test Status

✅ Passed
