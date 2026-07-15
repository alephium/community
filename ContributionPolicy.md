# A Temporary Change to How We Accept External Contributions

## What's changing

Effective immediately, Alephium core maintainers will not merge pull requests from external contributors we do not already know and trust. This applies across our core repositories:

- [Alephium](https://github.com/alephium/alephium)
- [Frontend](https://github.com/alephium/alephium-frontend)
- [Extension Wallet](https://github.com/alephium/extension-wallet)
- [Ledger Integration](https://github.com/alephium/ledger-alephium)
- [Web3 SDK](https://github.com/alephium/alephium-web3)
- [Explorer Backend](https://github.com/alephium/explorer-backend)

Contributors we already have an established working relationship with are unaffected by this change.

## Why now

Two things have changed recently, and both point in the same direction.

First, AI tools have changed what a pull request tells us about the person submitting it. A substantial, well-written patch used to imply substantial effort, and that effort was a reasonable proxy for good faith. That assumption is weaker today: it is now cheap to produce code, tests, and explanations that look like a serious, well-intentioned contribution regardless of the intent behind them. We use these tools ourselves, and we don't think the answer is to distrust everyone who uses AI — but we can no longer treat "this looks like a lot of careful work" as evidence of trustworthiness on its own.

Second, the risk is not limited to the code itself. CI/CD pipelines are part of the attack surface. GitHub Actions and the third-party actions our workflows depend on can carry their own vulnerabilities, and a seemingly harmless pull request can be enough to trigger a workflow run that leaks secrets or other sensitive information, even without a maintainer ever approving the code inside it. Combined with the possibility of subtle, hard-to-spot changes designed to introduce a vulnerability rather than an obvious bug, an unfamiliar PR today carries more risk than it did a few years ago.

Alephium is a Layer 1 protocol that secures real value and runs against untrusted input from the network by design. The cost of a single overlooked issue is high, and the person who decides to merge a change is the person who has to answer for what happens next. Right now, we think that person should be someone we already know.

## What this means in practice

- **PRs from contributors we know:** business as usual.
- **PRs from contributors we don't know:** we will not merge them or run them through CI as submitted. If a PR contains genuinely good work, a maintainer will reproduce the change independently — reading it for understanding, then reimplementing or verifying it ourselves before it goes anywhere near the codebase — and credit the original author in the original PR or issue thread. We are not asking anyone to resubmit through some other channel; there isn't a separate process for getting code in by another route.
- **This is a precaution, not a permanent policy.** It's tied to the current moment, where AI-assisted attacks and the tooling to defend against them are both moving quickly and unevenly. We'll revisit this as the picture becomes clearer, not on a fixed timeline.

## What isn't changing

Alephium remains open source, and outside involvement still matters. Bug reports, security disclosures, reproductions, technical discussion, and design feedback are all still welcome and still the best way to help — see our [Bug Bounty & Responsible Disclosure](https://github.com/alephium/community/blob/master/BugBounty.md) program for the vulnerability reporting process. What's changing is who merges code into the project, not whether outside expertise is valued.

We're grateful to everyone who has contributed to Alephium over the years, and to those whose work continues to make it in through this new process, even if it now arrives with a maintainer's name on the commit instead of their own.
