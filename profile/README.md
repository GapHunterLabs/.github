<div align="center">

# Gap Hunter Labs

**Engineering & Evidence.** Local-first developer tools and root-cause research, led by [Joel Díaz](https://github.com/kendjm).

[![Website](https://img.shields.io/badge/website-gaphunterlabs.com-0a0a0a?style=flat-square&logo=cloudflare&logoColor=F38020)](https://gaphunterlabs.com)
[![JetBrains Marketplace](https://img.shields.io/badge/JetBrains-Marketplace-0a0a0a?style=flat-square&logo=jetbrains&logoColor=white)](https://plugins.jetbrains.com/vendor/gap-hunter-labs)
[![X](https://img.shields.io/badge/X-@GapHunterLabs-0a0a0a?style=flat-square&logo=x&logoColor=white)](https://x.com/GapHunterLabs)
[![Email](https://img.shields.io/badge/contact-gaphunterlabs.com-0a0a0a?style=flat-square&logo=gmail&logoColor=white)](mailto:contact@gaphunterlabs.com)

</div>

---

## What it does

Gap Hunter Labs is an independent engineering practice: local-first IDE plugins and
extensions, plus root-cause investigation of performance, security and reliability
problems.

The working rule is simple: **reproduce it, measure it, then claim it.** Every finding
ships with the numbers from before and after.

## Catalog

| Where | What you find |
| --- | --- |
| [JetBrains Marketplace](https://plugins.jetbrains.com/vendor/gap-hunter-labs) | Plugins for IntelliJ Platform IDEs: code-quality detectors, security checks and productivity tools. Mostly free, with a few freemium and paid options. |
| VS Code Marketplace | Extensions that port several of the IDE plugins to VS Code. |
| [Catalog page](https://gaphunterlabs.com) | Every tool, with downloads and pricing, refreshed from live data. |

Highlights:

- **Mermaid Companion** — syntax highlighting and real syntax validation for `.mmd` / `.mermaid` files.
- **Refactor Simulator** — preview a refactoring in an isolated, in-memory sandbox before you commit it.
- **ghl-jail** — run a command-line tool so it can only touch one project folder, not your secrets. Windows, no admin rights, no install.

## Research

Findings are reported upstream with a reproduction and measurements:

| Ticket | Pull request | Outcome |
| --- | --- | --- |
| [IJPL-257919](https://youtrack.jetbrains.com/issue/IJPL-257919) | [#3696](https://github.com/JetBrains/intellij-community/pull/3696) | Fixed; blocking time cut from ~2.2 s to ~0–1 ms. Integrated upstream. |
| [IJPL-257909](https://youtrack.jetbrains.com/issue/IJPL-257909) | [#3701](https://github.com/JetBrains/intellij-community/pull/3701) | 689–931 ms down to 8–22 ms. Open. |
| [IJPL-257908](https://youtrack.jetbrains.com/issue/IJPL-257908) | [#3694](https://github.com/JetBrains/intellij-community/pull/3694) | 157 ms down to 0 ms. Open. |
| [IDEA-393501](https://youtrack.jetbrains.com/issue/IDEA-393501) | — | In progress on the JetBrains side. |

Other upstream work: dependency advisories reported in
[reactive-commons-go#5](https://github.com/bancolombia/reactive-commons-go/issues/5)
(10 advisories, fixed upstream).

## Principles

- **Local-first.** The tooling runs on your machine.
- **Traceable.** Each claim links to a ticket, a PR or a reproducible test.
- **Validated on real data.** Tested against real projects, not only synthetic fixtures.

## Services

Fixed-scope engagements for teams: performance audits, security reviews and migration
work. Scope and published pricing are on [gaphunterlabs.com](https://gaphunterlabs.com).

## Sponsors

**No sponsors yet.** This section is reserved for the people and companies that fund the
maintenance of these tools, and each one will be listed here by name and logo.

To become the first, write to [contact@gaphunterlabs.com](mailto:contact@gaphunterlabs.com).

<!-- Sponsors go here. Add one line per sponsor: [Name](url) -->

## Contact

- Website: [gaphunterlabs.com](https://gaphunterlabs.com)
- Email: [contact@gaphunterlabs.com](mailto:contact@gaphunterlabs.com)
- X: [@GapHunterLabs](https://x.com/GapHunterLabs)
- Founder: [Joel Díaz](https://github.com/kendjm)
- Security reports: see the `SECURITY` page on the website.
