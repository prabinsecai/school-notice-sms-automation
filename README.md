# School Notice & SMS Automation

An automated school communication workflow built with **n8n, Google Sheets, and the TextBee API** to simplify notice management and SMS notifications.

## Overview

Schools regularly need to share important announcements with parents. Managing recipient lists, preparing messages, and sending updates manually can take time and make tracking difficult.

This project explores a more efficient approach by connecting Google Sheets with n8n and an SMS gateway, creating a structured workflow for managing campaigns and sending school notices.

## How It Works

1. **Campaign Management** — Store campaign details and notice information in Google Sheets.
2. **Contact Management** — Organize recipient records for communication.
3. **Campaign Validation** — Check campaign details and status before processing.
4. **SMS Automation** — Use n8n and the TextBee API to send messages through an Android SMS gateway.
5. **Execution Logging** — Track workflow attempts and results for easier monitoring and troubleshooting.

## Tech Stack

- **n8n** — Workflow automation
- **Google Sheets** — Campaigns, contacts, and execution logs
- **TextBee API** — SMS gateway integration
- **JavaScript** — Workflow logic and data processing
- **HTTP Request / REST API** — Service integration

## Project Structure

```text
.
├── index.html
├── School Notice & SMS Automation System.json
└── README.md
```

- `index.html` — Project case-study webpage
- `School Notice & SMS Automation System.json` — Exported n8n workflow
- `README.md` — Project documentation

## Current Status

**Prototype — Testing in progress**

Test SMS messages have been received. Further work is needed to strengthen delivery-status reconciliation, prevent duplicate messages, improve error recovery, secure credentials, and prepare reliable hosting before production use.

## Future Improvements

- More reliable SMS delivery tracking
- Duplicate-send prevention and recovery handling
- Better campaign reporting and monitoring
- Secure credential management
- Production deployment and operational testing

## Notes

This project is being developed to explore practical automation for school-parent communication. Features and reliability will continue to improve through testing and feedback.

---

*Built with n8n, Google Sheets, and TextBee API.*