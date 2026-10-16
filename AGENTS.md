# Repository instructions for AI/code agents

Read the [canonical guidebook](https://github.com/Cucklord420/Toe-Tickling/blob/main/GUIDEBOOK.md) on the current default branch before substantive work. Respect the applicable user/platform instruction hierarchy, record the version actually consulted, and follow the guidebook's safety, verification, and evidence requirements. Do not claim to have read material that was unavailable.

## Repository-specific boundaries

- This repository publishes personal Vencord ClearVision v7 overrides through `theme.css`. Preserve CSS as the required runtime format: stylesheets and external theme imports are not failed Rust migrations.
- All **new first-party executable code and tests** must be Rust under the guidebook. Preserve existing upstream code, build interfaces, and third-party formats unless a replacement has demonstrated actual behavior parity.
- Before changing theme behavior, inspect the existing `theme.css`, `README.md`, `LICENSE-SCOPE.md`, imported theme URLs, and existing CI. Validate CSS syntax and the documented raw theme delivery URL. Compilation or parsing alone does not establish current Vencord compatibility.
- Preserve existing licenses: the pre-existing `theme.css` remains under the Unlicense; imported ClearVision styles retain Apache-2.0; only new original contributions follow the repository's AGPL-3.0-only scope. Do not silently relicense inherited work.
- Avoid publishing credentials, private settings, personal records, or unreviewed copied material. Use small reversible PRs, check concurrent changes, and report what was actually verified.

The guidebook provides general operating guidance. This file does not authorize deployment, license changes, or destructive actions.
