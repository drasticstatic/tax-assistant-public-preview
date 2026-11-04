<div align="center">

<img src="../assets/icons/git-pull-request.svg" width="56" height="56" alt="">

# GitHub Pro: four dollars a month for a lock on the private desks

*The first proposal written against the expense ledger. Small, specific, and the kind of line a sole proprietor keeps on purpose.*

![Proposal](https://img.shields.io/badge/Proposal-001-d9a441?style=flat-square)
![Status](https://img.shields.io/badge/Status-asking-8a6a2a?style=flat-square)
![Started](https://img.shields.io/badge/Started-2026--11--04-b45309?style=flat-square)
![For](https://img.shields.io/badge/For-Christopher-64748b?style=flat-square)

</div>

## <img src="../assets/icons/compass.svg" width="24" height="24" alt=""> TL;DR

1. **The problem it solves.** On Nov 4, 2026 Kenney was given write access to `proposals-thef`, a private repository under Christopher's personal account. GitHub Free cannot put a rule in front of `main` on a private personal repository: the API answered "Upgrade to GitHub Pro or make this repository public to enable this feature" when the rulesets were read. The same limit will meet `ops-arb` and every other private desk shared with a partner.
2. **What Pro buys.** Repository rules and branch protection on private repositories (a pull request before anything lands on `main`, required checks such as the tripwire self-test and ggshield, required reviewers, CODEOWNERS), GitHub Pages on private repositories, and more Actions minutes. Price: **$4 a month** for an individual account, as GitHub's upgrade prompt and billing page name it; the public pricing page shows the organisation equivalent, Team, at $4 per user per month.
3. **What it does not buy.** Nothing for the organisations (THEF, PIR, ORG, Psanctuary, the Church, Taylor's, Jeff's): their private repositories would need Team, per member. The reading rooms are the right fence there, and they are free. Pro covers Christopher's own private repositories only.
4. **Until it is bought,** the watchdog on `proposals-thef` reports every push by anyone but the steward (WATCHDOG.md there). A watchdog barks; Pro is the lock.
5. **The expense line.** $48 a year, 100% business: every repository on the account is the work. It goes on the ledger the day it is bought, with the receipt's folder named.

## <img src="../assets/icons/footprints.svg" width="24" height="24" alt=""> Decision

| Door | Cost | What changes |
|---|---|---|
| **A. Buy Pro now** | $4/month | turn on rules for `proposals-thef`, `ops-arb` and any desk a partner can write to: pull request required on `main`, the tripwire self-test and ggshield as required checks, one review; the watchdog stays as the record |
| B. Wait | $0 | the watchdog is the only guard; every push is in history; fine for a drafting desk, thin for a desk holding procedures |
| C. Move shared desks into an organisation | $0 | read-only members become possible, but a lab desk stops being a lab desk; the reading rooms already give partners the read side |

Lean: **A**, when the next card cycle allows; **B** until then, with the watchdog in place.

## <img src="../assets/icons/users-round.svg" width="24" height="24" alt=""> The steps after buying

1. GitHub → Settings → Billing → Plans → Pro.
2. For each shared private desk: Settings → Rules → Rulesets → New branch ruleset: target `main`; require a pull request before merging (1 review); require status checks (the tripwire self-test, ggshield); block force pushes. The same for `preview` where a desk uses it.
3. Add a `CODEOWNERS` naming the steward for `PUBLIC-ALLOWLIST*.txt`, `.github/`, `scripts/`.
4. Add the row to [EXPENSE-LEDGER.md](EXPENSE-LEDGER.md) with the receipt's folder.

*Sources: GitHub's API message on `repos/drasticstatic/proposals-thef/rulesets` (2026-11-04); github.com/pricing (read 2026-11-04; Team $4 per user per month, Enterprise $21). Not tax advice: whether the line is deductible is a CPA's call; the ledger only keeps it honest.*
