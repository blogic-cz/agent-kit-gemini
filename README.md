# Agent Kit - Gemini CLI Extension

MCP server integrations for Gemini CLI - browser automation, error tracking, and extended APIs.

## What's Included

| MCP Server | Description |
|------------|-------------|
| **chrome-dev-tools** | Browser automation and debugging |
| **sentry-spotlight** | Local error debugging |
| **sentry** | Cloud error tracking |
| **agentsfera** | Extended API capabilities |

## Installation

### Requirements

- **Gemini CLI 0.4.0+** (extensions support)
- Node.js 18+
- Chrome/Chromium browser

### Install with Auto-Update

```bash
# Upgrade Gemini CLI to 0.4.0+
npm install -g @google/gemini-cli@latest

# Install extension with auto-update enabled
gemini extensions install blogic-cz/agent-kit-gemini --auto-update

# Verify installation
gemini extensions list
# ✓ agent-kit (v1.0.0) - Enabled
```

## Usage

Once installed, just use Gemini CLI naturally:

```bash
gemini

> Take a screenshot of https://example.com
> Show me the latest errors from my local development
> Debug the performance issues in my app
```

The extension provides guidance to Gemini on when and how to use each tool automatically.

## Uninstall

```bash
gemini extensions uninstall agent-kit
```

## Optional Configuration

**Sentry Cloud** (for production errors):
```bash
export SENTRY_AUTH_TOKEN="your-token"
```

**Agentsfera** (for extended APIs):
```bash
export AGENTSFERA_API_KEY="your-key"
```

## Support

- Issues: [agent-kit-gemini repository](https://github.com/blogic-cz/agent-kit-gemini/issues)
- Full documentation: See [GEMINI.md](./GEMINI.md)
- Claude Code version: [blogic-marketplace/agent-kit](https://github.com/blogic-cz/blogic-marketplace/tree/main/agent-kit)

---

**Blogic** - Version 1.0.0
