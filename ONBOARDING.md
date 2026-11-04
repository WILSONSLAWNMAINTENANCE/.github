# Welcome to Wilson's Lawn Maintenance on GitHub

*For people joining the organisation, and for the AI helpers who read beside them.*

**Never heard of GitHub? Start with [Opening your gift](OPENING-YOUR-GIFT.md)**: what Jeff was given, what to expect,
and the first ten minutes, in plain words. Five minutes, and it asks you for nothing.

## Who is who

- **Jeffrey Wilson**, the owner of Wilson's Lawn Maintenance, owns this organisation and decides everything said about
  the business. His seat is an owner's.
- **Christopher W** (`@drasticstatic`), Jeff's brother, with his helpers **Alfred** (Claude Code) and **Littlebird**,
  set this home up as a gift and keeps these pages. He is the second owner, so the business never depends on one
  person, and he is the one to message about any of it.

## The invitation waits for Jeff's username

Jeff's GitHub username is not known yet. Nothing here can invite him until it is, and nobody will guess: the invitation
goes to the username Jeff sends, and only that one. When he has made his account ([Opening your gift](OPENING-YOUR-GIFT.md)
says how, in ten minutes), one message to Christopher with the username is all it takes. Then:

1. Christopher invites that username as an **owner** of `WILSONSLAWNMAINTENANCE`.
2. An email from GitHub arrives (or a dot on the bell icon). **Join**, and the business's home is under Jeff's profile.

## Your first hour

[SOP-COM-001, *New to GitHub: your first hour*](https://github.com/WILSONSLAWNMAINTENANCE/ops-standard-operating-procedures-public/blob/main/COM/SOP-COM-001-new-to-github-your-first-hour.md)
walks it step by step. In short:

1. Your own account at `github.com/signup`. **You type your own password**; nobody else ever sees it.
2. Two-factor sign-in on (this organisation requires it). Keep the recovery codes with important papers.
3. Send only your **username** to Christopher. Accept the invitation (email, or the bell icon).
4. Open the reading room, [`WILSONSLAWNMAINTENANCE/reading-room`](https://github.com/WILSONSLAWNMAINTENANCE/reading-room), while signed in.

## What is private, what is public

| Public (anyone) | Private (owners, and the readers they name) |
|---|---|
| this `.github` repository: the profile, the [decks](decks/) | `reading-room`: everything written for the business |
| `brand-assets`: the logo and the photos, and who may use them | `proposals`: ideas offered to the business |
| `reading-room-public`: the [visitors' front page](https://WILSONSLAWNMAINTENANCE.github.io/reading-room-public/) | `ops-standard-operating-procedures`: every procedure |
| `ops-standard-operating-procedures-public`: the procedures listed for visitors | `legal`: the paperwork, for the owner and counsel only |

The organisation's base permission is **none**: a private repository is read only by owners and the teams given it.
Names of repositories may be public; their contents are not.

## Bringing your AI helper

Your helper (Claude, ChatGPT, Codex, Littlebird, any of them) reads what you can, never more:

- **Simplest:** give it the page and the PDF beside it.
- **Connected:** a read-only fine-grained token in your own account, for `reading-room` only, short expiry, pasted only
  into the helper's own settings ([SOP-IT-002](https://github.com/WILSONSLAWNMAINTENANCE/ops-standard-operating-procedures-public/blob/main/IT/SOP-IT-002-reading-room-and-helper-access.md)).
- **Never:** a password, a sign-in code, a recovery code, a bank login, a wallet's seed phrase.

A good first message: *"Read Start here in the reading room and tell me in five lines what is waiting for me.
Don't change anything."*

## How the work is done

- Changes arrive by pull request into `main`; a person merges with a merge commit (never a squash, never a helper).
- Commit subjects start with one gitmoji ([GITMOJI.md](https://github.com/drasticstatic/my-template/blob/main/GITMOJI.md)); `sh scripts/install-hooks.sh` once per clone.
- Asking for a change to any of these pages is still one message to Christopher (SOP-OPS-001). Nothing here is needed for that.
