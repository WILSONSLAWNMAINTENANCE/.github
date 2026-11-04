# Contributing

> **Joined the organisation?** Start with [`ONBOARDING.md`](./ONBOARDING.md): two-factor sign-in, connecting your AI helper, and how the work is done.

This is the default contributing guide for every repository under `WILSONSLAWNMAINTENANCE` that has no `CONTRIBUTING.md` of its own.

## Before you contribute

These pages are about a real business and its customers. Please:

- Never put prices, customer names or addresses, payment information or anything from the business's accounts in an
  issue, pull request or commit. Customer details never enter git here, by rule.
- Never put a password, a sign-in code or a key anywhere. Nobody here will ask for one.
- When you're unsure whether wording about the business is right, open an issue and ask first. Jeff decides what is
  said about the business.

## How to contribute

1. A small fix (a typo, a broken link) can go straight to a pull request into `main`.
2. For anything larger, open an issue first so it can be talked through.
3. A person with the role merges, **with a merge commit, never a squash**, so every author's credit survives. Helpers
   (AI assistants) open pull requests; they never merge.
4. Public rooms (`*-public`) are written by their syncs only. Change the private source instead.

## Commit messages: Gitmoji

Every commit subject starts with **one gitmoji in its colon form**, then a type, an optional scope, and the subject:

```text
:sparkles: feat(room): the welcome deck is linked from the front page
:bug: fix(sop): SOP-IT-002 points at the right team
:memo: docs(readme): the reading room explained in plain words
```

The twelve the fleet uses, and why the colon form, are in
[GITMOJI.md](https://github.com/drasticstatic/my-template/blob/main/GITMOJI.md). It is warn-only: a commit that doesn't
follow it still lands, with a one-line hint. Run `sh scripts/install-hooks.sh` once per clone for that hint and for the
secret scan. If an AI helped, credit it with one `Co-Authored-By:` line
([the spec](https://github.com/drasticstatic/my-template/blob/main/AGENT-SYNC/README.md)).

## Reporting problems

Security issues go through [`SECURITY.md`](./SECURITY.md), not a public issue. Anything else is welcome as an issue.
