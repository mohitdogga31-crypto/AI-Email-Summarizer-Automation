# AI Email Summarizer Automation

## Overview

This n8n workflow automatically processes incoming emails using AI. The workflow summarizes email content with Google Gemini, categorizes emails into different types, and performs automated actions based on the category.

## Features

* Automatic email monitoring using Gmail Trigger
* AI-powered email summarization using Google Gemini
* Email categorization into:

  * Personal
  * Review
  * Invoice
* Automated email responses for selected categories
* Google Sheets logging for tracking processed emails
* Automatic email management

## Tools Used

* n8n
* Gmail Trigger
* AI Agent
* Google Gemini
* Edit Fields
* Switch Node
* Gmail
* Google Sheets

## Workflow Logic

### Step 1: Receive Email

The Gmail Trigger monitors incoming emails and starts the workflow whenever a new email arrives.

### Step 2: Generate Summary

The AI Agent uses Google Gemini to analyze and summarize the email content.

### Step 3: Process Data

The Edit Fields node formats and prepares the data for further processing.

### Step 4: Categorize Email

The Switch node classifies emails into one of three categories:

* Personal
* Review
* Invoice

### Step 5: Automated Actions

#### Personal Emails

* Send an automated Gmail response
* Store email information in Google Sheets

#### Invoice Emails

* Send an automated Gmail response
* Store email information in Google Sheets

#### Review Emails

* Mark the email as read



## Technologies

* n8n
* Google Gemini AI
* Gmail API
* Google Sheets API

## Benefits

* Reduces manual email processing
* Provides quick AI-generated summaries
* Organizes emails automatically
* Maintains records in Google Sheets
* Saves time through automation

## Author

Mohit Dogga 
