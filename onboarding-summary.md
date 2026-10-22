# Onboarding Demo Summary

A disposable, live GitHub-workflow demo built for a new teammate starting Monday — everything was created for real (no slides), so each step can be clicked through and inspected.

## Repository
- **Repo:** https://github.com/mcpmark-eval-liuhezi/onboarding-demo-2
- Public, initialized with a README, default branch `main`. Safe to delete after the walkthrough (a note to that effect is appended to the README).

## What was set up

1. **Issues broken into sub-issues** — A parent issue, "Onboarding checklist: day-1 setup" (https://github.com/mcpmark-eval-liuhezi/onboarding-demo-2/issues/1), with three sub-issues attached:
   - Set up the local development environment (#2)
   - Configure SSH keys and commit signing (#3)
   - Join the code review rotation (#4)

2. **Branch + runbook** — Branch `docs/onboarding-runbook` cut from `main`, carrying `ONBOARDING.md`, a short runbook whose checklist mirrors the three sub-issue titles exactly.

3. **Pull request** — "Add onboarding runbook" (https://github.com/mcpmark-eval-liuhezi/onboarding-demo-2/pull/5) from the branch into `main`.

4. **Review** — Reviewed like a teammate: an inline review comment on `ONBOARDING.md` (on the "Configure SSH keys and commit signing" checklist line), submitted as a plain **comment** review — not an approval, not a request for changes.

5. **Falling behind + sync** — While the PR was open, the README on `main` was edited directly (appending "Demo notes: disposable demo repo, safe to delete."), which left the PR behind its base. The PR branch was then updated from the base, bringing it back in sync.

6. **Merge + verification** — The PR was merged into `main`, `ONBOARDING.md` was read back from `main` to confirm it landed, and sub-issue #2 ("Set up the local development environment") was closed as completed.

## Demo script for Monday
Walk the new teammate through the links above in order: parent issue → sub-issues → PR → review comment → merge commit. Point out the "out-of-date" → "update branch" flow on the PR as the one non-obvious moment in the real workflow.
