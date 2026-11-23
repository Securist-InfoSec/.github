# Securist

**Autonomous pentesting that runs on your machine.**

There is no upload button. The planner, workers, tools, traffic capture, and evidence graph stay on the machine that owns the engagement. Every finding is bound to the request and response that prove it.

[Private beta](https://secur.ist/) · [Simulated run](https://secur.ist/demo.html) · [Security](https://secur.ist/security.html) · [Source](https://secur.ist/source.html)

## Repositories

| Repo | What it is |
|---|---|
| [`securist-pentest`](https://github.com/Securist-InfoSec/securist-pentest) | Public site, scoping assistant, simulated run, security and source pages |
| engine mirror | Published with the first signed build |
| benchmark | Lab targets, seeds, budgets, scoring, and the failure log |

## Boundaries

- No distributed scanning. Tool, scan, and exploit traffic originates only from the machine that owns the engagement.
- No shared targets. No feature lets one install attack a host on another install's behalf.
- No silent root CA. The capture certificate is explained, optional, and removable.
- Authorized testing only. A named owner and written permission come before any task.

## License

The engine is built on an AGPL-3.0 codebase. The corresponding source, including Securist patches, is offered with every distributed build.

Contact: securist_info_sec@protonmail.com
