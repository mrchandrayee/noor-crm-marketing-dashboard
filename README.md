# Noor — CRM & Marketing Automation Dashboard

[![Live Demo](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-blue?style=for-the-badge&logo=github)](https://mrchandrayee.github.io/noor-crm-marketing-dashboard/)
[![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org) [![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org) [![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](./LICENSE)

A responsive vanilla HTML/CSS/JavaScript recreation of the supplied 16.6-second screen recording.

## Run locally
1. Extract `noor-crm-marketing-dashboard.zip`.
2. Open `index.html` in Chrome, Firefox, Safari or Edge.

No npm install or build step is required.

Optional local server:
```bash
python3 -m http.server 8000
```
Then visit `http://localhost:8000`.

## Screens reconstructed from the video

### Dashboard
- Greeting: “Good afternoon, Noor”
- Audience: 4,862; 318 new in October
- Delivery rate: 94.2%; 312 queued
- Active campaigns: 18 / 40; 6 scheduled
- Credits balance: $1,830
- Messages sent: 128,407
- Monthly messages chart, channel mix, top contacts

### Inbox
- Conversation list with unread, assigned, starred/archive filters
- Contact search and WhatsApp / SMS / Email channel labels
- Conversation thread with message bubbles, assignment, archive and contact actions
- Reply composer adds messages to the local thread

### Campaigns
- Messages sent, average delivery/open rates and contacts reached
- 13 campaign rows with channel, audience, state and progress
- Campaign detail drawer with audience, channel, date, cost, phone message preview and result bars
- Create campaign form

### Automations
- Abandoned cart nudge, New subscriber welcome and Post-purchase follow-up
- Trigger → Wait → Send message → Condition → End of flow visual builder
- Add step, pause/resume and rename actions
- Conversion and conversion-rate summaries

### Reports and Contacts
- Message and channel metrics, campaign performance charts, audience and automation results
- Contacts directory with sample contact data

Also includes left icon rail navigation, collapse control, global search (⌘/Ctrl+K), sync feedback, mobile responsive layout and CSV export for report metrics.

## Visible source extraction note
The recording shows the product UI and screen transitions, not readable full HTML/CSS/JavaScript source code. This is a fresh runnable frontend reconstruction from the visible interface, labels, figures and interactions. The exact original source repository cannot be recovered from the screen recording alone.

## Demo / backend limitations
- All contact, message, campaign and automation data is local sample data.
- Sending messages, sync, campaign creation and automation controls are frontend demos only; no WhatsApp/SMS/email provider or CRM API is connected.
- Forms update in-memory state and reset on page refresh.
- No authentication, database, billing or real contact sync is included.

## 👨‍💻 Author

**mrchandrayee** · [GitHub](https://github.com/mrchandrayee)

## 📄 License

[MIT License](./LICENSE)
