# Renou

Renou is a personal relationship manager for iPhone. This plugin connects Claude to your Renou network and teaches it four everyday workflows, so staying in touch takes a sentence instead of an app session.

## What you can do

- **Create and update contacts.** "Add Alex Morgan from Acme." Then "Save Alex’s birthday as April 12, 1998."

- **Log a catch-up in one line.** "Had coffee with Marcus, we talked about his seed round." Claude finds Marcus, logs it and tells you the next check-in date.
- **Get a brief before a meeting.** "Brief me on Sarah before my call." You get her role, what you talked about last, open promises and two openers.
- **See who to reconnect with.** "Who should I reach out to this week?" You get the people who are overdue, upcoming birthdays and a one-line opener for each.
- **Draft a follow-up.** "Write Elena a follow-up about the candidates." Claude drafts it from your notes. Renou never sends messages for you.

## Set up

1. Install the plugin, then connect **Renou** from the plugin's Connectors tab.
2. Sign in with your Renou account and choose what to allow. Read access is required. Contact creation, updates (including birthdays), and interaction logging are selected by default; turn write access off for a read-only connection. Reconnect older connections to grant contact changes.
3. You need a Renou account with an active Plus or Power subscription. Both are managed in the Renou iPhone app.

Claude may ask for its own confirmation before a write, according to your connector settings.

Setup guide and troubleshooting: https://renou.ai/connect

## Data

The plugin itself stores nothing and contains no code. Its skills use the Renou connector at `https://renou.ai/mcp`, operated by MUNADI AI SOLUTIONS FZCO, which reads your own Renou contacts, interactions and reminders. With write access, it can create contacts, update details including birthdays, and log interactions. Answers come in small pages; there are no tools to export everything, delete contacts, or send messages. You can disconnect at any time in the Renou app under Settings, AI Connectors.

- Privacy policy: https://renou.ai/privacy
- Terms: https://renou.ai/terms
- Support: support@renou.ai, https://renou.ai/support

## License

MIT. See [LICENSE](LICENSE).
