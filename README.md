<p align="center"><img src="icon.png" width="128" alt="LittleOrange icon"></p>

<h1 align="center">LittleOrange</h1>

<p align="center">A tiny macOS menu bar app that shows your Claude session and weekly limits,<br>with a pixel-art Clawd living in the panel.</p>

<p align="center"><a href="../../releases/latest"><b>Download the latest version</b></a> · Free</p>

---

## What you get

- Your 5-hour session and weekly usage, right in the menu bar
- When each limit resets, down to the minute
- A little Clawd who keeps you company
- 21 themes · 8 languages · launch at login

## Requirements

- macOS 13 Ventura or later (Apple silicon or Intel)
- [Claude Code](https://claude.com/claude-code) signed in with your Claude account: run `claude` once, then `/login`

## Install

1. Download `LittleOrange.dmg` from [Releases](../../releases/latest) and open it.
2. Drag **LittleOrange** into **Applications**.
3. Open it. macOS will block it the first time because the app isn't notarized yet:
   go to **System Settings → Privacy & Security**, scroll down and click **Open Anyway**.
4. If macOS asks whether LittleOrange can use your Keychain, click **Always Allow**.
   That's how it reads your Claude Code sign-in.

## Privacy

LittleOrange reads your Claude Code sign-in from the Keychain and talks only to Claude's usage endpoint.
Nothing else leaves your Mac. No analytics, no tracking.

## Good to know

- The usage endpoint isn't a public API, so a future Claude update could break the app.
- If it says your sign-in expired, open `claude` once and it'll come back.
- LittleOrange is an unofficial, free app made by a fan. It isn't affiliated with or endorsed by Anthropic.
