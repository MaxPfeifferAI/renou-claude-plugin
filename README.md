# Renou

Renou is a personal relationship manager for iPhone. This plugin connects Claude to your Renou network and teaches it four everyday workflows, so staying in touch takes a sentence instead of an app session.

## What you can do

- **Log a catch-up in one line.** "Had coffee with Marcus, we talked about his seed round." Claude finds Marcus, logs it and tells you the next check-in date.
- **Get a brief before a meeting.** "Brief me on Sarah before my call." You get her role, what you talked about last, open promises and two openers.
- **See who to reconnect with.** "Who should I reach out to this week?" You get the people who are overdue, upcoming birthdays and a one-line opener for each.
- **Draft a follow-up.** "Write Elena a follow-up about the candidates." Claude drafts it from your notes. Renou never sends messages for you.

## Set up

1. Install the plugin, then connect **Renou** from the plugin's Connectors tab.
2. Sign in with your Renou account and choose what to allow. Reading is always on; logging interactions is a separate switch, off until you turn it on.
3. You need a Renou account with an active Plus or Power subscription. Both are managed in the Renou iPhone app.

To let Claude log interactions without asking each time, set the Renou tool "Log a touchpoint" to **Always allow** in Claude's connector settings.

Setup guide and troubleshooting: https://renou.ai/connect

## Data

The plugin itself stores nothing and contains no code. Its skills use the Renou connector at `https://renou.ai/mcp`, operated by MUNADI AI SOLUTIONS FZCO, which reads your own Renou contacts, interactions and reminders, and logs an interaction only when you allowed logging. Answers come in small pages; there is no bulk export, no editing or deleting of contacts, and no sending of messages. You can disconnect at any time in the Renou app under Settings, AI Connectors.

- Privacy policy: https://renou.ai/privacy
- Terms: https://renou.ai/terms
- Support: support@renou.ai, https://renou.ai/support

## License

MIT. See [LICENSE](LICENSE).
