# FocusForge

A focus and productivity companion for students who struggle with procrastination. FocusForge combines a Pomodoro-style timer, task management, distraction reminders, a progress dashboard, digital wellbeing tracking, and a community leaderboard into a single, self-contained web app.

## Features

- **Focus timer (the forge)** — Pomodoro-style focus, short break, and long break sessions with a glowing progress ring and spark animations on completion. Durations are fully customizable.
- **Study tasks** — Add tasks with priority levels, link a task to your active focus session, and track how many sessions each task has received.
- **Distraction reminders** — Optional gentle nudges during focus sessions to help you stay on track.
- **Progress dashboard** — Daily session and minute counts, current streak, total sessions, a 7-day activity chart, a daily goal progress bar, and earnable badges.
- **Digital wellbeing** — Tracks how long the FocusForge tab itself stays active vs. in the background, lets you manually log time spent on other apps, and includes a step-by-step guide to checking real screen time stats on Android, iPhone, and desktop.
- **Community** — A leaderboard, weekly challenges, and study groups to compare progress with other students. Currently runs on sample data as a preview of the planned multiplayer experience.
- **Account & settings** — Editable profile name, avatar color, custom timer durations, and a daily session goal.

## Getting started

This is a single static HTML file with no build step or dependencies.

1. Download `index.html`.
2. Open it in any modern browser.

That's it — all data is stored locally in your browser via `localStorage`. No account, server, or internet connection required (aside from loading fonts and icons).

## Tech

- Plain HTML, CSS, and JavaScript
- [Tabler Icons](https://tabler.io/icons) for iconography
- Google Fonts (Space Grotesk, Inter)

## Roadmap

- Real accounts and a shared backend for live multiplayer leaderboards and study groups
- Cross-device sync
- Export/import for personal data

## Privacy

All progress, tasks, and settings are stored only in your browser's local storage. Nothing is sent to a server.
