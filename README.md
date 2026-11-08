# freelance.link plugin

[freelance.link](https://freelance.link) shows when you have time. This plugin connects your agent to your freelance.link account, so one sentence keeps your profile, badge and open data current: "Project X was extended until March." or "I'm out next week."

| What | Your agent can |
| --- | --- |
| Availability | Read your status and first free date, confirm it's still correct |
| Projects | List, add, change, delete |
| Absences | List, add, delete |
| Waitlist | See who waits, notify them when you ask |

Requires a freelance.link account and Claude, Claude Code, Codex, ChatGPT or Cursor. The plugin connects to the MCP server at `https://freelance.link/mcp` with OAuth.

## Installation

Claude Code:

```bash
claude plugin install freelance-link --marketplace FreelanceLink/freelancelink-plugin
```

In Claude, connect freelance.link from the [Claude directory](https://claude.ai/directory/freelance-link). In ChatGPT, add `https://freelance.link/mcp` as a connector. In Cursor, clone this repository into `~/.cursor/plugins/local/freelance-link` and run **Developer: Reload Window**.

## Quick start

Sign in to freelance.link when your agent asks and choose what it may do. Then ask:

```text
What does my freelance.link profile say about my availability?
```

Your waitlist gets an email only when you ask for it. Review or revoke access anytime under **Account → Connections**.

## Documentation

How to connect and what each permission allows: [freelance.link/mcp](https://freelance.link/mcp). Questions go to [hey@freelance.link](mailto:hey@freelance.link); this repository only contains releases. See the [privacy policy](https://freelance.link/privacy) and [terms](https://freelance.link/terms).
