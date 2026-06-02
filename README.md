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

## Workflow Screenshot

![Workflow]<img width="1915" height="968" alt="email-summarizer-workflow png" src="https://github.com/user-attachments/assets/6ac3a42c-bfe5-4b09-8c29-f99fd2112c9a" />
![execution]<img width="1919" height="966" alt="email-summarizer-execution png" src="https://github.com/user-attachments/assets/d52e2e1a-de65-41d7-a2d2-845ef70c61a0" />

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
