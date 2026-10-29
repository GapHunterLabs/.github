<div align="center">

# Gap Hunter Labs

**Engineering & Evidence.** I'm [Joel Díaz](https://github.com/kendjm). I build local-first developer tools and investigate root causes.

[![Website](https://img.shields.io/badge/website-gaphunterlabs.com-0a0a0a?style=flat-square&logo=cloudflare&logoColor=F38020)](https://gaphunterlabs.com)
[![JetBrains Marketplace](https://img.shields.io/badge/JetBrains-Marketplace-0a0a0a?style=flat-square&logo=jetbrains&logoColor=white)](https://plugins.jetbrains.com/vendor/gap-hunter-labs)
[![X](https://img.shields.io/badge/X-@GapHunterLabs-0a0a0a?style=flat-square&logo=x&logoColor=white)](https://x.com/GapHunterLabs)
[![Email](https://img.shields.io/badge/contact-gaphunterlabs.com-0a0a0a?style=flat-square&logo=gmail&logoColor=white)](mailto:contact@gaphunterlabs.com)
[![Sponsor](https://img.shields.io/badge/sponsor-the%20work-0a0a0a?style=flat-square&logo=githubsponsors&logoColor=white)](https://gaphunterlabs.com/sponsors/)

</div>

---

## What it does

Gap Hunter Labs is my independent engineering practice: I build local-first IDE plugins
and extensions, and I investigate the root cause of performance, security and reliability
problems.

My working rule is simple: **I reproduce it, I measure it, then I claim it.** Every
finding I report comes with the numbers from before and after.

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

I report my findings upstream with a reproduction and measurements:

| Ticket | Pull request | Outcome |
| --- | --- | --- |
| [IJPL-257919](https://youtrack.jetbrains.com/issue/IJPL-257919) | [#3696](https://github.com/JetBrains/intellij-community/pull/3696) | Fixed; blocking time cut from ~2.2 s to ~0–1 ms. Integrated upstream. |
| [IJPL-257909](https://youtrack.jetbrains.com/issue/IJPL-257909) | [#3701](https://github.com/JetBrains/intellij-community/pull/3701) | 689–931 ms down to 8–22 ms. Open. |
| [IJPL-257908](https://youtrack.jetbrains.com/issue/IJPL-257908) | [#3694](https://github.com/JetBrains/intellij-community/pull/3694) | 157 ms down to 0 ms. Open. |
| [IDEA-393501](https://youtrack.jetbrains.com/issue/IDEA-393501) | — | Fixed by JetBrains on October 28, 2026. |

Other upstream work: I reported dependency advisories in
[reactive-commons-go#5](https://github.com/bancolombia/reactive-commons-go/issues/5)
(10 advisories, fixed upstream).

## Principles

- **Local-first.** My tools run on your machine.
- **Traceable.** Each claim I make links to a ticket, a PR or a reproducible test.
- **Validated on real data.** I test against real projects, not only synthetic fixtures.

## Services

I take fixed-scope engagements for teams: performance audits, security reviews and
migration work. Scope and published pricing are on [gaphunterlabs.com](https://gaphunterlabs.com).

## Sponsors

Sponsorship pays for the fixes I send upstream and for keeping my free tools working. It
never changes a finding or a report. The levels and what each one includes are on
[gaphunterlabs.com/sponsors](https://gaphunterlabs.com/sponsors/).

**No sponsors yet.** With their permission, I list each sponsor here by name or logo. To
be the first, [join on Patreon](https://www.patreon.com/c/GapHunterLabs) or write to me at
[contact@gaphunterlabs.com](mailto:contact@gaphunterlabs.com).

<!-- Sponsors go here. Add one line per sponsor: [Name](url) -->

## Contact

- Website: [gaphunterlabs.com](https://gaphunterlabs.com)
- Email: [contact@gaphunterlabs.com](mailto:contact@gaphunterlabs.com)
- X: [@GapHunterLabs](https://x.com/GapHunterLabs)
- Founder: [Joel Díaz](https://github.com/kendjm)
- Security reports: see the `SECURITY` page on the website.
