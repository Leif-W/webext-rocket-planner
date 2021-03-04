# WebExtension based Rocket Planner

Rocket Planner is a WebExtension based daily activity planner used to manage tasks.

# Usage

Here are some notes about usage.

## Installation

This add-on or extension is intended to be installed from a marketplace, a sufficiently secure and vetted repository, or the developer's official site.

## Compatibility

This add-on requires a browser enabled with JavaScript, CSS, and WebExtensions, such as a Chromium based browser (Google Chrome, Brave, Microsoft Edge), or Firefox based browser (Mozilla Firefox, Waterfox, Palemoon).

# Development

Here are some notes about the development process.

# Suggestions

Some suggested tools:

- [Visual Studio Code](https://code.visualstudio.om/)
- VSC extension [Draw.io Integration](https://marketplace.visualstudio.com/items?itemName=hediet.vscode-drawio) by Henning Dieterichs

## Requirements

[Requirements](docs/Requirements.md) documentation.

# Known Issues

- The Swimlane Flow Diagram finds the most icons using [draw.io](https://app.diagrams.net/), not the desktop app or the VSC extension.
- The .drawio file format is not rendered in the browser on GitHub, so I exported as an SVG file format.
- The draw.io app saves the file with a white label background for the 2nd and 3rd lane icon label. Manually edit style in VSC using the VSC draw.io extension.
- The chosen app icon is not displayed on GitHub as the original file is located on the [Icon Finder](https://www.iconfinder.com/) website and 3rd party images are blocked by my browser, GitHub, or the document.
- The manually downloaded and exported SVG image for the website icon is not properly displayed with a local reference.
- Hard coded the URL to the website.svg file using the raw GitHub URL, which is ugly and brittle. If the file is moed in the repo, the URL must be manually updated. Ew.
