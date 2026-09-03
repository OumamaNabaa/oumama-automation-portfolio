# Applicant CV Processing & HR Follow-up Automation

## Overview

An AI-powered n8n workflow that automates applicant email processing by validating incoming applications, extracting candidate information from CV documents, and handling HR follow-up communication.

## Workflow Architecture

Gmail Trigger  
↓  
Email Authentication Verification  
↓  
CV Attachment Detection  
↓  
AI CV Information Extraction  
↓  
Candidate Data Validation  
↓  
Duplicate Email Check  
↓  
Automated Follow-up Email  
↓  
Manual Review Handling  


## Features

- Validates incoming applicant emails
- Detects and prioritizes CV attachments
- Extracts candidate information using AI
- Validates extracted email addresses
- Prevents duplicate outreach
- Handles failed cases with manual review


## Technologies

- n8n
- Gmail Integration
- OpenAI API
- JavaScript
- Workflow Automation


## Challenges Solved

- Processing unstructured CV documents
- Extracting reliable candidate information
- Building validation logic
- Creating fallback paths for manual review
- Designing reliable automated communication flows
