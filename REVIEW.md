# Pull request review (gorfednet profile)

Read by the Claude reviewer (`.github/workflows/claude-review.yml`, which calls the shared workflow in `gorfednet/.github`) on every non-draft pull request and on a `claude review` comment. The shared workflow says what to report in general. This file holds what is particular to this repository.

## What this repository is

The public GitHub profile of Michael McArthur: `README.md` (shown on github.com/gorfednet) and `RESUME.md`. It holds prose and links only, no code.

## House rules to hold the change to

- Every word a visitor reads follows the content guidelines (`docs/content-guidelines.md` in `gorfednet/.github`, read from `origin/main`). Michael speaks as "I". Sentences are short, with at most 1 comma outside a list. No semicolons, em dashes or AI tells (an "X, not Y" antithesis, a colon-led punchline, a triad for rhythm).
- At most 1 sentence in 4 opens with "I", and a result takes the work as its subject.
- Digits for every number, dates as "25 October 2026", times in Eastern with ET, Canadian spelling (behaviour, colour, -ize).
- No process detail: say what shipped and who it's for, never how the checks work.
- Every link resolves and points at a public page. Name a repository only when it is public.
- The AI Use line stays in step with the spec version the repositories pin, with its tools ordered as the spec says.
- The profile never carries a private repository name, a secret, an address or a phone number beyond what `RESUME.md` already publishes.
- A check is never made green by weakening it.
- The 4th review round is a pull request's last for Low findings. From round 5, reply to each Low with fix, defer or decline; only High or Medium forces a fix.

## Where the rules live

- `gorfednet/.github` `docs/content-guidelines.md`, `~/.claude/rules/content-voice.md`
