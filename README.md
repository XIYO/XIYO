# XIYO

[한국어](README.ko.md)

I build local-first tools that make AI-assisted work repeatable, inspectable, and easier to trust.

My current work focuses on agent integrations for macOS and architecture tooling for SvelteKit. The goal is practical software with a short path from discovery to a verified first run.

## Start here

| Project | What it helps you do | Platform | Stage |
| --- | --- | --- | --- |
| [XIYO Plugins](https://github.com/XIYO/plugins) | Install Apple Calendar and message-analysis tools in Codex or Claude Code | macOS | Preview |
| [svelte-arch](https://github.com/XIYO/svelte-arch) | Keep people and AI agents on the same SvelteKit architecture, with an injectable kit and automated audits | SvelteKit | Preview |

### XIYO Plugins

Add the public marketplace directly from GitHub:

```bash
codex plugin marketplace add XIYO/plugins
codex plugin add apple-calendar@xiyo
codex plugin add message-pipeline@xiyo
```

Start a new Codex task after installation so the installed skills are loaded. Claude Code installation and platform prerequisites are documented in the [plugin marketplace](https://github.com/XIYO/plugins).

### svelte-arch

An architecture standard and injectable project kit for SvelteKit. It gives people and coding agents the same placement rules, project manifest, and executable audit instead of relying on memory alone.

[Read the architecture and installation guide](https://github.com/XIYO/svelte-arch)

## What I optimize for

- **Local-first boundaries** — private source data stays on the user's machine unless a documented action explicitly sends selected content elsewhere.
- **Inspectable behavior** — CLIs, schemas, and contracts make agent actions reviewable outside a chat UI.
- **Recoverable workflows** — idempotent operations, explicit state, and diagnostic commands make interrupted work safe to resume.
- **Agent-ready repositories** — installation, first use, verification, security boundaries, and contribution paths are treated as product features.

## Project stages

- **Preview** — usable today, with interfaces or installation paths that may still change before a stable release.
- **Experimental** — published for evaluation; expect missing integrations or manual setup.
- **Archived** — kept for reference and no longer actively supported.

## Contact

- Website: [xiyo.dev](https://xiyo.dev)
- Email: [bunny@xiyo.dev](mailto:bunny@xiyo.dev)
- Security reports: follow the `SECURITY.md` policy in the affected repository.
