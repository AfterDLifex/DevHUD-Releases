# DevHUD

**Your sprint, your reminders, and your credentials — in one quiet desktop HUD.**

DevHUD is a local-first developer dashboard for Windows. It keeps your active sprint, work items, quick captures, due dates, reminders, and an encrypted credential vault in a single frameless, always-available window — no account, no cloud, no tracking.

> [Download the latest release](../../releases/latest) · Windows 10/11 (x64)

---

## Why DevHUD

- **Zero friction capture** — dump a task, blocker, note, or idea into the inbox in seconds.
- **Never miss a deadline** — OS-level notifications for reminders, sprint end dates, and work-item due dates, plus an in-app notification center.
- **Private by design** — all data lives in a local SQLite database on your machine. Credentials are encrypted at rest with AES-256-GCM and Argon2id.
- **Always within reach** — shrink the app into a floating mini window (always-on-top "sticky note") that lives on your desktop while you code.
- **Auto-updates** — new versions download and install themselves in the background.

---

## Features

### Sprint & work tracking
- One active sprint at a time with goal, start/end dates, and progress
- Work items: tasks, blockers, production notes, ideas — with status, priority, and due dates
- Quick-capture inbox for unassigned thoughts
- Carry unfinished work into the next sprint, archive sprint snapshots, search sprint history, and generate stand-up summaries
- Productivity data export as JSON, plus verified SQLite backups with preview/restore

### Reminders & notifications
- One-time and repeating (daily/weekly) reminders with OS toast notifications
- Automatic alerts when your sprint end date approaches or passes
- Automatic alerts when work items come due or go overdue
- Notification center with unread badges, snooze, and dismiss — persisted across restarts

### Credential vault
- Local encrypted vault for logins, API keys, and notes
- AES-256-GCM encryption with Argon2id key derivation — decrypted only in memory while unlocked
- Timed clipboard clearing and automatic idle lock

### Workspace & personalization
- Frameless, resizable, always-on-top mini window mode
- Themes (default, light, midnight, AMOLED, Nord) and accent colors
- Font zoom, profile avatar, animated or static mini-window chip
- Optional launch-at-startup and configurable auto-refresh
- Keyboard shortcuts for every page (0–8)

---

## Install

1. Download `DevHUD_*_x64-setup.exe` from the [latest release](../../releases/latest).
2. Run the installer and launch **DevHUD**.
3. The app will notify you in-app when updates are available — or it updates automatically.

> **Note:** DevHUD requests Windows notification permission the first time a reminder or due-date alert fires. Allow it once and alerts will keep working.

## Requirements

- Windows 10 (1903+) or Windows 11, 64-bit
- ~50 MB disk space

## Privacy

DevHUD stores everything locally in `%APPDATA%` — there is no account system, no telemetry, and no data leaves your machine. Backups you create are unencrypted SQLite files, so keep them somewhere safe; vault contents remain encrypted inside them.

## Changelog

See [Releases](../../releases) for version history.

## License

Proprietary — © Sayan. All rights reserved.
