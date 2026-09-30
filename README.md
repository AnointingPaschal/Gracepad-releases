# Gracepad

**Church presentation and live broadcast software.** Project scripture, song
lyrics, sermon notes, and media to your congregation's screen — and send the
same output as a live NDI feed to OBS, vMix, or any NDI-compatible switcher
for streaming and recording.

> This repository hosts **downloads only**. Gracepad's source code is
> maintained privately — see [Support](#support) if you need help or want to
> report an issue.

---

## Download

| Platform | Download | Notes |
|---|---|---|
| 🪟 **Windows** | [**Latest Release →**](../../releases/latest) | `.exe` installer, full NDI broadcast support |
| 🍎 **macOS (Apple Silicon)** | [**Latest Release →**](../../releases/latest) | `.dmg` or `.zip`, full NDI broadcast support |
| 🐧 **Linux** | [**Latest Release →**](../../releases/latest) | `.AppImage` or `.deb` — NDI broadcast not available on this platform yet |
| 📖 **Bible Translation Pack** | [**Download (11 translations) →**](https://github.com/AnointingPaschal/Gracepad-releases/releases/download/bibles-v1/Witness-Bible-Pack.zip) | Import into the app — see [Importing Bible Translations](#importing-bible-translations) |

All release builds and version history: **[Releases page](../../releases)**

> **macOS note:** builds are unsigned (no Apple Developer certificate). On
> first launch, if macOS blocks it as "unidentified developer," right-click
> the app → **Open**, or allow it under **System Settings → Privacy &
> Security**.
>
> **Windows note:** if SmartScreen warns on first run, click **More info →
> Run anyway**. This is expected for an installer without a paid code-signing
> certificate.

---

## Table of contents

- [Features](#features)
- [Getting started](#getting-started)
- [How to use Gracepad](#how-to-use-gracepad)
  - [Projecting to a second screen](#projecting-to-a-second-screen)
  - [Broadcasting with NDI](#broadcasting-with-ndi)
  - [Bible & scripture](#bible--scripture)
  - [Songs](#songs)
  - [Media, Themes & Slides](#media-themes--slides)
  - [Playlists](#playlists)
  - [Quick Text & Alerts](#quick-text--alerts)
  - [Timer](#timer)
  - [Sermon AI tools](#sermon-ai-tools)
- [Importing Bible translations](#importing-bible-translations)
- [Free vs PRO](#free-vs-pro)
- [System requirements](#system-requirements)
- [Support](#support)

---

## Features

| Feature | Description |
|---|---|
| **Live Preview → Live** workflow | Stage anything in a Preview pane, review it, then push it to the congregation's screen with one click — nothing goes live by accident. |
| **Bible** | Multi-translation scripture display with fast book/chapter/verse navigation, plus AI-powered natural-language search ("find verses about anxiety"). |
| **Songs** | Build a song library with arranged lyric slides; import and auto-arrange lyrics from text, or search for lyrics online. |
| **Media** | Image and video backgrounds, with smooth playback behind your text. |
| **Themes** | Fully customizable presentation themes — fonts, colors, backgrounds, layout. |
| **Slide Builder** | A freeform slide/deck editor for anything custom — text, shapes, gradients, images — beyond the built-in categories. |
| **Playlists** | Order your entire service — scripture, songs, media, slides — into one run-of-show. |
| **Quick Text** | One-off announcement slides for anything that comes up mid-service. |
| **Alerts** | Time-critical overlays (e.g. a nursery alert) that can interrupt whatever's live without losing your place. |
| **Countdown Timer** | An on-screen timer, independently stylable and toggleable per output. |
| **Physical Projector Output** | Automatically detects a second monitor and drives it as a dedicated, distraction-free output — separate from your control panel. |
| **NDI Broadcast** | Send your live output as a network video source any NDI-aware tool (OBS, vMix, etc.) can pick up — no capture card required. *(Windows & macOS)* |
| **Sermon AI Tools** | Record and transcribe a sermon, then get an AI-generated summary and notes. |
| **Voice Commands** | Hands-free control during a live service. |

---

## Getting started

1. Download the installer for your platform from the table above.
2. Install and launch Gracepad.
3. The app opens in **Free** mode — every core feature works immediately;
   some (unlimited themes, AI tools, most Bible translations, lyric
   import/search — see [Free vs PRO](#free-vs-pro)) require a PRO license.
4. To activate PRO, sign in with your organization's Gracepad account from
   the app's license/login screen.

---

## How to use Gracepad

### Projecting to a second screen

Plug in a second monitor/projector before launching, or while the app is
open — Gracepad detects it automatically and offers to open the **Projector
Window** on it. If no second display is present, Gracepad simply runs
single-screen with no projector output; nothing breaks.

### Broadcasting with NDI

With NDI Runtime installed (see [System requirements](#system-requirements)),
enable **Go Live / NDI** from the control panel. Gracepad then appears as an
NDI source named for your install — pick it up in OBS, vMix, or any other
NDI-compatible receiver on the same network.

### Bible & scripture

Open the **Bible** tab, pick a translation from the tabs at the top, and
navigate by book/chapter/verse. Selecting a verse loads it into **Preview**;
click to send it **Live**. Use the search bar for a reference lookup, or (PRO)
ask a natural-language question like *"verses about forgiveness"*.

### Songs

Open the **Songs** tab to browse your library. Select a song to preview its
arranged slides, then push to Live. Add new songs manually, or (PRO) import
raw lyrics and let Gracepad auto-arrange them into slides.

### Media, Themes & Slides

- **Media** tab: add images/videos as backgrounds or full-screen content.
- **Themes** tab: customize how everything looks — up to 10 custom themes
  on Free, unlimited on PRO.
- **Slides** tab: build fully custom slides when nothing else fits.

### Playlists

Open the **Playlists** tab to assemble an ordered run-of-show — mix scripture,
songs, media, and slides into a single sequence you can step through live.

### Quick Text & Alerts

- **Quick Text**: type and send a one-off announcement slide instantly.
- **Alerts**: fire a time-critical overlay (e.g. nursery pickup) that
  interrupts the current Live content without losing it — Live resumes
  automatically once the alert clears.

### Timer

Open the **Timer** tab to run an on-screen countdown, independently visible
per output (Preview, Live, Projector).

### Sermon AI tools *(PRO)*

Record a sermon, get it transcribed, then generate an AI summary and notes —
save the result to a folder of your choice for later reference.

---

## Importing Bible translations

Gracepad reads Bible data from **`.tw`** files.

1. Download the **[Witness Bible Pack](https://github.com/AnointingPaschal/Gracepad-releases/releases/download/bibles-v1/Witness-Bible-Pack.zip)**
   above and unzip it — you'll get 11 `.tw` files:
   `KJV`, `AMP`, `NIV`, `ESV`, `AMPC`, `NLT`, `NASB`, `MSG`, `NKJV`, `ASV`,
   `RSV`.
2. In Gracepad, open the **Bible** tab.
3. Next to the translation tabs, click the file picker, choose a `.tw` file,
   then click **Import**.
4. Repeat for each translation you want available — imported translations
   appear as new tabs immediately.

> **Free tier** includes full access to **KJV, AMP, and NIV** out of the box.
> The remaining 8 translations in the pack require a **PRO** license to use
> once imported.

---

## Free vs PRO

| | Free | PRO |
|---|---|---|
| Bible translations | KJV, AMP, NIV | All imported translations |
| Custom themes | Up to 10 | Unlimited |
| Lyric import & auto-arrange | — | ✅ |
| AI lyric/Bible search | — | ✅ |
| Sermon AI transcription & summary | — | ✅ |
| Live watermark | Shown | Removed |

PRO is organization-licensed (one login, multiple devices depending on your
plan). Contact your Gracepad provider to activate or upgrade a license.

---

## System requirements

- **Windows 10/11** (x64) — full feature set including NDI.
- **macOS** (Apple Silicon: M1/M2/M3/etc.) — full feature set including NDI.
  Intel Macs are not currently built; open an issue if you need one.
- **Linux** (x64, AppImage or .deb) — everything except NDI broadcast, which
  is not yet available on this platform.
- **NDI Runtime** — install from [ndi.tv](https://ndi.tv) if you want NDI
  broadcast to work. Gracepad runs fine without it; NDI features are simply
  unavailable until it's installed.
- A second monitor is optional — required only if you want a dedicated
  physical projector output separate from the control panel.

---

## Support

This repository hosts downloads only — issues aren't tracked here. Reach out
to your Gracepad provider/organization contact for support, license
activation, or to report a bug.
