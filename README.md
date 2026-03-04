# JSON Formatter

A lightweight, single-page web application for formatting, highlighting, and exploring JSON data.

## Features

- **Syntax Highlighting** — Keys, strings, numbers, booleans, and null values are color-coded
- **Collapsible Sections** — Click any `{` or `[` to collapse/expand objects and arrays
- **Format** — Pretty-prints JSON with proper indentation
- **Compress** — Minifies JSON into a single line
- **Escape / Unescape** — Convert JSON to/from escaped string representation
- **Copy** — Copies the formatted output to clipboard
- **Expand All / Collapse All** — Bulk toggle all collapsible sections
- **Auto-format on paste** — Paste JSON and it formats instantly
- **Keyboard shortcut** — `Ctrl/Cmd + Enter` to format

## Usage

Open `index.html` in any browser. No build step, no dependencies.

Or visit the deployed version: [json-formatter-mauve-pi.vercel.app](https://json-formatter-mauve-pi.vercel.app)

## Development

The entire application is a single `index.html` file with embedded CSS and JavaScript.

Formatting is handled by [Prettier](https://prettier.io/) with Google style conventions:

```bash
npx prettier --write index.html
```
