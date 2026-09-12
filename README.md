# Mossland Open Developers — Repository conventions

<!-- opendevs-badges:start -->
[![Website: moss.land](https://img.shields.io/badge/Website-moss.land-2563eb?style=flat)](https://moss.land/)
<!-- opendevs-badges:end -->

This repository contains the [organization profile](profile/README.md) and shared README conventions for MosslandOpenDevs.

## README badges

Use a compact badge row below the project title, in this order. Include only fields supported by the repository's actual metadata and documentation.

| Badge | Source and destination | Presentation |
| --- | --- | --- |
| Lifecycle | The [ecosystem registry](https://links.moss.land/ecosystem-registry.json), or an explicit project lifecycle declaration; link to that source. | Lab `eab308`, Beta `3b82f6`, Archive `6b7280`. Do not invent a lifecycle for an unclassified project. |
| CI | The existing build, test, or documentation validation workflow; link to its Actions page. | Use GitHub's native workflow status badge. Preserve additional meaningful checks. |
| Website | The project's documented public website; link to that URL. | Shields.io `Website` badge, domain as its value, `2563eb`. A website link is not an uptime claim. |
| License | The actual license file or explicit README license section; link to that evidence. | Shields.io `License` badge, `64748b`. Use `mixed` or a scope label when code, text, maps, or assets have different terms. Omit if undeclared. |

Use `style=flat` for Shields.io badges. Keep useful project-specific package, runtime, or development-status badges after the common row. If none of the common fields applies, a neutral `Repository: MosslandOpenDevs` badge (`64748b`) may link to the repository. Badge count can differ between projects.

Keep translated READMEs aligned. For generated READMEs, update the generator and verify that regeneration is clean. The `opendevs-badges:start` and `opendevs-badges:end` comments delimit the shared row; they do not imply automatic synchronization. Recheck static lifecycle, website, and license values when those facts change.

Apply these conventions to actively editable public repositories. GitHub-archived repositories remain preserved; private repositories can adopt them when their internal documentation needs an update.

References: [Shields static badges](https://shields.io/badges/static-badge) · [GitHub workflow status badges](https://docs.github.com/en/actions/how-tos/monitor-workflows/add-a-status-badge).
