# Open Source Operations Guide (EN)

## Goal

Run your GitHub portfolio as a product system, not a random code dump.

This guide standardizes how repositories are created, upgraded, maintained, and archived.

## Operating Model

- `Tier A (Flagship)`: recruiter-facing, pinned, continuously improved.
- `Tier B (Growth)`: actively shipping, proving product value.
- `Tier C (Maintain)`: stable references, low-touch maintenance.
- `Archived`: historical, no longer part of active narrative.

## Monthly Routine

1. Run repo audit.
2. Classify repos by signal and activity.
3. Archive stale low-signal repositories.
4. Upgrade metadata for active repositories.
5. Refresh profile README and project index.

Command:

```bash
/Users/terre/scripts/github_repo_audit.sh outhsics /Users/terre/repo-audit
```

## Standards for Active Repositories

- Clear one-line description (problem -> value).
- Topics added and consistent.
- README includes a `Recruiter Snapshot` block:
  - status
  - positioning
  - business/engineering value
  - stack and delivery proof
  - last reviewed date
- Recent commit activity for flagship repos.

## Pinning Strategy

Pin only repositories that support your current narrative:

- 4-6 repos maximum
- Prefer production/system projects over learning demos
- Replace archived or stale repos immediately

Recommended pin set:

- `openfang-auto-clip`
- `ai-skills-control-kit`
- `upload-test-file-generator`
- `ui-diff-tool`
- `TrendRadar`
- `react-schema-form-lite`

Manual update path:

1. Open `https://github.com/outhsics`.
2. Enter `Repositories`.
3. Click `Customize your pins`.
4. Uncheck archived repos and apply the recommended set.

## New Computer Recovery

Keep these assets in GitHub:

- Profile repo (`outhsics/outhsics`)
- Scripts in `/Users/terre/scripts` (or mirrored repo)
- Audit outputs in `/Users/terre/repo-audit`
- Reusable templates in `templates/`

Recovery checklist:

1. Clone profile repo.
2. Install GitHub CLI and authenticate.
3. Run audit script.
4. Apply metadata sync and archive actions.
5. Update README/pins and continue delivery.

## Publishing Strategy

To make this reusable across machines and teams, package this as a dedicated public toolkit repository:

- Suggested name: `github-brand-os`
- Include: scripts, templates, docs, example workflows
- Add a quickstart for Codex/Claude/Cursor/Gemini users
