<div align="center">

<img src="https://avatars.githubusercontent.com/u/235319490?s=200" width="110" alt="Gelhaus Solutions"/>

# Gelhaus Solutions

**Software, security and infrastructure — built and run by one engineer, to production standards.**

[![Website](https://img.shields.io/badge/web-ennogelhaus.de-1f6feb?style=flat-square)](https://ennogelhaus.de)
[![Advisories](https://img.shields.io/badge/security-advisories-c9302c?style=flat-square)](https://github.com/Gelhaus-Solutions/advisories)
[![Maintainer](https://img.shields.io/badge/maintainer-%40egelhaus-24292f?style=flat-square&logo=github)](https://github.com/egelhaus)

</div>

---

Gelhaus Solutions is the umbrella for the work of [Enno Gelhaus](https://github.com/egelhaus) — Chief Operations & Security Officer at [Postiz](https://github.com/gitroomhq/postiz-app) — covering everything built outside of that role: developer platform automation, security tooling and advisories, community infrastructure, and the homelab that runs it all.

What you see here is the public surface. Most development happens on a self-hosted GitLab; repositories move to GitHub when they are ready to be public.

## Projects

| Repository | What it is |
| --- | --- |
| [**contribution-checker**](https://github.com/Gelhaus-Solutions/contribution-checker) | GitHub App + Next.js service that scores incoming pull requests for quality and checks them against a contributor whitelist. Runs in production across every Postiz repository and serves 100+ users on the hosted instance. |
| [**advisories**](https://github.com/Gelhaus-Solutions/advisories) | Central, cross-project security advisory record. One place to look, regardless of which project a finding affects. |

## Forks &amp; upstream work

Not everything worth maintaining is something new. These are forks kept alive here — some to carry patches upstream, some because the original stopped moving.

| Fork | Why |
| --- | --- |
| [**discordtickets-revamped**](https://github.com/Gelhaus-Solutions/discordtickets-revamped) | A maintained continuation of `discord-tickets/bot`, the most widely used open-source ticket bot for Discord, after upstream went quiet. Actively developed, GPL-3.0. |
| [**Vulnogram**](https://github.com/Gelhaus-Solutions/Vulnogram) | Fork of the CVE Program's tool for reserving, managing and publishing CVE records — kept in step with day-to-day advisory work. |
| [**hexclave**](https://github.com/Gelhaus-Solutions/hexclave) | Fork of the Hexclave infrastructure platform, tracked and patched alongside upstream. |

## How things are built

- **UI-first, always.** If it can be done through the API, it can be done through the interface. No feature is CLI-only.
- **Secrets belong in Vault.** Signing keys, app credentials and tokens are Vault-backed with strict access scoping — never in a repository, never in a plain CI variable.
- **Operators keep control.** Anything self-hosted stays that way: support access is opt-in, manually enabled and time-limited, and the operator always has the last word.
- **Forks are maintained, not abandoned.** If something is forked here, it gets updates, security fixes and issue responses.
- **Licensing is per repository.** Check the `LICENSE` file before reusing anything.

## Security

Security is the core of what this organisation does, not a side channel.

- Advisories for all projects are collected in [**Gelhaus-Solutions/advisories**](https://github.com/Gelhaus-Solutions/advisories).
- Found something? Report it privately to **security@egelhaus.de**, or through the repository's private vulnerability reporting. Please don't open a public issue for a security finding.
- Reports are handled under coordinated disclosure: acknowledgement, a fix, a published advisory, and credit where it's wanted.

## Contact

- **Web** — [ennogelhaus.de](https://ennogelhaus.de)
- **GitHub** — [@egelhaus](https://github.com/egelhaus)
- **Languages** — German and English, both fine.

<div align="center">
<sub>Built in Germany. Maintained with intent.</sub>
</div>
