# Trio Workspace

A clickable prototype of a desktop app that puts **Grok Bot**, **ChatGPT** and **Claude** in one workspace.
It is a single HTML file (React + Tailwind from CDNs, no build step, no backend) with fake example data.

## Run it

Open `index.html` in a browser. It needs an internet connection, because React, Babel, Tailwind and the fonts load from CDNs.

## What's in it

- **Header dock** with the three bots. Each can drop down to the top right with a speech bubble (Slack notification, voice mode, file permission request). Only one bot is open at a time.
- **Chat** with a model selector (Auto / Grok Bot / ChatGPT / Claude), fake replies, and an empty state with example prompts.
- **Browser panel** with tabs, a page preview, an "AI controlling" badge with Take over, and a DevTools console.
- **Chat graph**: a force-directed graph of your projects around a central "Me" node, with hover tooltips, drag, zoom, filters and click-to-open.
- **Collapsible sidebar**, light/dark theme (in Settings), and a command palette.

## Keyboard shortcuts

| Shortcut | Action |
| --- | --- |
| Ctrl/Cmd + K | Command palette |
| Ctrl/Cmd + N | New chat |
| Ctrl/Cmd + G | Open / close the graph |
| Ctrl/Cmd + B | Collapse / expand the sidebar |
| Esc | Close the palette or any open bot |

## Notes

This is a prototype: replies, chats, projects and the browser previews are made up, and Settings only has the theme toggle.
The three character images are embedded as base64 at the bottom of `index.html`.
