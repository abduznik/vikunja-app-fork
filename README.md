# Vikunja App (community fork)

This is a **maintained fork** of
[go-vikunja/app](https://github.com/go-vikunja/app), the official
cross-platform app for [Vikunja](https://vikunja.io), the fluffy, open-source,
self-hostable to-do app.

The upstream project's tagged releases stopped in 2024. This fork keeps the
Android app current for personal use and adds features on top. Not affiliated
with the official Vikunja project.

## Changes vs upstream

- **Task detail page** — tap a task to open a full read view (description,
  labels, dates, priority, progress, attachments) with edit/comments actions
- **Attachment upload** from the app (multipart PUT, Vikunja v2.5.0 quirk)
- **In-app attachment viewers** — PDFs render natively (pinch zoom), HTML
  files render in a WebView; other types open externally; downloads are cached
- **Clickable links in task descriptions** — bare `http://`, `https://` and
  `www.` URLs open the default browser
- **Home-screen widget** — tap task name to open the app, configurable
  lookahead days, auto-refresh when tasks change, always-on periodic sync
- **Week-start setting** aligned with the Vikunja API convention (0=Sunday)
- **Settings UI fixes** (default-project dropdown width, API-value alignment)

MIT licensed, same as upstream.

---