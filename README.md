<div align="center">

<img src="https://github.com/user-attachments/assets/57654cef-992c-4d48-b835-5a96eeb421aa" width="180" height="180" alt="Pocket Paste" style="background: transparent; border-radius: 0;" />

# Pocket Paste

### A quieter way to remember what you copy

Save clipboard history, find it quickly, and turn repeated text into reusable shortcuts — in a native macOS menu-bar app.

<p>
<a href="https://github.com/vanloc0301/Pocket-Paste/releases/latest"><strong>Download Pocket Paste for Mac</strong></a>
&nbsp; · &nbsp;
<a href="https://pocketpaste.app">Website</a>
&nbsp; · &nbsp;
<a href="https://github.com/vanloc0301/Pocket-Paste/releases">Releases</a>
</p>

<sub>macOS 14 Sonoma or later · Current release line: 2.2</sub>

</div>

<br />

## Why Pocket Paste?

Your clipboard is full of useful things: a sentence you want to reuse, a link you opened yesterday, an image from a design review, or a file you need again. Pocket Paste keeps those moments close without turning your Mac into a complicated productivity system.

Open the menu-bar panel, search your history, and paste the right item when you need it. For text you type repeatedly, create a snippet and expand it with a short trigger.

## What you can do

### Clipboard history

- Keep a searchable history of copied text, links, images, and files.
- Find entries with ordinary search or focused filters such as tags.
- Pin important items and paste them without leaving the app you are using.
- Drag supported items out when a normal paste is not the right interaction.
- Search text recognized inside captured screenshots with OCR.

### Text snippets

- Turn repeated phrases, support replies, addresses, and templates into shortcuts.
- Organize snippets with folders and tags.
- Use fill-in fields when a reusable template needs a little context.
- Edit and save snippets explicitly so a draft is never mistaken for a finished template.

### A native Mac workflow

- Open the history panel with a configurable global keyboard shortcut.
- Keep the app in the menu bar and out of the way until you need it.
- Use familiar macOS interactions for search, selection, paste, previews, and settings.
- Protect sensitive capture contexts, including secure input and password-manager workflows.

### Local-first by design

- Clipboard history and snippets stay on your Mac.
- Clipboard contents are not uploaded to Pocket Paste servers.
- Licensing and trial services receive only the limited device and account information needed to validate access.
- No subscription is required for the product license; eligible updates remain available to license holders.

## Install

1. Open the [latest release](https://github.com/vanloc0301/Pocket-Paste/releases/latest) and download the DMG.
2. Open the downloaded DMG.
3. Drag **Pocket Paste** into the **Applications** folder.
4. Launch Pocket Paste and follow the first-run permission guidance.
5. Allow Accessibility access when macOS asks for it. This is needed for global shortcuts and pasting selected history items.
6. If you want screenshot entries to appear in history, allow access to the relevant screenshots folder when requested.

## Requirements

- macOS 14 Sonoma or later.
- Accessibility permission for global hotkeys and assisted paste.
- Optional access to the screenshots folder for screenshot history and OCR search.

## Licensing

Pocket Paste is distributed with a one-time license rather than a subscription. Your license is entered from **Pocket Paste → Settings → License**. The [License Portal](https://pocketpaste.app/license) can help recover a key and manage activated Macs.

A trial is available so you can check the workflow on your own Mac before purchasing. For current plans and support, visit [pocketpaste.app](https://pocketpaste.app).

## Publishing releases

This repository is the public download and release hub for Pocket Paste. Keep application binaries in GitHub Releases, not in normal Git history.

Use one published release for each app version:

- Tag: v2.2
- Asset: Pocket-Paste-v2.2.dmg
- Next release: v2.3 with Pocket-Paste-v2.3.dmg

A normal release checklist is:

1. Build the new version and increment both the marketing version and build number.
2. Sign the production app with Developer ID and complete notarization before distributing it broadly.
3. Create a GitHub Release using a version tag such as v2.3.
4. Upload the matching DMG as a release asset.
5. Add short release notes covering user-visible changes, fixes, and any migration or permission notes.
6. Publish the release. The Download link above will then resolve to the newest published release page.

For a branded stable download address such as https://download.pocketpaste.app/latest, a small redirect endpoint can point to the newest GitHub release asset without proxying the DMG itself. This keeps the website link stable while every release retains its own versioned filename.

## Support

- Product site: [pocketpaste.app](https://pocketpaste.app)
- Documentation: [Pocket Paste Docs](https://pocketpaste.app/docs)
- Releases and changelog: [GitHub Releases](https://github.com/vanloc0301/Pocket-Paste/releases)

Pocket Paste is built for people who want their copied information to remain useful, searchable, and close at hand — without another busy dashboard competing for attention.
