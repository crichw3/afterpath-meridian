# Afterpath Meridian Design System - Public Mirror

Public mirror of the Afterpath Meridian design system and animated logo style guide, published as self-contained HTML references.

## Canonical URLs

**Always-current (bookmark these for external tools):**

Rendered (for humans, design tools):

- Design System: <https://crichw3.github.io/afterpath-meridian/meridian-latest.html>
- Logo Style Guide: <https://crichw3.github.io/afterpath-meridian/logo-style-guide-latest.html>

Raw source (for tools that parse HTML source):

- Design System: <https://raw.githubusercontent.com/crichw3/afterpath-meridian/main/meridian-latest.html>
- Logo Style Guide: <https://raw.githubusercontent.com/crichw3/afterpath-meridian/main/logo-style-guide-latest.html>

**Frozen version snapshots (for audit and historical reference):**

- `meridian-<version>.html`
- `logo-style-guide-<version>.html`

## Current version

- Design System: Meridian 1.1.0 (2026-04-22)
- Logo Style Guide: Meridian 1.1.0 (2026-04-22)

## What changed in 1.1.0

Logo is static by default. Animation is now a signal (reserved for Pathfinder states and documented hero contexts), not a decoration. Ambient UI chrome uses new canonical brand SVG assets via `StaticLogoLockup` / `StaticLogoIcon` components. No token changes; no animation tier values changed.

## Why this exists

External tools (Cloud Design, Figma, Cursor, v0, Builder.io), decks, and PRDs can consume the live Meridian reference through a single stable URL without version chasing. The `-latest.html` files are overwritten in place on every design system update, so anyone bookmarked to those URLs always sees current state.

## How this gets updated

Updates flow from the Afterpath working codebase (`Afterpath-AI/afterpath-next`). Every Meridian design system edit is governed by the Meridian maintenance contract, which requires the HTML peers to be regenerated and pushed here in the same session.

Do not open PRs against this repo directly. Changes here are mirror pushes from the maintenance contract.

## Repo structure

```
afterpath-meridian/
  meridian-latest.html           always-current DS (bookmark this)
  meridian-1.0.0.html            frozen snapshot
  logo-style-guide-latest.html   always-current logo guide (bookmark this)
  logo-style-guide-1.0.0.html    frozen snapshot
  backups/                       timestamped JSX backups before multi-edit sessions
  README.md                      this file
```

---

Afterpath, Inc., a Delaware Corporation.
