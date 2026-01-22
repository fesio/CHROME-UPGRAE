# Frequently Asked Questions (FAQ)

## What is this repository for?

This repository provides **Chrome DevTools MCP** - a Model Context Protocol server that enables AI coding assistants (like Gemini, Claude, Cursor, or Copilot) to control and inspect Google Chrome browsers for automation, debugging, and performance analysis.

## Can I use this to upgrade Internet Explorer or Windows Explorer?

**No.** This repository has nothing to do with Microsoft's Internet Explorer, Microsoft Edge, or Windows File Explorer. Despite the repository name containing "CHROME-UPGRAE", this is a tool for:
- Automating Google Chrome browser
- Debugging web applications in Chrome
- Analyzing web performance in Chrome
- Controlling Chrome via AI coding assistants

## How do I upgrade Internet Explorer?

Internet Explorer is no longer supported by Microsoft. You should:
1. **Use Microsoft Edge** - the modern replacement for Internet Explorer
2. Download Edge from: https://www.microsoft.com/edge
3. For legacy IE compatibility, Edge includes an "IE mode" feature

## How do I upgrade Windows File Explorer?

Windows File Explorer is part of the Windows operating system and cannot be upgraded separately. To get the latest version:
1. Update Windows through Windows Update
2. Go to Settings → Update & Security → Windows Update
3. Alternatively, consider upgrading to the latest version of Windows

## What does this repository actually do?

Chrome DevTools MCP allows you to:
- **Automate Chrome browser** - Click buttons, fill forms, navigate pages
- **Debug web applications** - Inspect console messages, network requests, and JavaScript errors
- **Analyze performance** - Record performance traces and get insights
- **Take screenshots** - Capture visual state of web pages
- **Run JavaScript** - Execute code in the browser context

## Who should use this repository?

This tool is designed for:
- Software developers using AI coding assistants
- QA engineers automating browser testing
- Web developers debugging applications
- Performance analysts examining web applications
- Anyone needing programmatic Chrome browser control via AI agents

## How do I get started?

1. **Install prerequisites:**
   - Node.js v20.19 or newer
   - Google Chrome (current stable version)
   - npm package manager

2. **Configure your MCP client** (e.g., Claude, Cursor, Copilot):
   ```json
   {
     "mcpServers": {
       "chrome-devtools": {
         "command": "npx",
         "args": ["-y", "chrome-devtools-mcp@latest"]
       }
     }
   }
   ```

3. **Test with a simple prompt:**
   ```
   Check the performance of https://developers.chrome.com
   ```

For detailed setup instructions, see the [main README](../README.md).

## I'm looking for browser upgrade information, where should I go?

For browser upgrades and downloads:
- **Google Chrome**: https://www.google.com/chrome/
- **Microsoft Edge**: https://www.microsoft.com/edge
- **Mozilla Firefox**: https://www.mozilla.org/firefox/
- **Safari**: Built into macOS, updated via macOS updates

## Still have questions?

- Check the [main README](../README.md) for detailed documentation
- See [Troubleshooting](./troubleshooting.md) for common issues
- Review the [Tool Reference](./tool-reference.md) for available features
- Report issues at: https://github.com/ChromeDevTools/chrome-devtools-mcp/issues
