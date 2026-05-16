# n8n-event-request-alert-by-zipcode-demo
Demo n8n workflow that saves event requests by ZIP code and sends an alert when enough people request the same area.

# Event Request Alert by Zipcode - Demo

This is a demo n8n workflow.

It collects event requests from a short form.  
It saves the requests in Google Sheets.  
It checks how many people requested an event in the same ZIP code area.  
If 5 or more people request the same area, it sends a Slack alert.

## What it does

1. A person fills out a form.
2. The workflow saves the request.
3. The workflow reads all requests.
4. It removes duplicate requests from the same email and ZIP code.
5. It groups requests by ZIP code prefix.
6. If 5 or more people request the same area, it sends an alert.

## Form fields

- Full Name
- Email
- ZIP Code
- Event Type
- Topic or Question

## Why this could be useful

A community team can see where people want local events.

This can help decide where to test:

- meetups
- workshops
- hack nights
- live build sessions

## Notes

This is demo data only.

The public file does not include real credentials, private links, or real user data.
