<h1 align="center"><img src="https://raw.githubusercontent.com/GapHunterLabs/.github/main/profile/banners/header.png" alt="Gap Hunter Labs. Engineering &amp; Evidence: I reproduce it, I measure it, then I claim it." width="100%"></h1>

<div align="center">

**Engineering & Evidence.** I'm [Joel Díaz](https://github.com/kendjm). I build local-first developer tools and investigate root causes.

[![gaphunterlabs.com](https://raw.githubusercontent.com/GapHunterLabs/.github/main/profile/badges/website.svg)](https://gaphunterlabs.com)
[![All repositories](https://raw.githubusercontent.com/GapHunterLabs/.github/main/profile/badges/repositories.svg)](https://github.com/orgs/GapHunterLabs/repositories)
[![JetBrains Marketplace](https://raw.githubusercontent.com/GapHunterLabs/.github/main/profile/badges/jetbrains-marketplace.svg)](https://plugins.jetbrains.com/vendor/gap-hunter-labs)
[![VS Code Marketplace](https://raw.githubusercontent.com/GapHunterLabs/.github/main/profile/badges/vscode-marketplace.svg)](https://marketplace.visualstudio.com/publishers/GapHunterLabs)
[![@GapHunterLabs on X](https://raw.githubusercontent.com/GapHunterLabs/.github/main/profile/badges/x.svg)](https://x.com/GapHunterLabs)
[![Email contact@gaphunterlabs.com](https://raw.githubusercontent.com/GapHunterLabs/.github/main/profile/badges/contact.svg)](mailto:contact@gaphunterlabs.com)
[![Sponsor the work](https://raw.githubusercontent.com/GapHunterLabs/.github/main/profile/badges/sponsor.svg)](https://gaphunterlabs.com/sponsors/)

</div>

<h2><img src="https://raw.githubusercontent.com/GapHunterLabs/.github/main/profile/banners/what-i-do.png" alt="What I do" width="100%"></h2>

Gap Hunter Labs is my independent engineering practice: I build local-first IDE plugins
and extensions, and I investigate the root cause of performance, security and reliability
problems.

My working rule is simple: **I reproduce it, I measure it, then I claim it.** Every
finding I report comes with the numbers from before and after.

<h2><img src="https://raw.githubusercontent.com/GapHunterLabs/.github/main/profile/banners/stack.png" alt="Stack" width="100%"></h2>

| Layer | What I use |
| --- | --- |
| **Platforms** | ![JetBrains IDEs](https://raw.githubusercontent.com/GapHunterLabs/.github/main/profile/badges/stack-jetbrains-ides.svg) ![IntelliJ IDEA](https://raw.githubusercontent.com/GapHunterLabs/.github/main/profile/badges/stack-intellij-idea.svg) ![VS Code](https://raw.githubusercontent.com/GapHunterLabs/.github/main/profile/badges/stack-vscode.svg) ![Windows](https://raw.githubusercontent.com/GapHunterLabs/.github/main/profile/badges/stack-windows.svg) |
| **Languages** | ![Kotlin](https://raw.githubusercontent.com/GapHunterLabs/.github/main/profile/badges/stack-kotlin.svg) ![Java](https://raw.githubusercontent.com/GapHunterLabs/.github/main/profile/badges/stack-java.svg) ![Python](https://raw.githubusercontent.com/GapHunterLabs/.github/main/profile/badges/stack-python.svg) |
| **Disciplines** | ![Static analysis](https://raw.githubusercontent.com/GapHunterLabs/.github/main/profile/badges/stack-static-analysis.svg) ![Performance](https://raw.githubusercontent.com/GapHunterLabs/.github/main/profile/badges/stack-performance.svg) ![Security research](https://raw.githubusercontent.com/GapHunterLabs/.github/main/profile/badges/stack-security-research.svg) ![Reliability](https://raw.githubusercontent.com/GapHunterLabs/.github/main/profile/badges/stack-reliability.svg) |
| **Tooling** | ![Gradle](https://raw.githubusercontent.com/GapHunterLabs/.github/main/profile/badges/stack-gradle.svg) ![JUnit](https://raw.githubusercontent.com/GapHunterLabs/.github/main/profile/badges/stack-junit.svg) ![Git](https://raw.githubusercontent.com/GapHunterLabs/.github/main/profile/badges/stack-git.svg) ![GitHub](https://raw.githubusercontent.com/GapHunterLabs/.github/main/profile/badges/stack-github.svg) ![GitHub Actions](https://raw.githubusercontent.com/GapHunterLabs/.github/main/profile/badges/stack-github-actions.svg) |

<h2><img src="https://raw.githubusercontent.com/GapHunterLabs/.github/main/profile/banners/catalog.png" alt="Catalog" width="100%"></h2>

| Where | What you find |
| --- | --- |
| [JetBrains Marketplace](https://plugins.jetbrains.com/vendor/gap-hunter-labs) | Plugins for IntelliJ Platform IDEs: code-quality detectors, security checks and productivity tools. Mostly free, with a few freemium and paid options. |
| [VS Code Marketplace](https://marketplace.visualstudio.com/publishers/GapHunterLabs) | Extensions that port several of the IDE plugins to VS Code. |
| [Catalog page](https://gaphunterlabs.com/catalog/) | Every tool, with downloads and pricing, refreshed from live data. |
| [GitHub repositories](https://github.com/orgs/GapHunterLabs/repositories) | The source of every plugin and extension, one repository each. |

### Selected tools

| Tool | The gap | What it does |
| --- | --- | --- |
| [Background ReadAction Freeze Companion](https://gaphunterlabs.com/catalog/background-readaction-freeze-companion/) | The freeze pattern that JetBrains' Platform Blog names, a background task that reaches a blocking, non-cancellable read action, had no static check. | An inspection for your plugin's own code. The same check found IDEA-393501 in IntelliJ itself. |
| [OpenAPI Companion](https://gaphunterlabs.com/catalog/openapi-companion/) | Reviews of existing OpenAPI plugins report external `$ref` values that do not resolve, or editors that freeze the IDE on large specs. | `$ref` navigation resolved entirely against local files, and a warning on every `$ref` that does not resolve. |
| [Ansible Companion](https://gaphunterlabs.com/catalog/ansible-companion/) | Working with Ansible Vault files in the IDE depended on the `ansible-vault` command being installed. | Encrypt and decrypt Ansible Vault (1.1, AES256) directly in the editor. |
| [Mermaid Companion](https://gaphunterlabs.com/catalog/mermaid-companion/) | Reviews of existing Mermaid tooling for JetBrains IDEs report false warnings and errors on valid diagrams, such as identifiers with non-ASCII characters. | Syntax highlighting and syntax validation for `.mmd` and `.mermaid` files: flowchart, sequence and class diagrams. |

Also: [Refactor Simulator](https://gaphunterlabs.com/catalog/refactor-simulator/), which previews a refactoring in an isolated, in-memory sandbox before you commit it, and [ghl-jail](https://gaphunterlabs.com/ghl-jail/), which runs a command-line tool so it can only touch one project folder, not your secrets (Windows, no admin rights, no install).

<h2><img src="https://raw.githubusercontent.com/GapHunterLabs/.github/main/profile/banners/store.png" alt="Store" width="100%"></h2>

Paid and freemium plugins are bought and licensed through the JetBrains Marketplace; prices
are shown there. Services are quoted on my website.

| Plugin | Model | Get it |
| --- | --- | --- |
| **OpenAPI Companion** | Paid | [JetBrains Marketplace](https://plugins.jetbrains.com/plugin/33349-openapi-companion) · [Details](https://gaphunterlabs.com/catalog/openapi-companion/) |
| **Mermaid Companion** | Freemium | [JetBrains Marketplace](https://plugins.jetbrains.com/plugin/33340-mermaid-companion) · [Details](https://gaphunterlabs.com/catalog/mermaid-companion/) |
| **Ansible Companion** | Freemium | [JetBrains Marketplace](https://plugins.jetbrains.com/plugin/33082-ansible-companion) · [Details](https://gaphunterlabs.com/catalog/ansible-companion/) |
| **API Security Companion** | Freemium | [JetBrains Marketplace](https://plugins.jetbrains.com/plugin/33195-api-security-companion) · [Details](https://gaphunterlabs.com/catalog/api-security-companion/) |
| **Refactor Simulator** | Freemium | [JetBrains Marketplace](https://plugins.jetbrains.com/plugin/33204-refactor-simulator) · [Details](https://gaphunterlabs.com/catalog/refactor-simulator/) |
| **Firestore Companion** | Freemium | [JetBrains Marketplace](https://plugins.jetbrains.com/plugin/33330-firestore-companion) · [Details](https://gaphunterlabs.com/catalog/firestore-companion/) |

| Service | What you get | Details |
| --- | --- | --- |
| **Plugin performance audit** | UI freezes, typing lag and high CPU in your IntelliJ Platform plugin, reproduced, measured and patched, at a fixed price. | [Scope and pricing](https://gaphunterlabs.com/plugin-performance-audit/) |
| **Dependency security review** | A read-only review of your dependencies and CI/CD workflows at a fixed price: known CVEs, dependency confusion and workflow permissions, with a fix for each. | [Scope and pricing](https://gaphunterlabs.com/dependency-security-review/) |
| **Custom plugin inspections** | Static-analysis inspections for your codebase, as a plugin your team installs and runs in CI. | [Details](https://gaphunterlabs.com/custom-plugins-inspections/) |

<h2><img src="https://raw.githubusercontent.com/GapHunterLabs/.github/main/profile/banners/research.png" alt="Research" width="100%"></h2>

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

<h2><img src="https://raw.githubusercontent.com/GapHunterLabs/.github/main/profile/banners/principles.png" alt="Principles" width="100%"></h2>

- **Local-first.** My tools run on your machine.
- **Traceable.** Each claim I make links to a ticket, a PR or a reproducible test.
- **Validated on real data.** I test against real projects, not only synthetic fixtures.

<h2><img src="https://raw.githubusercontent.com/GapHunterLabs/.github/main/profile/banners/services.png" alt="Services" width="100%"></h2>

I take fixed-scope engagements for teams: performance audits, security reviews and
migration work. Scope and published pricing are on [gaphunterlabs.com](https://gaphunterlabs.com).

<h2><img src="https://raw.githubusercontent.com/GapHunterLabs/.github/main/profile/banners/sponsors.png" alt="Sponsors" width="100%"></h2>

Sponsorship pays for the fixes I send upstream and for keeping my free tools working. It
never changes a finding or a report. The levels and what each one includes are on
[gaphunterlabs.com/sponsors](https://gaphunterlabs.com/sponsors/).

**No sponsors yet.** With their permission, I list each sponsor here by name or logo. To
be the first, [join on Patreon](https://www.patreon.com/c/GapHunterLabs) or write to me at
[contact@gaphunterlabs.com](mailto:contact@gaphunterlabs.com).

<!-- Sponsors go here. Add one line per sponsor: [Name](url) -->

## Contact

- Website: [gaphunterlabs.com](https://gaphunterlabs.com)
- Organization: [GapHunterLabs](https://github.com/GapHunterLabs)
- Email: [contact@gaphunterlabs.com](mailto:contact@gaphunterlabs.com)
- X: [@GapHunterLabs](https://x.com/GapHunterLabs)
- Founder: [Joel Díaz](https://github.com/kendjm)
- Security reports: see the `SECURITY` page on the website.

<p align="center"><img src="https://raw.githubusercontent.com/GapHunterLabs/.github/main/profile/banners/footer.png" alt="Gap Hunter Labs: reproduce it, measure it, then claim it. gaphunterlabs.com" width="100%"></p>
