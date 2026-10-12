<div align="center">

<a href="https://cotlet.dev">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/cotletdev/cotlet/main/assets/logo-white.svg">
    <img src="https://raw.githubusercontent.com/cotletdev/cotlet/main/assets/logo.svg" alt="Cotlet" width="240">
  </picture>
</a>

### Your AI agent, logged in to the apps that never built an API.

[Website](https://cotlet.dev) · [Integrations](https://cotlet.dev/integrations) · [Docs](https://cotlet.dev/docs) · [Pricing](https://cotlet.dev/pricing) · [Request access](https://cotlet.dev/signup)

</div>

**[Cotlet](https://cotlet.dev)** hosts MCP servers and REST APIs for web apps that have no official API, or only a narrow one. You sign in to each app once, in your browser; Cotlet keeps only the encrypted session, never your password. Your AI agent then works in your own account and does the clicking for you.

- **One MCP server** for every app: `https://cotlet.dev/mcp/v1`. Works with Claude, ChatGPT, Cursor, Codex, GitHub Copilot, Gemini, Windsurf, n8n and any MCP client.
- **A REST API** with the same actions for scripts: `https://cotlet.dev/api/v1`. One key for both.
- **97 apps** today, including Skool, Substack, Medium, Udemy, Teachable, Booksy, Fresha, GetYourGuide, Idealista and Dubsado.
- **No stored passwords, no CAPTCHA solving, no MFA bypass.** Hosted in the EU.

```bash
claude mcp add --transport http cotlet https://cotlet.dev/mcp/v1 \
  --header "Authorization: Bearer $COTLET_API_KEY"
```

📘 Start here: **[cotletdev/cotlet](https://github.com/cotletdev/cotlet)**, the full overview, catalog, use cases and FAQ.

<sub>Cotlet is unofficial and not affiliated with the apps it integrates. Run by Take Group sp. z o.o., Katowice, Poland. Contact: contact@cotlet.dev</sub>
