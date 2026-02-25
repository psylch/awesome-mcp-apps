# Awesome MCP Apps [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of MCP Apps — interactive UI applications embedded in AI chat interfaces (Claude, ChatGPT, VS Code, etc.) via the [MCP Apps protocol](https://modelcontextprotocol.io/docs/extensions/apps).

MCP Apps let MCP servers render rich, interactive UIs directly inside AI conversations. Think diagrams, charts, 3D viewers, games — not just text.

## Contents

- [Official](#official)
- [Apps](#apps)
  - [Diagrams & Visualization](#diagrams--visualization)
  - [3D & Creative](#3d--creative)
  - [Productivity](#productivity)
  - [Games](#games)
  - [Data & Analytics](#data--analytics)
  - [Media](#media)
- [Frameworks & SDKs](#frameworks--sdks)
- [Developer Tools](#developer-tools)
- [Templates](#templates)
- [Learning Resources](#learning-resources)
- [Launch Partners](#launch-partners)

## Official

- [ext-apps](https://github.com/modelcontextprotocol/ext-apps) — Protocol spec & SDK for MCP Apps.
- [MCP Apps Docs](https://modelcontextprotocol.io/docs/extensions/apps) — Official documentation.
- [Claude Design Guidelines](https://claude.com/docs/connectors/building/mcp-apps/design-guidelines) — UI design guidelines for Claude.
- [ChatGPT UI Guidelines](https://developers.openai.com/apps-sdk/concepts/ui-guidelines) — UI design guidelines for ChatGPT.

## Apps

### Diagrams & Visualization

- [excalidraw-mcp](https://github.com/excalidraw/excalidraw-mcp) — Excalidraw whiteboard with streaming render and checkpoint persistence. The reference implementation for MCP Apps. ⭐ 2.7k
- [mermaid-mcp-app](https://github.com/psylch/mermaid-mcp-app) — Mermaid diagram editor with click-to-select, box select, inline rename, and AI context design.
- [plantuml-mcp-app](https://github.com/psylch/plantuml-mcp-app) — PlantUML diagram renderer with live preview and code editing.

### 3D & Creative

- [splatter-mcp-app](https://github.com/kstonekuan/splatter-mcp-app) — Generate and view 3D models using 3D Gaussian Splatting.
- [brick-mcp-app](https://github.com/dend/brick-mcp-app) — LEGO brick visualization.
- [nyaomaru-3D-mcp-ui](https://github.com/nyaomaru/nyaomaru-3D-mcp-ui) — 3D character viewer.

### Productivity

- [wordly-mcp-app](https://github.com/arifszn/wordly-mcp-app) — Interactive text rewriting and grammar improvement.
- [mcpapp-colorpicker](https://github.com/elbruno/mcpapp-colorpicker) — Color picker with rich UI (.NET).
- [wordpress-agentic-ui-generator](https://github.com/mnfst/wordpress-agentic-ui-generator) — Convert WordPress sites into MCP Apps.
- [better-search-console](https://github.com/houtini-ai/better-search-console) — Google Search Console dashboards.

### Games

- [chessagine-mcp](https://github.com/jalpp/chessagine-mcp) — Chess board with Stockfish analysis and Lichess integration.
- [reversi-mcp-apps](https://github.com/mfukushim/reversi-mcp-apps) — Reversi / Othello game.
- [submarine-attack-mcp-apps](https://github.com/mfukushim/submarine-attack-mcp-apps) — Submarine attack game.

### Data & Analytics

- [metmuseum-mcp](https://github.com/mikechao/metmuseum-mcp) — Explore The Metropolitan Museum of Art collection.

### Media

- [abc-music-mcp-app](https://github.com/psylch/abc-music-mcp-app) — Music composer with interactive piano roll and ABC notation.
- [mcp-tts-voicevox](https://github.com/kajidog/mcp-tts-voicevox) — Text-to-speech with VOICEVOX engine.

## Frameworks & SDKs

- [mcp-use](https://github.com/mcp-use/mcp-use) — Fullstack MCP framework for building MCP Apps and MCP Servers. ⭐ 9.3k
- [skybridge](https://github.com/alpic-ai/skybridge) — Framework for building ChatGPT & MCP Apps. ⭐ 637
- [generative-ui](https://github.com/CopilotKit/generative-ui) — Generative UI examples for AG-UI, A2UI, and MCP Apps. ⭐ 556
- [sunpeak](https://github.com/Sunpeak-AI/sunpeak) — Local-first MCP App framework. ⭐ 151
- [mcp-apps-demo](https://github.com/CopilotKit/mcp-apps-demo) — CopilotKit MCP Apps demo.
- [chapplin](https://github.com/ssssota/chapplin) — Lightweight MCP Apps and ChatGPT Apps framework.
- [mcp-apps-kit](https://github.com/AndurilCode/mcp-apps-kit) — TypeScript framework targeting both MCP Apps and ChatGPT Apps from a single codebase.
- [mcp-ui-components](https://github.com/themesberg/mcp-ui-components) — UI components based on Flowbite and Skybridge.
- [mcp-ui](https://github.com/epicweb-dev/mcp-ui) — Go beyond text interaction in AI chat.

## Developer Tools

- [MCPJam Inspector](https://github.com/MCPJam/inspector) — Test & debug MCP servers and MCP Apps. ⭐ 1.8k
- [mcp-apps-theme-inspector](https://github.com/osamu329/mcp-apps-theme-inspector) — Visualize host CSS theme variables and preview UI components.
- [mcp-ui-studio](https://github.com/d-barletta/mcp-ui-studio) — Visual workshop for designing MCP Apps.
- [yavio](https://github.com/teamyavio/yavio) — Open-source analytics and visibility layer for MCP Apps.

## Templates

- [mcp-app-template (sebderhy)](https://github.com/sebderhy/mcp-app-template) — ChatGPT/MCP app template designed to be modified by coding agents.
- [mcp-app-template (madebywild)](https://github.com/madebywild/mcp-app-template) — Template using Skybridge + Tailwind + Apps SDK UI.
- [mcp-app-fastmcp-example](https://github.com/vardior/mcp-app-fastmcp-example) — Python example using FastMCP backend.
- [nextjs-mcp-apps-chatbot](https://github.com/cameronking4/nextjs-mcp-apps-chatbot) — Next.js chatbot template with AppHost for rendering MCP Apps.
- [mcpdemos](https://github.com/leestott/mcpdemos) — 8 Node.js/TypeScript demos covering text tools to interactive UIs.

## Learning Resources

- [MCP Apps Blog Post](https://blog.modelcontextprotocol.io/posts/2026-01-26-mcp-apps/) — Official announcement.
- [MCP Apps are here (WorkOS)](https://workos.com/blog/2026-01-27-mcp-apps) — Technical deep dive.
- [5 Tips for Building MCP Apps (Goose)](https://block.github.io/goose/blog/2026/01/30/5-tips-building-mcp-apps/) — Practical building tips.
- [MCP Apps Tips (MCPJam)](https://www.mcpjam.com/blog/mcp-apps-tips) — Development tips from MCPJam.

## Launch Partners

The following companies were [launch partners](https://blog.modelcontextprotocol.io/posts/2026-01-26-mcp-apps/) for MCP Apps (January 26, 2026):

Amplitude · Asana · Box · Canva · Clay · Figma · Hex · monday.com · Slack · Salesforce

---

## Contributing

Contributions welcome! Please read the [contributing guidelines](CONTRIBUTING.md) first.

If you built an MCP App or found one that's missing, open a PR.
