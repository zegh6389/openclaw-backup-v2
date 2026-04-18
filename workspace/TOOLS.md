# TOOLS.md - Local Notes

Skills define _how_ tools work. This file is for _your_ specifics — the stuff that's unique to your setup.

## Research Protocol (MANDATORY)

**For ALL research tasks, use BOTH tools simultaneously:**

1. **Perplexity PWM MCP** (`pplx_sonar`, `pplx_smart_query`, `pplx_deep_research`)
   - Authenticated as: macbhatti374@gmail.com (Pro)
   - Token: `~/.config/perplexity-web-mcp/token`
   - Quota: 200 Pro searches, 20 Deep Research remaining
   - FREE option: `pplx_sonar` uses Sonar (no Pro quota)

2. **Websearch Minimax** (configured in OpenClaw)
   - Primary web search for general lookups
   - Configured in openclaw.json

**Rule:** Always query BOTH sources in parallel for comprehensive research. Cross-reference and synthesize results for better accuracy.

---

## What Goes Here

Things like:

- Camera names and locations
- SSH hosts and aliases
- Preferred voices for TTS
- Speaker/room names
- Device nicknames
- Anything environment-specific

## Examples

```markdown
### Cameras

- living-room → Main area, 180° wide angle
- front-door → Entrance, motion-triggered

### SSH

- home-server → 192.168.1.100, user: admin

### TTS

- Preferred voice: "Nova" (warm, slightly British)
- Default speaker: Kitchen HomePod
```

## Why Separate?

Skills are shared. Your setup is yours. Keeping them apart means you can update skills without losing your notes, and share skills without leaking your infrastructure.

---

Add whatever helps you do your job. This is your cheat sheet.
