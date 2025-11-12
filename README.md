# Agent Kit - Gemini CLI Extension

## Installation

```bash
# Upgrade Gemini CLI to 0.4.0+
npm install -g @google/gemini-cli@latest

# Install extension with auto-update (installs to ~/.gemini/extensions/agent-kit/)
gemini extensions install https://github.com/blogic-cz/agent-kit-gemini --auto-update
```

## Requirements

**Node.js LTS** is required for MCP servers to work properly.

→ Download: https://nodejs.org

---

## What's Included

| MCP Server | Description |
|------------|-------------|
| **chrome-dev-tools** | Browser automation and debugging |
| **sentry-spotlight** | Local error debugging |
| **sentry** | Cloud error tracking |
| **agentsfera** | Extended API capabilities |

**Requirements:** Gemini CLI 0.4.0+, Node.js 22+, Chrome/Chromium

## Usage

Once installed, just use Gemini CLI naturally:

```bash
gemini

> Take a screenshot of https://example.com
> Show me the latest errors from my local development
> Debug the performance issues in my app
```

The extension provides guidance to Gemini on when and how to use each tool automatically.

## License

MIT

## Author

Blogic - https://github.com/blogic-cz
