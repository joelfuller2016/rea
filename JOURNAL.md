# Work journal

## 2026-11-07 — Owner fork preserved for machine recovery

- Request: create an owner-controlled fork before a possible computer format. The
  fork is https://github.com/joelfuller2016/rea, with upstream parent
  https://github.com/morluto/rea and default branch `main` at creation source
  `1a0e2c77f208bfb8d102dc68d75af3cc6f1a5a75`.
- Verification: GitHub parent/default-branch metadata and fetched Git HEAD agree.
  Before this journal entry, both remotes advertised246 branch/tag refs; three
  upstream branch targets had advanced relative to the fork snapshot. An identical
  latest upstream mirror is not claimed.
- Preservation scope: Git source/history is forked. Published release binaries,
  package caches and private application data are separate recovery assets. Portable
  adapter/setup recovery is tracked in
  https://github.com/joelfuller2016/codex-portable-settings/pull/9; the application
  plan is https://github.com/joelfuller2016/apply-studio/issues/1.
- This checkpoint changes only `JOURNAL.md` under the owner's standing journal
  publication rule. Existing installed checkouts, runtime configuration and product
  code are untouched. No upstream code, build, provider or browser action was run.
  Whitespace, staged-file scope and remote commit readback are the relevant checks.
