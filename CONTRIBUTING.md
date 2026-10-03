# Contributing

Thanks for picking up the dice. This file covers every public repo under [github.com/dnddiceroller](https://github.com/dnddiceroller) unless a repo has its own.

## What lives here

These repos are the public side of [dnddiceroller.com](https://www.dnddiceroller.com): specs, small tools and runnable examples. The production site is maintained privately, so a pull request here changes these repos, not the live roller. [open-source.md](https://github.com/dnddiceroller/engineering-handbook/blob/main/docs/open-source.md) explains the split.

| Repo | Good first contributions |
| --- | --- |
| [roll-verification-spec](https://github.com/dnddiceroller/roll-verification-spec) | A sentence that confused you, a claim that reads stronger than the spec supports |
| [dice-probability-tools](https://github.com/dnddiceroller/dice-probability-tools) | New notation, a wrong number, a missing test against brute force |
| [examples](https://github.com/dnddiceroller/examples) | A receipt that failed to verify, a clearer script |
| [engineering-handbook](https://github.com/dnddiceroller/engineering-handbook) | A rule that reads wrong, a term missing from the glossary |

## Found a problem with the live site?

Open an issue in the repo closest to it, or email dev@dnddiceroller.com. Security problems go to [SECURITY.md](SECURITY.md), never a public issue.

## Before you open a pull request

1. **Open an issue first** for anything bigger than a typo. It saves you building something we would not merge.
2. **One pull request, one job.** The branch name says what it does.
3. **No new dependencies.** Every repo here runs on Node 20 or later with nothing to install. Keep it that way.
4. **Run the tests.** `node --test` where a repo has them. Paste the output in the pull request.
5. **Measure, don't assert.** A claim about odds, speed or size comes with the command that produced it.
6. **Keep it reversible.** One revert should undo your change.

## Writing

The docs are for players and developers who have never seen our code.

- Short sentences. Active voice. Present tense.
- Say what a receipt proves, and what it does not. Never round a claim up.
- Plain words first. Put the term in the [glossary](https://github.com/dnddiceroller/engineering-handbook/blob/main/docs/glossary.md) if it needs one.

The [engineering handbook](https://github.com/dnddiceroller/engineering-handbook) has the full rules we build by.

## Licence

Code is MIT. Handbook prose is CC BY 4.0. By contributing you agree your work ships under the licence of the repo you contribute to.

## Conduct

Everyone here follows the [Code of Conduct](CODE_OF_CONDUCT.md). Be the player people want back at the table.
