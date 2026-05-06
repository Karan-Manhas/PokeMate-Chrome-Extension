# PokeMate Chrome Extension

A lightweight Chrome extension that opens a small Pokémon-inspired companion from the browser toolbar. The original idea was based on the concept of **rubber duck debugging**: having a small visual companion nearby while thinking through code, problems, or tasks.

> This is an early Chrome Extension project. It is intentionally simple and is best treated as a small UI/prototype project rather than a production browser extension.

## Overview

PokeMate adds a toolbar button to Chrome. When the extension icon is clicked, a popup appears with a Pokémon-themed animated companion.

The project demonstrates the basic structure of a Chrome Extension using Manifest V3, including:

- Extension manifest configuration
- Browser action popup
- Background service worker
- Static image/icon assets
- Options page scaffold

## Why I Built This

This project was inspired by the idea of **rubber duck debugging**, where explaining a problem out loud can help clarify thinking and reveal solutions. PokeMate turns that idea into a playful browser extension: a small companion that can sit in the browser and act as a light-hearted debugging buddy.

## Features

- Chrome toolbar extension icon
- Popup-based companion UI
- Pokémon-themed visual design
- Manifest V3 configuration
- Basic background service worker setup
- Options page scaffold for future customisation

## Tech Stack

- HTML
- JavaScript
- Chrome Extensions API
- Manifest V3

## Project Structure

```text
PokeMate-Chrome-Extension/
├── background.js        # Background service worker
├── manifest.json        # Chrome extension configuration
├── options.html         # Options page scaffold
├── popup.html           # Extension popup UI
├── images/              # Extension icons and image assets
└── README.md
```

## Installation

To run the extension locally:

1. Download or clone this repository.
2. Open Google Chrome.
3. Navigate to:

```text
chrome://extensions/
```

4. Enable **Developer mode** in the top-right corner.
5. Click **Load unpacked**.
6. Select the project folder.
7. Pin the extension to your browser toolbar.
8. Click the Pokéball icon to open PokeMate.

## Current Limitations

This is an older prototype and currently has a few limitations:

- The extension is static and does not yet include interactive assistant behaviour.
- The options page is only scaffolded and does not currently persist user settings.
- Some referenced files may need to be added or cleaned up if the project is revived, such as popup/options scripts and styling.
- The popup currently uses an externally hosted animated image; for a more reliable extension, this should be replaced with a local asset.

## Potential Improvements

Possible future improvements include:

- Add multiple selectable companions
- Store user preferences with `chrome.storage`
- Replace external image links with local extension assets
- Add simple animations or interaction states
- Add keyboard shortcuts
- Improve popup styling
- Add tests or linting for extension structure
- Package for Chrome Web Store distribution

## Status

Prototype / archived learning project.

This repository is mainly useful as evidence of early experimentation with browser extensions and lightweight UI tooling
