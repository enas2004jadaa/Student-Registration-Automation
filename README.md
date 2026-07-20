# Student-Registration-Automation
Automated student registration workflow built with n8n. Validates form submissions using JavaScript and stores accepted or rejected applications in Google Sheets.

Overview

This project automates student registration using n8n.

It validates submitted student information, determines whether the application meets predefined rules, and stores the results in Google Sheets.

Features

Student registration form
JavaScript validation
Name validation
Age validation
Acceptance/Rejection status
Validation reason generation
Google Sheets integration
Automatic data logging

Validation Rules

The workflow verifies:

Student name contains at least 3 characters
Student age is between 10 and 18 years old

If validation fails, the workflow records the rejection reason.

Technologies
n8n
JavaScript
Google Sheets
Form Trigger

Workflow

Student submits the registration form.
JavaScript validates the submitted data.
Workflow determines whether the submission is Accepted or Rejected.
Validation reason is generated.
Results are stored automatically in Google Sheets.

Skills Demonstrated

Workflow Automation
JavaScript
Data Validation
Form Processing
Google Sheets Automation
Low-Code Development
Business Process Automation

Notes

Sensitive credentials and spreadsheet identifiers have been removed for security purposes.
