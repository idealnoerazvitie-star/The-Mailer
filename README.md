# The Mailer

A calm, responsive, local-first email interface demo with its own visual identity.

## Run it

Open `index.html` in a browser, or serve this folder locally:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## What works

- Inbox, starred, snoozed, sent, archive, spam, trash, and drafts folders
- Search across sender, address, subject, body, preview, and labels
- Open and read messages, mark read/unread, star, archive, trash, report spam, and snooze
- Multi-select and bulk actions; create and apply labels
- Compose, reply, forward, autosave drafts, discard drafts, and a local Sent folder
- Sort order, refresh, light/dark theme, help, and account information dialogs
- Responsive layout, keyboard focus support, and `Ctrl/Cmd + K` search shortcut
- Mail and preferences saved in browser local storage

## Important limitations

This is a static front-end prototype. It does **not** have a real server, user accounts, synchronized mailboxes, or an email delivery service. Sent messages and attachments are not transmitted; sending only saves a local copy to Sent and displays a notice. Data is stored in this browser and can be removed by clearing site data. Do not use it for sensitive information.
