# Bug Bounty & Responsible Disclosure

**Update:** Due to the high volume of AI-assisted attacks and analysis, the reward program is currently suspended. Voluntary vulnerability reports are still very welcome and greatly appreciated.

## Update on the Alephium Bug Bounty Program

As AI-assisted security research becomes increasingly widespread, the volume and nature of bug reports across the software industry are changing rapidly. High-quality vulnerability discovery is becoming more accessible, and this creates both opportunities and new operational challenges for open-source projects like Alephium.

The Alephium core team is currently conducting an internal AI-assisted security review of the codebase and infrastructure. This process includes auditing, triaging, and patching potential issues identified through internal tooling and analysis. During this phase, external bug reports may take longer than usual to review.

We remain committed to responsible disclosure and to working constructively with security researchers. However, reports will be evaluated in the context of the ongoing internal review, including whether the issue was already known, under investigation, or identified by our own auditing process.

Bug bounty rewards will continue to be assessed based on severity, impact, quality of the report, reproducibility, and the value added by the researcher. Given the growing role of AI-assisted discovery, we may also take into account the effort, originality, and cost involved in producing the report.

Alephium is an independent Layer 1 project with more limited resources than many larger ecosystems. While we deeply appreciate meaningful contributions to the security of the protocol, bounty expectations should remain realistic and aligned with the project’s available resources.

We thank the security community for helping keep Alephium safe and resilient.

## Coverage

This Program encompasses bugs and vulnerabilities across the entire operational Alephium environment. This scope extends to the GitHub repositories mentioned below:

- [Alephium](https://github.com/alephium/alephium)
- [Frontend](https://github.com/alephium/alephium-frontend)
- [Extension Wallet](https://github.com/alephium/extension-wallet)
- [Ledger Integration](https://github.com/alephium/ledger-alephium)
- [Web3 SDK](https://github.com/alephium/alephium-web3)
- [Explorer Backend](https://github.com/alephium/explorer-backend)
- [Website](https://github.com/alephium/www)
- [Website Bridge](https://bridge.alephium.org/)

*Nonetheless, if a bug in any Alephium-related repository is discovered, even if it doesn't fall within the ones listed, that puts users’ funds at risk, the team will contemplate the issue as part of the bounty's scope.*

Exclusions from the Program's coverage include:

- Third-party contracts outside Alephium's direct control
- Bugs in third-party contracts or apps utilizing Alephium code

## Rewards

Bug bounty rewards will continue to be assessed based on severity, impact, quality of the report, reproducibility, and the value added by the researcher. Given the growing role of AI-assisted discovery, we may also take into account the effort, originality, and cost involved in producing the report, as determined solely by Alephium. Rewards are ultimately determined within the means and resources available to the project at the time, alongside all other relevant factors.

## Disclosure

All found vulnerabilities or bugs must be exclusively reported to this email: **bugbounty@alephium.org**. 

Public disclosure of the vulnerability, or disclosure to any other individual, entity, or email address is prohibited before Alephium has been alerted, resolved the issue, and authorized public disclosure. Additionally, the vulnerability must be reported within 24 hours of its discovery.

A comprehensive report on a vulnerability increases the chances of a reward. Please supply as much information as possible about the vulnerability, including:

- The conditions that the bug reproduction depends on.
- Steps required to reproduce the bug or, ideally, a proof of concept.
- The potential repercussions of the vulnerability's exploitation.
- Any individual who reports a unique, previously unreported vulnerability that leads to a code alteration or configuration change, and maintains its confidentiality until its resolution by our engineers, may opt for public recognition for their contribution.

## Qualification

To qualify for a reward under this Program, you must:

- Comply with the [Program Rules](https://github.com/alephium/community/blob/master/RewardProgramRules.md) and meet its eligibility requirements.
- Identify a previously unreported, non-public vulnerability that the team isn't aware of and is within the Program's scope.
- Be the first to report the unique vulnerability to bugbounty@alephium.org, adhering to the reporting requirements.
- Provide enough information to help the core contributors understand, reproduce, and rectify the vulnerability.
- Not exploit the vulnerability in any manner, including making it public or obtaining profit (beyond this Program's reward).
- Refrain from publicizing the vulnerability in any form other than confidential reporting to us.
- Make a sincere attempt to prevent privacy infringements, data destruction, or disturbance of any in-scope assets.
- Not report a vulnerability rooted in the same issue that has already been rewarded under this Program.
- Not indulge in any illegal behavior while disclosing the bug to bugbounty@alephium.org, such as threats, demands, or any coercive tactics.

## Additional Terms

By submitting your report, you concede to Alephium any and all rights, including intellectual property rights, required to verify, alleviate, and disclose the vulnerability. We retain absolute discretion regarding all reward decisions, including eligibility for and amounts of rewards, and the payment method.

The terms and conditions of this Program can be modified at any time.
