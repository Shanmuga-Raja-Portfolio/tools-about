# TOOLS: pinned dev tools and a self-audit security kit

> Proprietary software by InferApps Tech PVT LTD. The source code is private. This page
> describes the project and what we're building.

The shared toolbox behind the other projects here: pinned versions of everyday
code-quality tools, and a kit for running AI-assisted security reviews of **our own**
projects in a repeatable, contained way.

## What we're building

- **Pinned linters**: [actionlint](https://github.com/rhysd/actionlint) for GitHub Actions
  workflows and [ShellCheck](https://github.com/koalaman/shellcheck) for shell scripts, so
  every project checks against the same versions.
- **AI penetration-test runs** with [Strix](https://github.com/usestrix/strix), inside
  Docker and with a time cap, pointed only at targets we own.
- **AI code review** with Alibaba's Open Code Review, using an isolated config.
- **Safe output**: secrets are redacted from tool output, and every run lists each host it contacted.
- **Telemetry off** for every tool.

## Status

In build. Already used for the Maker Studio security review.

---
Questions? Open an issue in this repository.
Part of [Shanmuga Raja Portfolio](https://shanmuga-raja-portfolio.github.io/).
