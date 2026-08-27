# Lesson 6 – n8n API Resilience Assessment

## Handling API Responses, Errors, and Rate Limits

This repository contains the n8n workflows created for the Lesson 6 LMS assessment.

### Main Workflow

The resilient API integration workflow demonstrates:

- HTTP Request retry configuration
- Continue on Fail behavior
- API pagination
- Safe pagination limits
- Wait-node throttling
- Public test API integration

### Global Error Workflow

A dedicated Error Trigger workflow captures:

- Execution ID
- Workflow ID
- Workflow name
- Failed node
- Error message

### Assessment Evidence

The LMS submission includes the Loom/YouTube demonstration, exported n8n workflow source, screenshots, and supporting documentation.

### Notes

Public test APIs are used for demonstration. The intentional failing endpoint is used to demonstrate Continue on Fail and error handling. Do not commit real credentials, tokens, or other secrets to this repository.
