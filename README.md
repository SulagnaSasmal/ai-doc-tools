# AI & Automation Tools

A landing page and hub for AI-powered documentation and automation tools built by Sulagna Sasmal: DocCraft AI, SpecFlow, DocQuery, DocPulse, and the PPT→MP4 pipeline.

## Live Demo

Hosted on GitHub Pages: `sulagnasasmal.github.io/ai-doc-tools/`

## Tools Featured

| Tool | Purpose | Link |
|------|---------|------|
| DocCraft AI | AI documentation generator: converts raw content into polished, MSTP-compliant docs | [Repo](https://github.com/SulagnaSasmal/Doccraft) |
| SpecFlow | OpenAPI 3.x → interactive developer portal (browser-based, no build step) | [Repo](https://github.com/SulagnaSasmal/specflow) |
| DocQuery | RAG-powered documentation chatbot with source citations | [Repo](https://github.com/SulagnaSasmal/docquery) |
| DocPulse | Documentation analytics dashboard (page views, search failures, content freshness) | [Repo](https://github.com/SulagnaSasmal/docpulse) |
| PPT→MP4 | PowerPoint-to-narrated-video pipeline using Azure TTS + FFmpeg | [Repo](https://github.com/SulagnaSasmal/ppt-to-mp4-doc-automation) |

## Tech Stack

- Single HTML file (inline CSS + JS, zero external dependencies)
- Inter / JetBrains Mono fonts
- Light and dark mode support

## Dark / Light Mode

The page supports dark and light themes via a toggle button (◐ / ☀) in the navigation bar. Theme preference persists in `localStorage`. System `prefers-color-scheme` is respected on first visit.

## Status

**Infrastructure: Complete**

| Area | Status |
|------|--------|
| Landing page with 5 tool cards | Complete |
| Tool descriptions, links, and tech stacks | Complete |
| Dark / light theme support | Complete |
| Responsive layout | Complete |

## Future Enhancements

- Embedded live demos within the page (SpecFlow iframe, DocCraft widget)
- Tool comparison matrix
- Changelog feed aggregated from all 5 tool repos
- Usage stats and uptime indicators
