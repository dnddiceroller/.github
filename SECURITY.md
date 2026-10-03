# Security

## Report a problem

Email **dev@dnddiceroller.com**. Please do not open a public issue.

Include:

- what you found and where
- the steps to reproduce it
- what you think it lets someone do

We reply as soon as we can, tell you what we plan to do, and credit you in the fix if you want credit.

## In scope

- Every public repo under [github.com/dnddiceroller](https://github.com/dnddiceroller).
- The randomness and receipt claims of [dnddiceroller.com](https://www.dnddiceroller.com), as written in [roll-verification-spec](https://github.com/dnddiceroller/roll-verification-spec). For example:
  - a receipt that names a beacon record the dice did not come from
  - a certificate page that says **match** when the beacon disagrees
  - a way to predict a beacon roll from public information
  - a way to make a roll fall back to device randomness without the receipt saying `+ device`

## Out of scope

- Findings that need a compromised device or browser.
- Denial of service and volume testing. Please do not load-test the live site.
- Reports from automated scanners with no working example.
- Social engineering of anyone involved.

## Please

- Test against your own rolls and your own account only.
- Give us a reasonable time to fix a problem before you publish it.

## Rewards

We do not run a bug bounty and promise no payment. We do say thank you, in public if you like.
