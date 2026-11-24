
## Context & Links
- **Jira Ticket(s):** 
- **Solution Doc / DSD Ticket:** _(or N/A)_
- **Related PR(s) (`staging` / `migrations`):** _(or N/A)_

## Summary of Changes
<!-- Briefly describe what this PR does. For regressions caused by a previous PR, include: causing PR link, stacktrace, replication steps, root cause, and lesson learned. -->

## Evidence & Artifacts
<!-- Attach required screenshots/logs where applicable: Unit tests, Code coverage, local SonarQube/Snyk, DBeaver query plan + raw SQL, pre/post benchmark, or migration file tree + empty-migration check. -->

---

## Developer Contract (All boxes must be checked to merge)

### PR & Commits *(Required for all branches, including `uat`/`main`)*
- [ ] **PR Metadata:** Assigned to the committer, labeled properly (type, feature/epic, module, and target branch label), and tagged with the right reviewers (co-dev + squad QGK for `dev`/`migrations`; main QGK + Lead for `uat`/`main`).
- [ ] **Commits:** Follow `PRDV-XYZ - <present-tense message>`, have no duplicates, and accurately describe the patch.

### Code Quality & Verification *(Check if verified, or N/A for `uat`/`main`/sync PRs)*
- [ ] **Lint & Style:** Applied `ruff` linting and followed CoreBE Python Style Guidelines.
- [ ] **Tests & Coverage:** Added/updated unit tests (success & failure paths) and attached test + coverage screenshots showing coverage maintained or increased.
- [ ] **Security & Quality Scans:** Attached local SonarQube and Snyk scan results with no unresolved blockers.

### Conditional Checks *(Complete and attach evidence above, or verify N/A)*
- [ ] **Queries & Performance:** If adding/modifying queries or optimizing endpoints, attached raw SQL, DBeaver query plan, and pre/post benchmark *(or N/A)*.
- [ ] **Migrations & Regressions:** If adding migrations, verified `NULL`/`BLANK` safety for shared tables and attached file tree + empty-migration logs; if fixing a bug from a prior PR, documented root cause and lesson learned above *(or N/A)*.