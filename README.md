# .github

Defaults GitHub applies to every repository of `abrosimov`, private ones included, that has no file
of the same kind of its own. Repositories do not carry their own copies: one set here keeps the
policy the same everywhere.

What every repository inherits:

- `.github/ISSUE_TEMPLATE/` — the bug report form; blank issues are open to maintainers only, and
  dependency requests are pointed to Renovate's Dependency Dashboard.
- `.github/pull_request_template.md` — the shape of a pull request description.

What cannot be inherited and lives in each repository instead: `LICENSE` (Apache-2.0, from
[repo-template](https://github.com/abrosimov/repo-template)), `CODEOWNERS`, labels, `dependabot.yml`
and the Renovate configuration (the shared preset is
[renovate-config](https://github.com/abrosimov/renovate-config)).

The defaults do not show in a repository's file list or in its clones. Labels a template sets must
exist in every repository that uses it; the bug form sets only `bug`, which GitHub creates in every
new repository.

GitHub reads these defaults only while this repository is public, so nothing private belongs here.
