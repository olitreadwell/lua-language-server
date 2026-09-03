# LuaLS/lua-language-server context
> refreshed 2026-09-03 | upstream default: master @ 7a73c7889

## Identity & policies
- upstream: LuaLS/lua-language-server, default branch `master`, primary language Lua, English-first (README + changelog in English; some zh content in README footer).
- CLA/DCO: none (no CLA bot, no DCO requirement in CONTRIBUTING).
- AI-assisted PR policy: unstated (no AI disclosure requirement found; repo even uses AI for locale translations per CONTRIBUTING).
- signed commits required: no (no branch protection on master).
- PR template: none (`.github` has no PULL_REQUEST_TEMPLATE; use pipeline fallback body).
- external tracker: github.

## Conventions (verified from merged PRs)
- branch naming: mixed; `fix/...` and `feat/...` dominant (fix/generic-parent-inheritance, fix/pcall-own-return, feat/generic-operator-call, fix/namestyle-config). Fall back to `fix/<kebab>`.
- commit style: `type: description` (e.g. `fix:`, `feat:`, `chore:`, `docs:`) per CONTRIBUTING.
- CONTRIBUTING: do NOT commit `doc/` and `locale/` directories (only your own language in locale/). Changes altering behavior must update `changelog.md` (CI-enforced).
- CI: build.yml + test.yml (Lua). Trivial doc/typo changes to non-doc/non-locale files don't affect CI.
- how outside PRs get merged: responsive — recent 30-PR sample all 24 merged were external; median time-to-merge ~7 days.

## Maintainer picture
- Active maintainers: sumneko (owner), actboy168, CppCXY, RomanSpector (frequent external contributor). Fast response latency observed.

## Issue-area health
- No contested/redesign signals relevant to trivial doc cleanup. Repo actively maintained (pushed 2026-09-03).

## Gap ledger (dedupe — READ FIRST, never re-pick)
- (none yet for this repo)

## Mined gaps (discovered, not yet attempted)
- (see current run: trivial-fix pass — typos/broken links/stale refs across repo, excluding doc/ and locale/ per CONTRIBUTING)
