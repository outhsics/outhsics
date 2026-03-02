# GitHub Brand Playbook (Big-Tech Ready)

This playbook is for maintaining a high-signal GitHub profile that recruiters and engineering managers can evaluate quickly.

## 1) Profile-Level Standards

- Profile README must answer in 10 seconds:
  - Who you are
  - What you build
  - What projects prove it
- Keep pinned repos aligned with current direction (avoid archived/legacy pins).
- Bio should be role-oriented, not generic motivation text.

## 2) Repository-Level Standards

Every active repository should have:

- Clear description (1 sentence, outcome-focused)
- 3-8 topics (`ai`, `automation`, `nextjs`, etc.)
- README first screen with:
  - problem
  - solution
  - quick start
  - architecture or workflow
- Maintenance signal:
  - recent commits
  - stable default branch
  - actionable issues/roadmap

## 3) Repo Status Model

Use one of these statuses in README:

- `active`
- `maintain`
- `incubating`
- `archive-candidate`
- `legacy`

If `archive-candidate`, archive first. Do not delete directly.

## 4) Quality Bar for Featured Repos

A pinned repo should satisfy at least 4 of 6:

1. Clear business/engineering value
2. Good README and structure
3. Recent activity (typically <= 180 days)
4. Reusable patterns/scripts
5. Reasonable code quality and project hygiene
6. Demonstrates differentiated capability

## 5) Monthly Maintenance Rhythm

Monthly 30-minute pass:

1. Run repo audit (`github_repo_audit.sh`)
2. Refresh active/maintain/archive-candidate lists
3. Archive next small batch (5-10)
4. Re-check pinned repos
5. Update profile README if focus changed

## 6) Interview-Oriented Evidence

Your top repositories should collectively prove:

- Product sense (problem -> solution)
- Engineering execution (architecture + delivery)
- Operational maturity (scripts, runbooks, automation)
- Communication quality (docs, issue hygiene, naming)

## 7) Anti-Patterns

- Empty descriptions for active repos
- Pinned archived repos
- README with no quick-start path
- Large number of stale demo/test repos kept unclassified
- Public repos with unclear ownership/purpose

## 8) Visual Style Strategy (Cool but Professional)

- Use visual polish for first impression: hero banner, compact badges, clear section rhythm.
- Avoid over-decoration that hurts trust: too many GIFs, long animations, noisy widgets.
- Keep "cool" elements to top area only; keep project evidence clean and scannable.
- Prioritize hiring signal over pure aesthetics:
  - flagship projects
  - recent shipping signal
  - clear value statements
