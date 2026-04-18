# USER.md — My Human

- **Name:** Awais Zegham
- **What to call them:** Awais
- **Username:** @Autonomousssss
- **Pronouns:** he/him
- **Timezone:** America/New_York (EDT)
- **Location:** Unknown

## Context

Active Telegram user. Has 779+ skills installed. Very curious about OpenClaw internals.

## Communication Style

- **Prefers:** brief responses / casual
- **Tone:** casual
- **When urgent:** [unknown]

## Spelling & Communication Notes

⚠️ **Important:** Awais is bad with spelling — ALWAYS check/ask when uncertain. Don't assume spelling is correct — ask if unsure rather than guessing wrong.

## Credential & Secrets Management

⚠️ **CRITICAL RULE — ALWAYS FOLLOW THIS ORDER:**

1. **Need a credential?** → First check Doppler (`doppler secrets get KEY --plain`)
2. **If not in Doppler** → Ask the user
3. **User provides a credential** → ALWAYS verify it works before saving:
   - For GitHub tokens: `curl -s "https://api.github.com/user" -H "Authorization: Bearer TOKEN"`
   - For other APIs: make a test call to confirm validity
4. **Credential works** → Save to Doppler immediately (`doppler secrets set KEY=VALUE`)
5. **Only then** → use it

**⚠️ TOKEN VERIFICATION RULE:**
- Never trust a token without testing it first
- Always run a quick API call to verify before committing it to config
- If token returns `Bad credentials` or `Authentication Failed` → it's wrong, tell Awais
- Doppler is the source of truth — never hardcode tokens in configs

## API Key Storage (Doppler)

| Service | Key | Verified |
|---------|-----|----------|
| GitHub | `GITHUB_TOKEN` | ✅ yes |
| Vercel | `VERCEL_TOKEN` | ✅ yes |
| Resend | `RESEND_API_KEY` | ✅ yes |
| Heroku | `HEROKU_API_KEY` | ✅ yes |
| NordVPN | `NORDVPN_ACCESS_TOKEN` | ✅ yes |
| Supabase | `SUPABASE_ACCESS_TOKEN` | ✅ yes |
| Notion | `NOTION_TOKEN` | ✅ yes |
| Minimax | `MINIMAX_API_KEY` | ✅ yes |

## Preferences

- **Topics to avoid:** [none known]
- **Pet peeves:** wrong assumptions, being ignored
- **Things they love:** OpenClaw, automation, skill management

## Current Projects

- [OpenClaw setup & configuration]
- [UGC Factory — automated content pipeline]
- [Skill management & installation]

## Notes

- Remembers everything and references past conversations often
- Asks frequent system checks (skill count, gateway status, etc.)
- Prefers Git commits after each change
- Uses Google Drive (5TB) for media storage
- Uses Notion for pipeline tracking
- GitHub MCP connected for 24/7 GitHub operations

## Exact Identifiers

```
User: Awais Zegham, username: @Autonomousssss, Telegram ID: 5274114698
OpenClaw workspace: /home/jin/.openclaw/workspace/
Skills directory: /home/jin/openclaw-src/skills/
GitHub user: zegh6389
GitHub repo: https://github.com/zegh6389/ugc-factory
UGC Drive: https://drive.google.com/drive/folders/1xXK0og1Irn0fpsek_9GIZUor6ENXiqbd
Notion workspace: AWAIS ZEGHAM's Notion
Dashboard URL: https://web-dashboard-bice-nine.vercel.app
Gateway port: 18789
```

---

_I should update this as I learn._
